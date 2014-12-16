---
layout: post
og: true
og-type: article
title: "Ésta Navidad, más sensibilidad" 
share: true
work: 2970
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

**[Artinpocket](http://www.artinpocket.cat/)** nace con la voluntad de facilitar la compra de arte contemporáneo por parte del público. Nuestra misión es **dar accesibilidad al mercado del arte**. Te damos la oportunidad de transformar cualquier espacio con la adquisición de obras de arte emergente que ayudarán a darle tu toque personal.

¿Necesitas un nuevo aire en tu oficina? ¿En tu local? ¿En tu habitación? Paséate por nuestra galeria online y podrás **descubrir nuevos talentos**. Actualemente disponemos de más de 500 obras de arte y la comunidad crece dia tras dia para **llevar a tu casa lo mejor de la creación contemporánea**.

¿Cómo funciona? Sólo tienes que escoger la obra que más te guste, realizar la compra mediante nuestra plataforma online y nosotros nos encargamos de llevártela a casa con nuestro servicio de paquetaría. ¿Y si al final no te convence? No te preocupes, puedes devolverla sin ningún carlgo adicional. ¿Todavía estás dudando?

Queremos llevarte a los artistas con más talento, por eso en nuestra galeria sólo representamos artistas que han estado **seleccionados por nuestro equipo de comisarios**. ¡Convertirse en un coleccionista de arte nunca fue tan fácil!

Si lo que buscas es hacer un regalo especial, ahora mismo puedes disfrutar de descuentos especiales en nuestra web, para que **ésta Navidad** puedas regalar **piezas de arte únicas y exclusivas con certificado de autenticidad**.