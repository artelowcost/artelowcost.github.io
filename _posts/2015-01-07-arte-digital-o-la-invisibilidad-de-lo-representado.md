---
layout: post
og: true
og-type: article
title: "Arte digital o la invisibilidad de lo representado" 
share: true
work: 1802
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

Durante muchos siglos (por no decir milenios), el arte se ha empeñado en querer representar la realidad. Pero eso no quiere decir que siempre se ha plasmado de una forma naturalista, realista para que nos entendamos. Las tendencias y las épocas artísticas son como un péndulo, si un estilo es naturalista, el siguiente es justo lo contrario, donde lo importante es lo que simboliza lo representado y no una búsqueda para plasmarlo como algo real. A partir de finales del siglo XIX esto ha estallado y convive realismo con obras de carácter más abstracto. **El gran reto del artista es querer representar la realidad a partir de un medio ficticio que es la obra artística, donde lo único “real” y palpable es el material con que se crea la obra**: lienzo, pigmentos, mármol, bronze, hierro,… El arte, en el fondo, es una mentira que se te presenta como una verdad.

Pero **todo esto se resquebraja con la incursión del arte digital a mediados del siglo XX**. En el arte digital la imagen no existe como tal, sino que es la plasmación gráfica de un código invisible para nosotros, lo que vemos no es lo que hay, lo que el artista crea es un código matemático. Como decía Donald Kuspit, “Con el arte digital postmoderno la imagen pasa a ser una manifestación secundaria -un epifenómeno material, por así decirlo- del código abstracto que, de este modo, se convierte en el vehículo principal de la creatividad. Hasta hace poco, el objetivo primordial de las artes plásticas era la producción de imágenes materiales, y el código inmaterial que guiaba el proceso creativo desempeñaba un papel secundario y a menudo inconsciente”. Para algunos expertos, este tipo de arte se tendría que denominar new art media (arte de los nuevos medios) ya que incluye arte, ciencia y tecnología.

¿Cómo se pasa el código matemático a imagen gráfica? Tiene su traducción a través de puntitos, los denominado píxeles, los cuales se unen para crear la plasmación visual de la obra. Es la versión digital de los neoimpresionistas, con el artista Seurat a la cabeza, con el estilo puntillista como los famosos cuadros “[Un dimanche après-midi à l'Ile de la Grande Jatte](http://fr.wikipedia.org/wiki/Un_dimanche_apr%C3%A8s-midi_%C3%A0_l%27%C3%8Ele_de_la_Grande_Jatte 'Un dimanche après-midi à l'Île de la Grande Jatte — Wikipédia')”  o “Une baignade à Asnières”.

Si quieres ver una buena muestra de **[arte digital](http://www.artinpocket.cat/categoria-producto/digital/?orderby=rating)** y comprar algunas de sus obras sólo tienes que ir a **[Artinpocket](http://www.artinpocket.cat/categoria-producto/digital/?orderby=popularity)**, arte accesible para todos los bolsillos. Recuerda, lo que ves no existe como tal, sólo es la plasmación gráfica del código matemático.