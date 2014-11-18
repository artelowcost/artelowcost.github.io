---
layout: post
og: true
og-type: article
title: "Un regalo para siempre, el Arte nunca pasa de moda" 
share: true
work: 3352
---

{% assign work_data = site.data.works.artworks | where:"id", page.work %}
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

¿Porque caer en el eterno consumismo de cada año? ¿Por qué regalar siempre las mismas cosas que no aportan nada y que al poco tiempo se consumen o se quedan obsoletas? **El Arte nunca pasa de moda y la belleza de un lienzo, una escultura o una fotografía podría deteriorarse pero nunca desaparecer**. 

Sea cual sea la obra de arte por la que decidas será el fruto de la creatividad de un artista que ha invertido muchas horas en concebirla y realizarla. Cuando te la lleves a casa y se la ofrezcas a esa persona tan especial piensa que también le estás regalando un poco de su tiempo y un trocito de tu alma. 

**¿Y si estas Navidades regalas Arte? con [#Empocionart](http://www.emocio-nart.com/artworks/) os ofrecemos la posibilidad de acceder a obras de arte originales de jóvenes creadores a un precio accesible y unas condiciones únicas**, más de 60 creadores y cerca de 500 obras te esperan en [Artinpocket](http://www.artinpocket.cat/tienda/?orderby=price&min_price=25&max_price=300) seguramente alguna de ellas se adapte a tu gusto y a tu bolsillo. En Artinpocket ya lo decimos **¿el arte es caro? ¡No siempre! ¿El Arte es para una minoría? ¡Falso!**
