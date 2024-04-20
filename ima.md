---
layout: default
title: Divulgación IMA
description: Modelos matemáticos, simulaciones, videos, otros.
---
# Videos interesantes
### Mates Mike: El Problema de los Tres Cuerpos, una Visualización del CAOS del Cosmos.
<p style="text-align: center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/427vNUBNguw?si=fvn0EH4IpxjMowK6" title="YouTube video player" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>
### Veritasium: El Extraño Comportamiento de los Objetos en Rotación.
<p style="text-align: center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/yIz6hHgRmk8?si=iWdviu_BVcnv8Ss6" title="YouTube video player" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>
### Date un vlog: El Problema de los 3 Cuerpos: El Origen de la Serie de Netflix. 
<p style="text-align: center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/QAshpZNMyCE?si=iawuxV4SGn8ct9ec" title="YouTube video player" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>

<h1>Modelamiento matemático</h1>
<h2>Modelo depredador-presa (Lotka–Volterra)</h2>
<p class="justificado">Las siguientes ecuaciones describen la dinámica de un sistema 
  biológico en el cual dos especies interacúan, una como presa y la otra como depredador. 
  Las ecuaciones de Lotka-Volterra, con capacidad de carga del ambiente ($k$) vienen 
  dadas por:</p>

<p>
  \[
  \begin{align*}
  \frac{dP}{dt}&=r_1 P \left(1-\frac{P}{k}\right)-a_1PD\\
  \frac{dD}{d t}&=a_2 PD - r_2D,
  \end{align*}
  \]
</p>

<p>donde $r_1, r_2, a_1, a_2$ son parámetros (positivos) que representan las interacciones de las dos especies.</p>

<p style="text-align: center;">
<iframe width="560" height="315" src="https://phet.colorado.edu/sims/html/natural-selection/latest/natural-selection_es.html" title="Depredador presa" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

<p><strong>Ejemplo</strong> del modelo presentado con condición inicial 
  $P(0) = 2000$ conejos, $D(0) = 10$ lobos y capacidad de carga $k=10000$ conejos.
</p>
<!-- <div id="banner" style="overflow: hidden; display: inline-block;"> -->
  <div class="image" style="max-width: 100%; max-height: 50%;">
      <img src ="img/predator_prey.png" style="max-width: 50%;"><img src ="img/predator_vs_prey.png" style="max-width: 50%;">
  </div>
<!-- </div> -->
<h2>Ecuaciones de aguas someras (Shallow water equations)</h2>
<p> 
  En la actualidad, científicos de todo el mundo intentan continuamente utilizar métodos numéricos para
predecir la evolución de eventos geofísicos e industriales de alto impacto social, 
ambiental y económico. En particular, Chile es un país que constantemente ha sido afectado por tsunamis, deslizamientos de
tierra e inundaciones que han dejado bajo el agua y lodo ciudades enteras.
</p>
<p style="text-align: center;">
  <img src ="img/villa_santa_lucia.jpg" style="max-width: 70%;">
  <figcaption>Fig.1 Aluvión de Villa Santa Lucı́a, Chaitén.</figcaption>
</p>
<p>
  La caracterización y estudio
  de estos fenómenos implica la modelización matemática y númerica de ecuaciones 
  diferenciales parciales (EDPs) complejas y disponer de herramientas que permitan hacer 
  simulaciones numéricas de estos eventos nos permitiría estar un paso delante de la 
  ocurrencia de estos, así como también, tomar decisiones que permitan minimizar el 
  impacto ambiental y social en caso de que se produzcan inevitablemente.
</p>
<p>
  Desde el punto de vista físico-matemático, flujos viscosos como agua o aire se modelan 
  mediante las <strong>ecuaciones de aguas someras (shallow water)</strong>. En el caso de un 
  fondo plano (horizontal), con fuerzas de Coriolis, fuerzas de fricción y viscosas despreciables, 
  las ecuaciones de aguas poco profundas vienen dadas por:
