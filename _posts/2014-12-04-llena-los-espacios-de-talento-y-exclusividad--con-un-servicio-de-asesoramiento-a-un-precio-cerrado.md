---
layout: post
og: true
og-type: article
title: "Navidad 2014, un regalo con doble sensibilidad" 
share: true
work: 3594
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

Esta Navidad [Down Catalunya](http://sindromedown.cat/es/) y **[Artinpocket](http://www.artinpocket.cat/)** proponen hacer **un regalo con doble sensibilidad**. [#DoblementeSensible](https://twitter.com/hashtag/doblementesensible) es una propuesta que tiene como objetivo financiar las actividades que lleva a cabo la Coordinadora Síndrome de Down de Cataluña y fomentar la compra de arte como regalo alternativo y sensible con la creación artística.

- ¿Quieres saber cómo ser #DoblementSensible? Esta Navidad lo tienes muy fácil, con una propuesta exclusiva que te permite
- Fomentar la compra de arte como regalo alternativo y sensible con la creación artística.
- Ayudar a financiar las acciones de la Coordinadora Síndrome de Down de Cataluña

El 10% del importe de todas las ventas que se hagan durante toda la campaña de Navidad y Reyes a través de Artinpocket se destinarán a Down Cataluña.

**El dibujante KAP ha creado y cedido la ilustración** ***[Especiales como todos]({{ work.permalink }})*** de edición limitada de 100 ejemplares a un precio de 40 € el ejemplar que se podrá adquirir de forma exclusiva en el portal de Artinpocket. En este caso el **90% del importe de esta obra irá destinada a Down Catalunya**.