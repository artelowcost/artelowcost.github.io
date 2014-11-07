---
layout: post
og: true
og-type: article
title: "Llena tu casa de talento y emoción" 
share: true
work: 2084
---

{% assign work_data = site.data.works.lalaia | where:"id", page.work %}
{% assign work = work_data | first %}
<figure class="text-center">
	<div class="padding-artwork-container">
		<div class="embed-container embed-container_4-3">
			<core-image sizing="cover" class="core-image-size" preload fade src="{{ work.featured_src }}"></core-image>	
		</div>
	</div>
	<figcaption>
		<p><small><strong>{{ work.title }}</strong> | {% if work.downloadable == true %} digital art{% else if %} dimensiones: {{ work.dimensions.length }}x{{ work.dimensions.height }} {{ work.dimensions.unit }}{% endif %}</small></p>
		<p><a href="{{ work.permalink }}" class="btn btn-primary btn-lg">¡{% if sale_date > site.sale-end %}{{ work.regular_price }}{% else if %}{{ work.price_html }}{% endif %}! ¡comprar! <i class="fa fa-credit-card"></i></a></p>
	</figcaption>
</figure>

Imagina, crea y renueva con [Artinpocket](http://www.artinpocket.cat/). Sé diferente, en Artinpocket queremos que decores a tu manera y a tu estilo, por eso **hemos preparado para ti la mejor selección de obras de arte para que tu casa sea única**. Te ofrecemos más de 700 obras para elegir: foto, grabado, escultura, collage... ¡Consigue el toque que buscas para tu salón y marca la diferencia.

Efecto único y personalizado: Paisaje, geometrías, colores... elijas lo que elijas conseguirás un efecto único. Atrévete e investiga, **[descubre y emociónate](http://www.emocio-nart.com/)** con las obras de arte de Artinpocket. Si tienes dudas [contacta](mailto:info@artinpocket.cat?subject=Quiero llenar mi casa con Artinpocket) con nosotros y te ayudamos.