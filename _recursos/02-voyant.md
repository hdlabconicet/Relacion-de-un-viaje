---
layout: page
title: Análisis textual automatizado
permalink: /voyant/
type: extras
description: Estadísticas textuales y visualizaciones del texto realizadas con Voyant Tools
icon: bar-chart
---

Exploración del contenido de <i>Relación de un viaje al Río de la Plata</i> con [Voyant Tools](https://voyant-tools.org/), una herramienta de lectura distante y análisis estadístico de textos digitales.

Las siguientes secciones presentan cuadros interactivos. En cada panel, deslice el cursor sobre la esquina derecha de la barra superior para mostrar las opciones. El ícono <i class="fa-solid fa-question" style="color:#157fcc;"></i> permite acceder a una explicación de la herramienta usada en cada panel. El ícono <i class="fa-solid fa-toggle-on" style="color:#157fcc;"></i> permite modificar las opciones de la herramienta.

## Nube de palabras

Palabras más frecuentes del texto de Acarete du Biscay. Deslice el cursor sobre las palabras para ver la frecuencia en el texto.

<iframe class="py-3" src='https://service.sadilar.org/voyant/tool/Cirrus/?stopList=keywords-545438a422ec8d8be37eec82395158e8&corpus=7b8386214c0e0920f80f38f2f313ffda'></iframe>

Deslice la barra de términos para aumentar o disminuir la cantidad de palabras en la nube.

## Contextos

Contexto enunciativo de las palabras más frecuentes del texto. Puede modificar por frecuencia ascendente o descendente.

<iframe class="py-3" src="https://service.sadilar.org/voyant/tool/Contexts/?stopList=keywords-cefa75986faee7e695738230acf346d3&query=buenos&corpus=7b8386214c0e0920f80f38f2f313ffda"></iframe>

Modifique el término a consultar desde el menú inferior izquierdo.

## Tendencias

Evolución de la frecuencia de los principales términos de <i>Relación de un viaje al Río de la Plata</i>.

<iframe class="py-3" src='https://service.sadilar.org/voyant/tool/Trends/?stopList=keywords-545438a422ec8d8be37eec82395158e8&query=buenos&query=aires&query=hasta&query=plata&query=r%C3%ADo&mode=document&corpus=7b8386214c0e0920f80f38f2f313ffda'></iframe>

## Grafo de colocaciones

Deslice el cursor sobre las palabras de este grafo de colocaciones para consultar la frecuencia de cada par de términos.

<iframe class="py-3" src='https://service.sadilar.org/voyant/tool/Links/?stopList=keywords-cefa75986faee7e695738230acf346d3&query=buenos&query=aires&query=r%C3%ADo&query=leguas&query=holandeses&query=potos%C3%AD&query=pesar&context=15&corpus=7b8386214c0e0920f80f38f2f313ffda'></iframe>

<div class="py-4 mt-4"><p>Visite <a href="https://service.sadilar.org/voyant/?stopList=keywords-cefa75986faee7e695738230acf346d3&panels=cirrus%2Creader%2Ctrends%2Csummary%2Ccontexts&corpus=7b8386214c0e0920f80f38f2f313ffda" target="_blank">este link</a> para descubrir <i>Relación de un viaje al Río de la Plata</i> a la luz de otras herramientas ofrecidas por Voyant Tools: <a href="https://service.sadilar.org/voyant/tool/Bubbles/?stopList=keywords-cefa75986faee7e695738230acf346d3&corpus=7b8386214c0e0920f80f38f2f313ffda" target="_blank">burbujas de términos</a>, <a href="https://service.sadilar.org/voyant/tool/Veliza/?stopList=keywords-cefa75986faee7e695738230acf346d3&corpus=7b8386214c0e0920f80f38f2f313ffda" target="_blank">Veliza</a>, <a href="https://service.sadilar.org/voyant/tool/TextualArc/?stopList=keywords-cefa75986faee7e695738230acf346d3&corpus=7b8386214c0e0920f80f38f2f313ffda" target="_blank">arco textual</a> y muchas más.</p></div>
