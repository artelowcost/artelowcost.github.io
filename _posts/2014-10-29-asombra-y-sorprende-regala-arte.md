---
layout: post
og: true
og-type: article
title: "Asombra y Sorprende, regala arte" 
share: true
work: 3338
---

{% assign work_data = site.data.works.casals | where:"id", page.work %}
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

Regala arte, es la mejor opción para todos aquellos que busquen hacer **un regalo** no solo sorprendente y conmovedor si no también **emotivo, personal y exclusivo**.  En [Artinpocket](http://www.artinpocket.cat/) os animamos a que apostéis por una obra de arte por eso te ofrecemos **más de 500 obras de arte de jóvenes creadores a precios asequibles** dónde de bien seguro encontrarás una pieza especial para regar. 

Si tienes que hacer un regalo a un  familiar, amigo o a tu pareja, seguramente te encuentras perdido pensando en cómo ser original y sorprender. **[Artinpocket](http://www.artinpocekt.cat/)** te propone un amplio abanico de posibilidades donde podrás elegir entre escultura, pintura, obra gráfica a precios al alcance de tu bolsillo.

Si tu presupuesto está más limitado, obra gráfica o fotografía, ya que ambas nos permiten disfrutar del arte a precios realmente asequibles, nuestro lema es **¿el arte es caro? NO SIEMPRE ¿El arte es para una minoría? FALSO**. 
