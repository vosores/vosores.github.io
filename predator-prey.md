---
layout: default
title: Predator-prey example
description: Un ejemplo sencillo
---
#### Modelo depredador-presa (Lotka–Volterra).
Las siguientes ecuaciones describen la dinámica de un sistema biológico en el cual dos especies interactúan, una como presa y la otra como depredador. Las ecuaciones de Lotka-Volterra, con capacidad de carga del ambiente ($k$) vienen dadas por:

$$\begin{align*} \frac{dP}{dt}&=r_1 P \left(1-\frac{P}{k}\right)-a_1PD\\ \frac{dD}{d t}&=a_2 PD - r_2D, \end{align*}$$

donde $r_1$, $r_2$, $a_1$, $a_2$ son parámetros (positivos) que representan las interacciones de las dos especies.

**Ejemplo** del modelo presentado con condición inicial $P(0) = 2000$ conejos, $D(0) = 10$ lobos y capacidad de carga $k=10000$ conejos.
<div class="image" style="max-width: 100%; max-height: 50%;"><img src="https://vosores.github.io/predator_prey.png" style="max-width: 50%;"><img src="https://vosores.github.io/predator_vs_prey.png" style="max-width: 50%;"></div>
<!-- </div> -->
#### Como obtuve la solución anterior? Usando métodos numéricos.
<script src="https://gist.github.com/vosores/421dd0ce6bebdf6d1b9259368ce634ab.js" type="text/javascript"></script>
<p>Haz click en Open In Colab, cambia las condiciones iniciales y describe lo observado.</p>
