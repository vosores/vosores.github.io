---
layout: archive
title:
permalink: /divulgacion/
author_profile: true
redirect_from:
  - /resume
---

<!-- {% include base_path %} -->


<style>
body{
max-width: 1180px;
width: 98%;
margin: 0px auto;
/* background-color: #9ec3e8; Complementario/#e8c39e */
border-radius: 4px;
/* text-align: justify; */
}
h1{
text-align: center;
}
ul{
text-align: justify; 
}
ol{
text-align: justify;
/* .button {
background-color:#9ec3e8;
}  */
}
p{
text-align: justify;
/* .button {
background-color:#9ec3e8;
}  */
}
.center {margin:0 auto; text-align:center;}
</style>

# Modelo depredador-presa (Lotka–Volterra)
<p>Las siguientes ecuaciones describen la dinámica de un sistema biológico en el cual dos especies interacúan, una como presa y la otra como depredador. Las ecuaciones de Lotka-Volterra, con capacidad de carga del ambiente ($k$) vienen dadas por:</p>

$$
\begin{align*}
\frac{\partial P}{\partial t}&=r_1 P \left(1-\frac{P}{k}\right)-a_1PD\\
\frac{\partial D}{\partial t}&=a_2 PD - r_2D,
\end{align*}
$$

<p>donde $r_1, r_2, a_1, a_2$ son parámetros (positivos) que representan las interacciones de las dos especies.</p>

<div class="center">
<iframe width=100% src="https://phet.colorado.edu/sims/html/natural-selection/latest/natural-selection_es.html" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>