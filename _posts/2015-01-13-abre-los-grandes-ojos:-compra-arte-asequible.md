---
layout: post
og: true
og-type: article
title: "Abre Los (Grandes) Ojos: Compra Arte Asequible" 
share: true
work: 3883
---

{% assign work_data = site.data.works.artworks | where:"id", page.work %}
{% assign work = work_data | first %}
<figure class="text-center">
	<div class="padding-artwork-container">
		<div class="embed-container embed-container_9-16">
			<core-image sizing="cover" class="core-image-size" preload fade src="{{ work.featured_src }}"></core-image>	
		</div>
	</div>
	<figcaption>
		<p><small><strong>{{ work.title }}</strong> | {% if work.downloadable == true %} digital art{% else if %} dimensiones: {{ work.dimensions.length }}x{{ work.dimensions.height }} {{ work.dimensions.unit }}{% endif %}</small></p>
		<p><a href="{{ work.permalink }}" class="btn btn-primary btn-lg">¡{% if sale_date > site.sale-end %}{{ work.regular_price }}{% else if %}{{ work.price_html }}{% endif %}! ¡comprar! <i class="fa fa-credit-card"></i></a></p>
	</figcaption>
</figure>

Hace apenas un par de semanas se ha estrenado en las salas de cine [la nueva película de Tim Burton, Big eyes](http://www.imdb.com/title/tt1126590/?ref_=nv_sr_1). ¿La habéis visto? Basada en hechos reales, relata la vida de la pintora [Margaret Keane](http://es.wikipedia.org/wiki/Margaret_Keane) que con sus cuadros de niños de grandes ojos tuvo una gran popularidad en la Norteamérica de mediados del siglo XX, pero el que se llevaba el mérito y éxito era su marido Walter, el cual se atribuía la creación de las obras. Sin entrar en valoraciones, la cinta nos va muy bien para poder ver como se empezó a gestar una nueva forma de compra de arte. Cuidado que va algún spoiler, pero no os preocupéis que no son relevantes para la trama.

En un momento del film, cuando las obras de Keane  empiezan a ser muy populares, la gente arranca los posters de publicidad de la galería para poder llevárselos a casa. Walter, que otra cosa no, pero es un gran comerciante, hace reproducciones de las obras y las vende a unos precios asequibles, lo cual les comporta mayores beneficios que no la venta de la obra original en sí. **De esta manera se inició un nuevo consumo del arte, ya no sólo para una élite con grandes cuentas bancarias, sino que entraba en las casas de las clases populares**. Estas personas querían tener una pieza como fuera, para ellos lo importante es tener la obra, y no que ésta sea única y original. Y todo esto a pesar que el gran crítico de arte del New York Times, John Canaday, se empeñaba a desacreditar y desvalorizar las obras de Keane.

**Este mismo concepto de accesibilidad del arte es lo que podemos encontrar en [Artinpocket](http://www.artinpocket.cat/)**, donde puedes comprar una gran cantidad de **obras de arte contemporáneo a unos precios muy económicos**, hay obras a partir de los 5€! Y te recomendamos lo mismo que hicieron los que adquirieron obra de Keane, compra la pieza que te guste más allá de lo que opinen los expertos, los cuales pueden ayudar, pero los gustos son personales y intransferibles!