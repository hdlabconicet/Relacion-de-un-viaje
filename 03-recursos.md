---
layout: page
title: Recursos
permalink: /acarete-recursos/
type: extras
---


<!-- Recursos -->
<div class="container mx-auto px-2">
	<!-- <div class="border-top-thick">  Linea larga 
	<div class="col-1 sm-width-full border-top-thick"> </div> Linea corta -->
  {% for post in site.recursos %}
    {% include post_block.html %}
  {% endfor %}

  <div class="py-1 mb-0 prose">
  <h2 class="h2 lh-condensed col-9 mb-2">
    <a class="no-underline" title="Texto anotado en Recogito" href="https://recogito.pelagios.org/document/lhwcy2r5yd8d8o/part/1/edit" target="_blank">Texto anotado en Recogito</a>
  </h2>
  <a class="h3 lh-condensed" href="https://recogito.pelagios.org/document/lhwcy2r5yd8d8o/part/1/edit" target="_blank"><p>El relato de Acarete disponible en una plataforma de anotación colaborativa</p></a></div>

</div><!-- End Recursos -->