---
layout: post
title: "Asombra y Sorprende, regala arte" 
share: true
work: 3338
---

{% assign work_data = site.data.works.casals | where:"id", page.work %}
{% assign work = work_data | first %}
<figure class="text-center">
	<img src="{{ work.featured_src }}">
	<figcaption>
		<p><small><strong>{{ work.title }}</strong> | {% if work.downloadable == true %} digital art{% else if %} dimensions: {{ work.dimensions.length }}x{{ work.dimensions.height }} {{ work.dimensions.unit }}{% endif %}</small></p>
		<p><a href="{{ work.permalink }}" class="btn btn-primary btn-lg">{{ work.price_html }}! comprar! <i class="fa fa-credit-card"></i></a></p>
	</figcaption>
</figure>

Regala arte, es la mejor opción para todos aquellos que busquen hacer **un regalo** no solo sorprendente y conmovedor si no también **emotivo, personal y exclusivo**.  En [Artinpocket](http://www.artinpocket.cat/) os animamos a que apostéis por una obra de arte por eso te ofrecemos **más de 500 obras de arte de jóvenes creadores a precios asequibles** dónde de bien seguro encontrarás una pieza especial para regar. 

¿Si tienes que hacer un regalo a un  familiar, amigo o a tu pareja? Seguramente te encuentras perdido pensando en cómo ser original y sorprender, Artinpocket te propone un amplio abanico de posibilidades donde podrás elegir entre escultura, pintura, obra gráfica a precios al alcance de tu bolsillo.

Si tu presupuesto está más limitado, obra gráfica o fotografía, ya que ambas nos permiten disfrutar del arte a precios realmente asequibles, nuestro lema es **¿el arte es caro? NO SIEMPRE ¿El arte es para una minoría? FALSO**. 