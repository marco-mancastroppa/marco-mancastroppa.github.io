---
layout: default
---
<head>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
</head>

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
<ul class="two-column-list">
<li><b>Dynamical processes on temporal networks</b>
    <a href="https://iopscience.iop.org/article/10.1088/1742-5468/ab16c4" target="_blank">
        <img src="/pictures/dyn_temp.png" alt="Dyn_temp">
    </a>
</li>
<li><b>Adaptive temporal networks</b>
    <a href="https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.6.033159" target="_blank">
        <img src="/pictures/adaptive.png" alt="adaptive_temp">
    </a>
</li>
<li><b>Contact tracing for epidemic mitigation</b>
    <a href="https://www.nature.com/articles/s41467-021-22082-7" target="_blank">
        <img src="/pictures/CT.png" alt="CT">
    </a>
</li>
<li><b>Structural and dynamical characterization of hypergraphs</b>
    <a href="https://www.nature.com/articles/s41467-023-41887-2" target="_blank">
        <img src="/pictures/hyper.png" alt="hyper">
    </a>
</li>
<li><b>Temporal hypergraphs generation</b>
    <a href="https://epjdatascience.springeropen.com/articles/10.1140/epjds/s13688-024-00490-1" target="_blank">
        <img src="/pictures/Ht.png" alt="Ht">
    </a>
</li>
<li><b>Opinion dynamics on networks and hypergraphs</b>
    <a href="https://www.nature.com/articles/s41467-023-41887-2" target="_blank">
        <img src="/pictures/OP.png" alt="OP">
    </a>
</li>

* * *

# Closest collaborations
<p id="collaboration"></p>
<ul class="two-column-list">
    <li><b>Cosimo Agostinelli</b>, Centre de Physique Théorique (CNRS, Aix-Marseille Université)</li>
    <li><a href="https://www.cpt.univ-mrs.fr/~barrat/"><b>Alain Barrat</b></a>, Centre de Physique Théorique (CNRS, Aix-Marseille Université)</li>
    <li><a href="https://personale.unipr.it/en/ugovdocenti/person/18825"><b>Raffaella Burioni</b></a>, University of Parma, INFN</li>
    <li><a href="https://sites.google.com/site/claudiocastellanohome/home"><b>Claudio Castellano</b></a>, Institute of Complex Systems, ISC-CNR</li>
    <li><a href="https://giuliacencetti.github.io"><b>Giulia Cencetti</b></a>, Centre de Physique Théorique (CNRS, Aix-Marseille Université)</li>
    <li><a href="https://www.epicx-lab.com/vittoria-colizza.html"><b>Vittoria Colizza</b></a>, INSERM, Sorbonne Université</li>
    <li><a href="https://iaciac.github.io/author/iacopo-iacopini/"><b>Iacopo Iacopini</b></a>, Network Science Institute, Northeastern University London</li>
    <li><a href="https://www.nicolaperra.com"><b>Nicola Perra</b></a>, Queen Mary University of London</li>
    <li><a href="http://lordgrilo.github.io"><b>Giovanni Petri</b></a>, Network Science Institute, Northeastern University London, CENTAI</li>
    <li><a href="https://scholar.google.it/citations?user=Z7zwwb8AAAAJ&hl=it"><b>Alessandro Vezzani</b></a>, IMEM-CNR, University of Parma, INFN</li>
</ul>

* * *
