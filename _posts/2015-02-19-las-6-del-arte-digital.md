---
layout: post
og: true
og-type: article
title: "Las 6 del Arte digital" 
share: true
work: 2112
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
**[Artinpocket](http://www.artinpocket.cat/)**, web especializada en la venta de obras de creadores contemporáneos, ha apostado también por un tipo de arte que conceptualmente es innovador, rompedor, y adecuado por los tiempos en los que estamos: el **Arte digital**. ¿Pero, qué entendemos como arte digital? De manera genérica, lo podemos definir como aquel tipo de arte que está pensado, creado y consumido de forma digital, es decir, hecho a partir de un dispositivo digital, que crea unos códigos matemáticos que se transforman en imágenes visibles (fijas o en movimiento) exhibidos en otro dispositivo digital, sea un ordenador, un teléfono móvil, una pantalla de televisión o una tableta. En resumen: gráficos generados y visionados a partir de una máquina electrónica.

##¿Cuándo?
En el año 1962, un señor de nombre Michael Noll, seguramente sin ser consciente, iniciaba una nueva etapa: había realizado distintos dibujos en ordenador y los fue a imprimir en los laboratorios Bell. Tres años más tarde, y más concretamente del 5 al 19 de **enero de 1965**, en el octavo piso del edificio Hahn en la ciudad de Stuttgart, George Nees, Frieder Nake y Michael Noll (ei! Este ya nos suena!) crearon la **exposición “Computergrafik”, la primera muestra de gráficos realizados por ordenador a partir de algoritmos**. Ahora nos puede parecer bastante obvio y normal, pero en aquella época los ordenadores sólo se usaban para fines científicos. Ahora ya ciencia y arte iban de la mano. 
Pero era un método mixto, se creaba digitalmente y se mostraba analógicamente. A partir de este momento todo evolucionó a un ritmo vertiginoso y exponencial, sobretodo en este nuevo siglo donde ha estallado por completo la revolución tecnológica. Con el paso del tiempo, y con los dispositivos actuales, este arte ya no hace falta que se imprima para poder ser exhibido, ya no hace falta pasarlo a analógico. **Arte digital desde su concepción hasta su exposición**.

##¿Cómo?
Tal y como hemos dicho, el arte digital es un código matemático que se nos oculta debajo de representación gráfica, una imagen, pero ¿Cómo se pasa el código matemático a imagen? Tiene su traducción a través de puntitos, los denominado píxeles, los cuales se unen para crear la plasmación visual de la obra. **Para que nos entendamos, es la versión digital de los neoimpresionista**, con el artista Seurat a la cabeza, con el estilo puntillista como los famosos cuadros “Un dimanche après-midi à l'Ile de la Grande Jatte”  o “Une baignade à Asnières”. Pequeños puntos de color que se unen en nuestra mente para crear una imagen.

##¿Por qué?
Si el arte en sí es mentira (aquello que representa no es la realidad, sino la recreación de la realidad), el arte analógico partía de elementos naturales para crear (pigmentos, mármol, papel, madera, etc.). El digital aún es el más “mentiroso”, **ya no hay elementos reales, sólo son unos códigos (ceros y unos) camuflados detrás de un aspecto visual reconocible para todo el mundo**. Es por esto que podemos decir que el arte digital es el más innovador y rompedor que hay actualmente. 

##¿Quién?
Cualquier persona que tengo en sus manos, o en sus bolsillos, cualquier dispositivo digital es un usuario potencial para el consumo de arte digital. ¿Tienes un teléfono móvil?, ¿Una tablet?, ¿Un ordenador?... pues sí, eres el candidato idóneo para empezar a consumir arte digital. Visita Artinpocket, mira las obras digitales y, sobretodo, las puedes comprar! 

##¿Dónde?
Con el arte analógico había dos posibilidades para poder disfrutar de las obras de arte (entendidas como originales): ir a una galería, a un museo, a una sala de exposiciones, etc. y contemplar las obras o comprarlas y gozar de ellas en casa. Con el arte digital esto se multiplica ya que **lo puedes llevar encima y verlas donde tu más quieras**, sólo hace falta llevarlo en un dispositivo móvil! El arte tiene que dejar de ser elitista y exclusivista. Compra arte digital y llévalo contigo hasta el fin del mundo!

El arte digital y **[Artinpocket](http://www.artinpocket.cat/)**: accesibilidad y asequibilidad del arte de nuestros días!