</p>
<p>
  \[
  \begin{align*}
  \frac{\partial (\rho \eta)}{\partial t}+\frac{\partial (\rho \eta u)}{\partial x}+\frac{\partial (\rho \eta v)}{\partial y}&=0,\\
  \frac{\partial (\rho \eta u)}{\partial t}+\frac{\partial}{\partial x}\left(\rho \eta u^2+\frac{1}{2}\rho g \eta^2\right)
+\frac{\partial (\rho \eta u v)}{\partial y}&=0,\\
\frac{\partial (\rho \eta v)}{\partial t}+\frac{\partial (\rho \eta u v)}{\partial x}+
\frac{\partial}{\partial y}\left(\rho \eta v^2+\frac{1}{2}\rho g \eta^2\right)&=0,\\
  \end{align*}
  \]
</p>
<p>$\eta$ es la altura total de la columna de fluido (profundidad instantánea del fluido en función de $x$, $y$ y $t$), 
  y el vector 2D $(u,v)$ es el campo de velocidad horizontal del fluido. Además, $g$ es la aceleración de la gravedad y $\rho$ 
  es la densidad del fluido.</p>

<p style="text-align: center;">
<iframe width="560" height="315" src="https://phet.colorado.edu/sims/html/wave-interference/latest/wave-interference_es.html" title="ondas" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

<p><strong>Importancia:</strong>
<ul>
  <li>
    Simulación del rompimiento de represas.
  </li>
  <li>
    Predicción de zonas de innundación.
  </li>
  <li>
    Predicción y simulación de tsunamis en zonas costeras.
  </li>
  <li>
    Simulación de avalanchas y aluviones.
  </li>
  <li>
    Evolución de lava tras una erupción volcánica.
  </li>
</ul>
</p>
<p style="text-align: center;">
  <img src ="img/juanpabloii.jpg" style="max-width: 70%;">
  <figcaption>Fig.2 Inundación río Bio-Bio, Concepción.</figcaption>
</p>

<h2>Oscilaciones amortiguadas de un péndulo simple</h2>

<p class="justificado">Un  movimiento  de  tipo  armónico  simple, sin roce  está  regido  por la siguiente ecuación diferencial ordinaria:
\[\frac{d^2x}{dt^2}+\omega_0^2x=0, \tag{1}
\]
donde $x$ representa la elongación o desplazamiento respecto al punto de equilibrio, $\omega_0=\sqrt{g/l}$ es la frecuencia  natural de las 
oscilaciones armónicas.  La solución  de  la  ecuación (1), viene dada por:
\[x(t) = A\sin(\omega_0t+\psi).
\]
Donde $A$, es la amplitud del movimiento, $\omega_0$ es la frecuencia angular, $\psi$ es la fase inicial e indica el estado de 
oscilación o vibración (o fase) en el instante de tiempo $t = 0$ de la partícula que oscila.
</p>

<p>
  <strong>Péndulo simple con fricción:</strong> La fuerza de amortiguamiento por fricción de la velocidad del cuerpo oscilante, un tipo de 
  fuerza retardadora muy común, y actúa en la dirección opuesta a la velocidad. En el caso del péndulo, esta fuerza es directamente 
  proporcional a la velocidad, por lo que lo expresamos como $f_r=-b v_t$. Así, las ecuaciones que describen las 
  <strong>Oscilaciones amortiguadas de un péndulo simple</strong> vienen dadas por:
  \[\frac{d^2x}{dt^2}+\frac{b}{m}\frac{dx}{dt}+\frac{g}{l}x=0,\quad(\text{pequeñas oscilaciones.})
\]
La solución de la ecuación del movimiento viene dada por:
\[
x(t)=x_0e^{-\gamma t}\cos(\omega t + \psi_0),
\]
con $\gamma=b/2m$, $w=\sqrt{\omega_0^2-\gamma^2}$.
</p>
<p style="text-align: center;">
  <iframe width="560" height="315" src="https://phet.colorado.edu/sims/html/pendulum-lab/latest/pendulum-lab_es.html" title="Movimiento armónico" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </p>

[back](./)
