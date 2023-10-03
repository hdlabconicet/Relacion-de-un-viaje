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

<iframe class="py-3" src='https://voyant-tools.org/tool/Cirrus/?palette=extjs&stopList=keywords-55ea55e9933ed6062c0ef087b3a73b02&whiteList=&visible=100&fontFamily=LatoWeb&corpus=876a19b39ea7f0b10da4ecc22c8dc9a5&lang=es&stopList=keywords-55ea55e9933ed6062c0ef087b3a73b02'></iframe>

Deslice la barra de términos para aumentar o disminuir la cantidad de palabras en la nube.

## Contextos

Contexto enunciativo de las palabras más frecuentes del texto. Puede modificar por frecuencia ascendente o descendente.

<iframe class="py-3" src="https://voyant-tools.org/tool/Contexts/?palette=extjs&lang=es&stopList=keywords-55ea55e9933ed6062c0ef087b3a73b02&query=mercaderías&corpus=876a19b39ea7f0b10da4ecc22c8dc9a5"></iframe>

Modifique el término a consultar desde el menú inferior izquierdo.

## Tendencias

Evolución de la frecuencia de los principales términos de <i>Relación de un viaje al Río de la Plata</i>.

<iframe class="py-3" src='https://voyant-tools.org/tool/Trends/?palette=extjs&lang=es&stopList=keywords-55ea55e9933ed6062c0ef087b3a73b02&query=mercaderías&query=río&query=minas&query=salvajes&mode=document&corpus=876a19b39ea7f0b10da4ecc22c8dc9a5'></iframe>

## Grafo de colocaciones

Deslice el cursor sobre las palabras de este grafo de colocaciones para consultar la frecuencia de cada par de términos.

<iframe class="py-3" src='https://voyant-tools.org/tool/CollocatesGraph/?palette=extjs&lang=es&stopList=keywords-55ea55e9933ed6062c0ef087b3a73b02&query=minas&query=río&mode=corpus&corpus=876a19b39ea7f0b10da4ecc22c8dc9a5'></iframe>

<div class="py-4 mt-4"><p>Visite <a href="https://voyant-tools.org/?corpus=876a19b39ea7f0b10da4ecc22c8dc9a5&palette=extjs&stopList=keywords-55ea55e9933ed6062c0ef087b3a73b02&panels=reader,termsberry,textualarc,summary,correlations" target="_blank">este link</a> para descubrir <i>Relación de un viaje al Río de la Plata</i> a la luz de otras herramientas ofrecidas por Voyant Tools: <a href="https://voyant-tools.org/?corpus=876a19b39ea7f0b10da4ecc22c8dc9a5&palette=extjs&lang=es&stopList=keywords-55ea55e9933ed6062c0ef087b3a73b02&view=Bubbles" target="_blank">burbujas de términos</a>, <a href="https://voyant-tools.org/?corpus=876a19b39ea7f0b10da4ecc22c8dc9a5&palette=extjs&lang=es&stopList=keywords-55ea55e9933ed6062c0ef087b3a73b02&view=Veliza" target="_blank">Veliza</a>, <a href="https://voyant-tools.org/?corpus=876a19b39ea7f0b10da4ecc22c8dc9a5&palette=extjs&lang=es&stopList=keywords-55ea55e9933ed6062c0ef087b3a73b02&view=TextualArc" target="_blank">arco textual</a> y muchas más.</p></div>
