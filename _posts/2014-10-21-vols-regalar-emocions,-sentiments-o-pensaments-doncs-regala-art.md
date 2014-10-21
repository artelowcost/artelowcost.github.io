---
layout: post
title: "Vols regalar emocions, sentiments o pensaments? Doncs regala art!" 
share: true
work: 2458
---

{% assign work_data = site.data.works.alones | where:"id", page.work %}
{% assign work = work_data | first %}
<figure class="text-center">
	<img src="{{ work.featured_src }}">
	<figcaption>
		<p><small><strong>{{ work.title }}</strong> | {% if work.downloadable == true %} digital art{% else if %} dimensions: {{ work.dimensions.length }}x{{ work.dimensions.height }} {{ work.dimensions.unit }}{% endif %}</small></p>
		<p><a href="{{ work.permalink }}" class="btn btn-primary btn-lg">{{ work.price_html }}! comprar! <i class="fa fa-credit-card"></i></a></p>
	</figcaption>
</figure>

L’art ens fa sensibles al món que ens envolta, la bellesa ens estremeix i alhora ens provoca un alleujament emocional i fins i tot físic. Mitjançant les creacions dels artistes expressem les nostres inquietuds, aquestes desencadenen un seguit de sentiments que ens condueixen a la reflexió i a l’anàlisi. L’art ens ajuda a pensar i potència la nostra humanitat.

[Artinpocket](http://www.artinpocekt.cat/) t’obre les portes i et proposa descobrir el seu col·lectiu d’artistes. **Art a l’abast de tothom**!