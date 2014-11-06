---
layout: post
title: ¡El mundo del arte será digital!  
share: true
work: 2087
---

{% assign work_data = site.data.works.lalaia | where:"id", page.work %}
{% assign work = work_data | first %}
<figure class="text-center">
	<div class="padding-artwork-container">
		<div class="embed-container embed-container_3-1">
			<core-image sizing="cover" class="core-image-size" preload fade src="{{ work.featured_src }}"></core-image>	
		</div>
	</div>
	<figcaption>
		<p><small><strong>{{ work.title }}</strong> | {% if work.downloadable == true %} digital art{% else if %} dimensiones: {{ work.dimensions.length }}x{{ work.dimensions.height }} {{ work.dimensions.unit }}{% endif %}</small></p>
		<p><a href="{{ work.permalink }}" class="btn btn-primary btn-lg">¡{% if sale_date > site.sale-end %}{{ work.regular_price }}{% else if %}{{ work.price_html }}{% endif %}! ¡comprar! <i class="fa fa-credit-card"></i></a></p>
	</figcaption>
</figure>

Todo el mundo lo sabe, pero pocos lo dicen en voz alta. **El arte y su consumo serán digitales**. Seguramente por esto el ámbito comercial y el arte de Internet se están acercando y aparecen diferentes propuestas artísticas pero también nuevas plataformas y productos para poder consumir y disfrutar del nuevo formato digital.  
 
Nos ha tocado vivir una época de transformaciones, una transformación y revolución fascinante **vivimos en una era en donde el efecto completo de la revolución digital que comenzó un par de décadas atrás aún está desenvolviéndose** y donde hay mucho por hacer, innovar, proponer e incluso inventar. Se está gestando un cambio profundo en distintos sistemas que habían sido establecidos por un sector del arte tradicional: un mercado clásico del arte que está formado por grandes ferias, casa de subastas y coleccionistas que todavía funciona muy bien, especialmente porque el campo artístico “tradicional” está compuesto principalmente por piezas físicas como pinturas, impresiones, esculturas e instalaciones. Todavía hoy una obra enmarcada que cuelga sobre la pared tiene un lugar muy importante en el ámbito comercial. Pero **poco a poco toma más importancia un arte inmaterial y puramente conceptual, el arte digital** poco a poco formará parte de nuestras vidas y las futuras generaciones sin lugar a dudas convivirán con obras digitales siendo consumidas en entornos digitales. 

Quedan muchas preguntas e incógnitas al respecto: por ejemplo determinar qué es arte digital y qué no es Arte digital. ¿Cómo se va autentificar una obra digital? Un debate sin duda apasionante dónde no sólo van a intervenir los críticos, instituciones o coleccionistas el nuevo entorno digital abre la puerta e invita a participar en este proceso a nuevos actores: los propios consumidores. **¡El mundo del arte será digital!** 