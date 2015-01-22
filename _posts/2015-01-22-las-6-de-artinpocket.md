---
layout: post
og: true
og-type: article
title: "Las 6 de artinpocket" 
share: true
work: 4006
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

##¿Qué? 
**[Artinpocket](http://www.artinpocket.cat/)** es una comunidad que promociona y vende arte de creadores contemporáneos accesible con un solo clic. Si te gusta el arte, quieres ser mecenas, iniciar una colección, decorar una habitación o simplemente disfrutar del arte,  sólo tienes que entrar en la web. ¡Hay más de 500 obras para escoger! Piensa que es una plataforma especializada que reúne **la promoción del arte, los artistas y las galerías con un canal de venta directa** de obras artísticas.

##¿Cuándo?
**[Artinpocket](http://www.artinpocket.cat/)** es una galería de arte contemporáneo que está **abierta los 365 días al año y con un horario muy flexible de 0h a 24h**. No hay excusas, Artinpocket no cierra para ti, puedes comprar arte siempre que quieras y tanto como quieras. Por cualquier duda puedes ponerte en contacto con nosotros y podremos ayudarte con lo que haga falta. Pero recuerda, los gustos son muy personales, deja que ellos también te aconsejen!

##¿Cómo?
Facilísimo, sólo tienes que ir a la web de **[Artinpocket](http://www.artinpocket.cat/)**, navegar por las más de 500 obras de distintos artistas contemporáneos, encontrar la obra o las obras que te gustan, clicar en “añadir en el carrito” y pagar. **Fácil, rápido y cómodo**. ¿Que no lo quieres comprar de momento? Guárdalo en tu **lista de deseos** y recupérala más adelante. ¿Que quieres hacer un regalo? Más facilidades, puedes adquirir un **cheque regalo**, pones la cantidad de euros que quieres invertir y lo reenvías a quien tu quieras regalar. Así seguro que lo aciertas!

##¿Por qué?
La voluntad de **[Artinpocket](http://www.artinpocket.cat/)** es transformar y renovar el canal de proyección tradicional a partir de la construcción de una comunidad que fomente y estimule la compra de arte. Hasta ahora, la consumición del arte era por las vías más tradicionales, pero esto tiene que evolucionar al mismo ritmo que el propio arte. De aquí viene el objetivo de artinpocket, **acercar el arte y que la gente lo pueda consumir a muy bajo coste** a través de un entorno on line.

##¿Quién?
El mundo de la compra y venta de arte mueve más de 300 millones de euros al año, pero la gran mayoría queda en manos de las grandes fortunas. En cambio, la voluntad de **[Artinpocket](http://www.artinpocket.cat/)** es poder acercar la compra de arte a **todos los bolsillos, ya que puedes encontrar obras a partir de los 5€**. Anímate, obras creadas por creadores a muy bajo coste. Todos podemos tener una obra de arte!

##¿Dónde?
Muy simple: donde tu quieras. **Sólo hace falta una conexión a Internet** y tener un dispositivo para conectarte a **[Artinpocket](http://www.artinpocket.cat/)**. 

**[Artinpocket](http://www.artinpocket.cat/)**: accesibilidad y asequibilidad del arte de nuestros días!