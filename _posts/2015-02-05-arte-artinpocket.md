---
layout: post
og: true
og-type: article
title: "¿Arte? Artinpocket" 
share: true
work: 4067
---

{% assign work_data = site.data.works.artworks | where:"id", page.work %}
{% assign work = work_data | first %}
<figure class="text-center">
	<div class="padding-artwork-container">
		<div class="embed-container embed-container_4-4">
			<core-image sizing="cover" class="core-image-size" preload fade src="{{ work.featured_src }}"></core-image>	
		</div>
	</div>
	<figcaption>
		<p><small><strong>{{ work.title }}</strong> | {% if work.downloadable == true %} digital art{% else if %} dimensiones: {{ work.dimensions.length }}x{{ work.dimensions.height }} {{ work.dimensions.unit }}{% endif %}</small></p>
		<p><a href="{{ work.permalink }}" class="btn btn-primary btn-lg">¡{% if sale_date > site.sale-end %}{{ work.regular_price }}{% else if %}{{ work.price_html }}{% endif %}! ¡comprar! <i class="fa fa-credit-card"></i></a></p>
	</figcaption>
</figure>

Muchos se pueden hacer esta pregunta, ¿Para qué sirve el arte? Pero, ¿realmente el arte tiene que valer sólo para una cosa? Unos pueden defender que tiene una funcionalidad meramente estética, otros la de reflejar la realidad, algunos dirán que es una forma atractiva de explicar un mensaje, hasta habrá quien dirá que puede ayudar a cambiar el mundo y, esperemos, unos pocos pueden pensar que no tiene ninguna utilidad. Cada cual que extraiga sus propias conclusiones.

Pero una cosa es cierta, cada persona tiene su propia visión del arte y este no puede entenderse como tal si no hay alguien que lo mira, lo disfruta, lo interpreta,.. **Una obra no está terminada cuando el artista da el último toque de pincel, sino que está terminada cuando hay un espectador**. Una obra puede tener mil interpretaciones y todas pueden ser igual de válidas. En el fondo, el arte no está cerrado en si mismo, el arte es diálogo y nosotros somos los receptores y transmisores de esta conversación.

Y aquí es donde entra con fuerza Artinpocket. Visita la web, mira las obras, interprétalas, dales contenido, conoce a nuevos artistas, visualiza las galerías online,... y si encuentras la obra que realmente te “habla”, no lo dudes, cómprala. Artinpocket te acerca al arte y, como verás, a muy bajo coste. Puedes convertirte en un mecenas fácilmente y sin dejarte una fortuna. Llena tu casa de arte, pero también tus dispositivos electrónicos con la selección de arte digital (hecho y pensado para ser consumido en soportes digitales). **[Artinpocket](http://www.artinpocket.cat/) es una comunidad de venta de arte en continuo movimiento**.

Así que, ¿Para qué sirve el arte? Hay múltiples y personales interpretaciones. Y ¿Artinpocket? **Para facilitarte y acercarte a un consumo de arte adaptado a los tiempos en los que estamos**. 