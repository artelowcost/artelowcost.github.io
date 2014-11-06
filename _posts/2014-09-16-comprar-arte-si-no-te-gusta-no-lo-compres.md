---
layout: post
title: ¿Comprar arte? si no te gusta no lo compres  
share: true
work: 1863
---

{% assign work_data = site.data.works.martacarrete | where:"id", page.work %}
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

Una de las primeras tareas para comprar arte es marcar el presupuesto que vas a dedicar. No puedes olvidar que el mercado es muy amplio y puedes adquirir obras originales de jovenes creadores desde unos pocos cientos de euros. Si tu presupuesto no es muy alto, **la fotografía, el grabado o el arte contemporáneo realizado por artistas emergentes como los que te ofrece [Artinpocket](http://www.artinpocket.cat/) son una gran opción**. Escojas el tipo de arte que escojas y sea cual sea el presupuesto que te marques cíñete a él y no lo sobrepases bajo ningún concepto.

Sin lugar a dudas y en segundo lugar pero no menos importante y fundamental para comprar una obra de arte es que te guste. Si no te gusta es por algún motivo.  ¿Su estética no encaja dentro de tus gustos? ¿Es el color? O a lo mejor estás detectando algo que no debería estar ahí, algo que quizás pase desapercibido a los demás, pero que de algún modo reste valor a la obra. ¿Comprar arte? ¡Si no te gusta no lo compres!

Por último tómate un respiro y todo el tiempo que necesites para decidir qué tipo de obra vas a comprar y en qué tipo de piezas quieres, te gusta y puedes comprar por presupuesto. En la web de Artinpocket presentamos **nuestra exclusiva oferta de piezas de arte original a un precio asequible**. Una oferta de obras de arte de más de 500 obras disponibles para comprar arte on line.