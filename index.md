---
layout: default
---
<head>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
</head>

<style>
.image-left {
    float: left;
    width: 60%; 
    vertical-aligne: top;
    margin: 0 15px 10px 0; /* Adds space around the image */
}
.image-right {
    float: right;
    width: 60%;
    vertical-aligne: top;
    margin: 0 0 10px 15px; /* Adds space around the image */
}
    
.container {
  display: flex;
  align-items: center;
  gap: 15px; 
}

.container img {
  max-width: 50%; 
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

/* Style for the unordered list */
ul.two-column-list {
    display: grid;
    grid-template-columns: repeat(2, 1fr); /* Creates two equal columns */
    gap: 10px; /* Adds space between the columns */
    padding: 0;
    list-style-type: none; /* Removes bullet points */
}

/* Style for list items */
ul.two-column-list li {
    margin-bottom: 10px; /* Adds space between list items */
}
</style> 

<div class="container"> 
  <img src="/pictures/me.jpg" alt="Marco Mancastroppa">
  <p>I am a <b>physicist</b> with a background in <b>statistical physics</b> and <b>physics of complex systems</b>. My research activity focuses on the study of <b>complex networks, higher-order interactions, network dynamics and stochastic processes on networks</b>, with applications in <b>epidemiology, social systems, and data-driven modeling</b>.<br><br>
    I am currently a <b>post-doctoral researcher</b> at the <a href="https://www.cpt.univ-mrs.fr/">Centre de Physique Théorique (CNRS, Aix-Marseille Université)</a> in Marseille (France) under the supervision of <a href="https://www.cpt.univ-mrs.fr/~barrat/">Alain Barrat</a>.<br><br>
    Here you can find information about my <a href="https://marco-mancastroppa.github.io/academic-trajectory">academic trajectory</a>, my <a href="#topics">research projects</a>, my <a href="#collaboration">collaboration network</a> and <a href="https://marco-mancastroppa.github.io/publications.html">publications</a>. Feel free to <a href="https://marco-mancastroppa.github.io/contacts.html">reach me out</a> if you’re interested in potential collaborations! <br><br>
    <a href="mailto:marco.mancastroppa@cpt.univ-mrs.fr"><i class="fa-solid fa-envelope fa-2x"></i></a>
    <a href="https://bsky.app/profile/marco-mancastroppa.bsky.social" target="_blank"><i class="fa-brands fa-bluesky fa-2x"></i></a>
    <a href="https://scholar.google.com/citations?user=4UKBmnoAAAAJ&hl=en" target="_blank"><i class="fa-solid fa-graduation-cap fa-2x"></i></a>
    <a href="https://orcid.org/0000-0002-7344-7992" target="_blank"><i class="fa-brands fa-orcid fa-2x"></i></a>
    <a href="https://www.researchgate.net/profile/Marco-Mancastroppa" target="_blank"><i class="fa-brands fa-researchgate fa-2x"></i></a>
    <a href="https://github.com/marco-mancastroppa" target="_blank"><i class="fa-brands fa-github fa-2x"></i></a>
    <a href="https://fr.linkedin.com/in/marco-mancastroppa-b3587611a" target="_blank"><i class="fa-brands fa-linkedin fa-2x"></i></a>
</p>
</div>

* * *

# Topics
<p id="topics"></p>
<b style="color: #155799;">Dynamical processes on temporal networks</b><br>
<p>
    <img src="/pictures/dyn_temp.png" alt="Dyn_temp" class="image-right">
    Several systems present time-varying interactions, which follow specific dynamics and temporal patterns: these systems are represented using <b>temporal networks</b>. Dynamic processes on temporal networks are strongly impacted by the network dynamics, especially when the dynamics of and on the network have comparable time scales. We are interested in how temporal properties of the network influence dynamic processes unfolding upon it.<br>
</p>
<b>Temporal hypergraphs generation<br><br>
<img src="/pictures/Ht.png" alt="Ht"><br><br>
<b>Adaptive temporal networks<br><br>
 <img src="/pictures/adaptive.png" alt="adaptive_temp"><br><br>
<b>Contact tracing for epidemic mitigation<br><br>
 <img src="/pictures/CT.png" alt="CT"><br><br>
<b>Structural and dynamical characterization of hypergraphs<br><br>
<img src="/pictures/hyper.png" alt="hyper"><br><br>
<b>Opinion dynamics on networks and hypergraphs<br><br>
 <img src="/pictures/OP.png" alt="OP"><br><br>
        
* * *

# My collaboration network
<p id="collaboration"></p>
<ul class="two-column-list">
    <li><b>Cosimo Agostinelli</b>, Centre de Physique Théorique (CNRS, Aix-Marseille Université)</li>
    <li><a href="https://www.cpt.univ-mrs.fr/~barrat/"><b>Alain Barrat</b></a>, Centre de Physique Théorique (CNRS, Aix-Marseille Université)</li>
    <li><a href="https://personale.unipr.it/en/ugovdocenti/person/18825"><b>Raffaella Burioni</b></a>, University of Parma, INFN</li>
    <li><a href="https://sites.google.com/site/claudiocastellanohome/home"><b>Claudio Castellano</b></a>, Institute of Complex Systems, ISC-CNR</li>
    <li><a href="https://giuliacencetti.github.io"><b>Giulia Cencetti</b></a>, Centre de Physique Théorique (CNRS, Aix-Marseille Université)</li>
    <li><a href="https://www.epicx-lab.com/vittoria-colizza.html"><b>Vittoria Colizza</b></a>, INSERM, Sorbonne Université</li>
    <li><b>Alessandro De Gaetano</b></a>, Centre de Physique Théorique (CNRS, Aix-Marseille Université), ISI Turin</li>
    <li><b>Juliette Gambaudo</b></a>, Centre de Physique Théorique (CNRS, Aix-Marseille Université)</li>
    <li><a href="https://scholar.google.it/citations?user=nqXUx9cAAAAJ&hl=it"><b>Andrea Guizzo</b></a>, Fondazione Bruno Kessler, FBK, Trento</li>
    <li><a href="https://iaciac.github.io/author/iacopo-iacopini/"><b>Iacopo Iacopini</b></a>, Network Science Institute, Northeastern University London</li>
    <li><a href="https://scholar.google.com/citations?user=9YHHXwgAAAAJ&hl=en"><b>Razieh Masoumi</b></a>, University of Padova</li>
    <li><b>Gabriel Maurial</b></a>, Centre de Physique Théorique (CNRS, Aix-Marseille Université)</li>
    <li><a href="https://www.nicolaperra.com"><b>Nicola Perra</b></a>, Queen Mary University of London</li>
    <li><a href="http://lordgrilo.github.io"><b>Giovanni Petri</b></a>, Network Science Institute, Northeastern University London, CENTAI</li>
    <li><a href="https://scholar.google.it/citations?user=Z7zwwb8AAAAJ&hl=it"><b>Alessandro Vezzani</b></a>, IMEM-CNR, University of Parma, INFN</li>
</ul>

* * *
