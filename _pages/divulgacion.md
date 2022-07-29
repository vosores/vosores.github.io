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
.center {margin:0 auto; text-align:center;}
</style>

# Modelo depredador-presa (Lotka–Volterra)
Las siguientes ecuaciones describen la dinámica de un sistema biológico en el cual dos especies interacúan, una como presa y la otra como depredador. Las ecuaciones de Lotka-Volterra, con capacidad de carga del ambiente ($k$) vienen dadas por:
$$
\begin{align*}
\frac{\partial P}{\partial t}&=r_1 P \left(1-\frac{P}{k}\right)-a_1PD\\
\frac{\partial P}{\partial t}&=a_2 PD - r_2D,
\end{align*}
$$
donde $r_1, r_2, a_1, a_2$ son parámetros (positivos) que representan las interacciones de las dos especies.

<div class="center">
<iframe width="560" height="315" src="https://phet.colorado.edu/sims/html/fourier-making-waves/latest/fourier-making-waves_es.html" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>