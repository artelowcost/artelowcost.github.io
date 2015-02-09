---
layout: post
og: true
og-type: article
title: "Consumir arte" 
share: true
work: 4065
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

Des de que el ser humano existe como tal ha tenido la necesidad de crear arte. Y aún diría más, **ha tenido la necesidad de disfrutarlo y exponerlo, mostrarlo**, ya sea en una cueva, al aire libre, en un museo, en una galería, en la pared de un despacho o en una página web. Este último caso lo tenemos con **[Artinpocket](http://www.artinpocket.cat/)**, que tiene la **voluntad de acercar el arte de los creadores contemporáneos a todo aquel que lo quiere apreciar y, finalmente, comprar**.

El arte, en el fondo y aunque a muchos les pese, es un producto de consumo. La misma concepción del arte es que la obra no es tal hasta que alguien más que el artista la observa y la interpreta, se la hace suya. Es allí donde se termina y se completa. Por lo tanto, es un producto que se puede vender y comprar, pero cuidado, no es un producto de consumo “más”. Es complicado tratar temas económicos cuando hablamos de productos culturales, y más cuando se trata del arte, sobretodo del visual y plástico. ¿Tiene precio la creatividad? **La concepción más difundida es relacionar arte con fortuna, pero podemos afirmar que ya no son sinónimos**. 

Y muestra de esto lo encontramos con Artinpocket. Ya hemos dicho que acerca el arte a los usuarios de una forma rápida y efectiva, pero, además, de una manera asequible. Se puede adquirir una obra artística desde tan solo 5€! Si te gusta el arte y quieres tener una pieza original, no lo dudes, visita su galería, descubre a nuevos artistas, disfruta del arte. Recuerda que el arte tiene que tener visibilidad y lo puedes comprar. **Ya no hay excusas y Artinpocket es la respuesta: te acerca al arte de un modo asequible, compra y decora de una forma creativa y original**.