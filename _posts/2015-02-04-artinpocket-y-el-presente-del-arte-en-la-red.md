---
layout: post
og: true
og-type: article
title: "Artinpocket y el presente del arte en la red" 
share: true
work: 4096
---

{% assign work_data = site.data.works.artworks | where:"id", page.work %}
{% assign work = work_data | first %}
<figure class="text-center">
	<div class="padding-artwork-container">
		<div class="embed-container embed-container_16-9">
			<core-image sizing="cover" class="core-image-size" preload fade src="{{ work.featured_src }}"></core-image>	
		</div>
	</div>
	<figcaption>
		<p><small><strong>{{ work.title }}</strong> | {% if work.downloadable == true %} digital art{% else if %} dimensiones: {{ work.dimensions.length }}x{{ work.dimensions.height }} {{ work.dimensions.unit }}{% endif %}</small></p>
		<p><a href="{{ work.permalink }}" class="btn btn-primary btn-lg">¡{% if sale_date > site.sale-end %}{{ work.regular_price }}{% else if %}{{ work.price_html }}{% endif %}! ¡comprar! <i class="fa fa-credit-card"></i></a></p>
	</figcaption>
</figure>

La empresa Inditex facturó 553 millones de euros sólo en venta online en el 2014, un 42% más que el ejercicio anterior; la venta online de viajes aumentó un 9% llegando a facturar 9.300 millones; la cadena de distribución americana Walmart creció un 27% en la facturación de su venta por internet; Amazon, el gran gigante de las ventas online, se supera con un 22’4% más que los años anteriores. Así que, **¿las ventas online son el futuro del comercio?** La respuesta es clara y evidente: **NO, es el PRESENTE**.

Lo mismo tiene que pasar en el mundo del arte. Entre artistas, galerías y compradores mueven un total de unos 300 millones de euros al año, pero sólo el 5% se genera de manera online.  Es por esto que **[Artinpocket](http://www.artinpocket.cat/) se ha decantado para llevar el mundo del arte al presente en lo que compra y venta se refiere**. Ya no hace falta ir a una galería para comprar arte, sino que Artinpocket ha creado una selección de artistas y obras que **puedes comprar desde donde más te convenga**. Y lo que es más interesante, ya no hace falta tener las cuentas llenas, puedes encontrar obra de artistas contemporáneos a muy bajo coste. Por 5 euros ya te puedes convertir en mecenas de arte!

**[Artinpocket](http://www.artinpocket.cat/)** es justamente eso, un portal online que te facilita el acceso al arte y asequible para todos. 