---
layout: default
---
<style>
.container {
  display: flex;
  align-items: center;
  gap: 15px; 
}

.container img {
  max-width: 30%; 
  height: auto;
}

.container p {
  flex: 1; 
}

  
@media (max-width: 768px) {
  .container {
    flex-direction: column;
    text-align: center; 
  }

  .container img {
    max-width: 80%; 
  }
}
</style>

<div class="container">
  <img src="/pictures/me.jpg" alt="Marco Mancastroppa">
  <p>I am a <b>physicist</b> with a background in <b>statistical physics</b> and <b>physics of complex systems</b>. My research activity focuses on the study of <b>complex networks, higher-order interactions, network dynamics and stochastic dynamical processes on networks</b>.<br><br>
    I am currently a <b>post-doctoral researcher</b> at the <a href="https://www.cpt.univ-mrs.fr/">Centre de Physique Théorique (CNRS, Aix-Marseille Université)</a> in Marseille (France) under the supervision of <a href="https://www.cpt.univ-mrs.fr/~barrat/">Alain Barrat</a>.<br><br>
    Here you can find more information about my <a href="https://marco-mancastroppa.github.io/timeline.html">academic trajectory</a> or about my <a href="https://marco-mancastroppa.github.io/publications.html">research activity</a>.
</p>
</div>
