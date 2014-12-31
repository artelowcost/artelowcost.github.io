---
layout: post
og: true
og-type: article
title: "Regala original, regala Artinpocket" 
share: true
work: 2280
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

¿Aún no sabes qué regalar por estas fiestas de Navidad y Reyes? ¡Ya queda muy poco tiempo! Si estás cansado de pensar qué puedes comprar y que sea original, o si estás harto de regalar siempre lo mismo, no lo dudes y date una vuelta virtual por **[Artinpocket](http://www.artinpocket.cat/)**. Allí encontrarás más de 500 obras (pintura, grabado, arte digital, fotografía, escultura,…) de arte contemporáneo de distintos artistas emergentes a muy bajo coste. Si no sabes qué obra regalar, **Artinpocket** te facilita la compra con el **[cheque regalo](http://www.artinpocket.cat/tienda/cheque-regalo-navidad-2014/)**. Tan simple como poner la cantidad que deseas regalar y listo.

Para esta campaña de Navidad 2014, puedes adquirir una obra del proyecto [#DoblementSensible](https://twitter.com/hashtag/doblementsensible): con la compra de la obra “[Especials com tothom](http://www.artinpocket.cat/tienda/especials-com-tothom-kap-2014/)” de Kap (edición limitada de 100 ejemplares) ayudas a financiar las actividades que lleva a término la [Coordinadora Síndrome de Down de Catalunya](http://sindromedown.cat/ca/), así como fomentar la compra de arte como regalo alternativo y sensible con la creación artística. Además, por cada venta de piezas de arte para estas fechas, Artinpocket destinará el 10% a Down Catalunya.

Mucha gente no sabe como aproximarse al arte contemporáneo actual y, aún menos, qué obra comprar. Para empezar se tiene que tener muy claro el presupuesto que se dispone. A partir de aquí, no hace falta ser un experto en arte, básicamente es recomendable comprar cualquier obra que te guste. A lo mejor compras una pieza del futuro gran artista. Nunca se sabe, ¡recuerda que Van Gogh sólo vendió un cuadro en vida y ahora se pagan por millones!
Así que, por **estas Navidades regala arte gracias a Artinpocket**: una obra original y exclusiva que se convierte en un regalo original.
