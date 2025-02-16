---
layout: default
---
<head>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
</head>

<style>
.image-left {
    float: left;
    width: 55%; 
    vertical-aligne: top;
    margin: 0 5px 3px 0; /* Adds space around the image */
}
.image-right {
    float: right;
    width: 55%;
    vertical-aligne: top;
    margin: 0 0 3px 5px; /* Adds space around the image */
}
    
.container {
  display: flex;
  align-items: center;
  gap: 15px; 
}

.container img {
  max-width: 35%; 
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

# About me
<p id="aboutme"></p>
<div class="container"> 
  <img src="/pictures/me.jpg" alt="Marco Mancastroppa" style="width: 100%; aspect-ratio: 1 / 1; object-fit: cover;">
    <p>
    <a href="mailto:marco.mancastroppa@cpt.univ-mrs.fr"><i class="fa-solid fa-envelope fa-2x"></i></a>
    <a href="https://bsky.app/profile/marco-mancastroppa.bsky.social" target="_blank"><i class="fa-brands fa-bluesky fa-2x"></i></a>
    <a href="https://scholar.google.com/citations?user=4UKBmnoAAAAJ&hl=en" target="_blank"><i class="fa-solid fa-graduation-cap fa-2x"></i></a>
    <a href="https://orcid.org/0000-0002-7344-7992" target="_blank"><i class="fa-brands fa-orcid fa-2x"></i></a>
    <a href="https://www.researchgate.net/profile/Marco-Mancastroppa" target="_blank"><i class="fa-brands fa-researchgate fa-2x"></i></a>
    <a href="https://github.com/marco-mancastroppa" target="_blank"><i class="fa-brands fa-github fa-2x"></i></a>
    <a href="https://fr.linkedin.com/in/marco-mancastroppa-b3587611a" target="_blank"><i class="fa-brands fa-linkedin fa-2x"></i></a>
  <br>I am a <b>physicist</b> with a background in <b>statistical physics</b> and <b>physics of complex systems</b>. My research activity focuses on the study of <b>complex networks, higher-order interactions, network dynamics and stochastic processes on networks</b>, with applications in <b>epidemiology, social systems, and data-driven modeling</b>.<br><br>
I am currently a <b>post-doctoral researcher</b> at the <a href="https://www.cpt.univ-mrs.fr/">Centre de Physique Théorique (CNRS, Aix-Marseille Université)</a> in Marseille (France) under the supervision of <a href="https://www.cpt.univ-mrs.fr/~barrat/">Alain Barrat</a>.
</p>
</div>
    <p>Here you can find information about my <a href="https://marco-mancastroppa.github.io/academic-trajectory">academic trajectory</a>, my <a href="#topics">research projects</a>, my <a href="#collaboration">collaboration network</a> and <a href="https://marco-mancastroppa.github.io/publications.html">publications</a>. Feel free to <a href="https://marco-mancastroppa.github.io/contacts.html">reach me out</a> if you’re interested in potential collaborations!</p>

* * *

# Topics
<p id="topics"></p>
<b style="color: #155799; font-size: 24px;">Structural characterization of hypergraphs</b>
<p id="characterizationH"></p>
<p>
    <img src="/pictures/hyper.png" alt="hyper" class="image-right">
    Going beyond networks, to include <b>higher-order interactions</b>, is a major step to better describe complex systems characterized by group interactions. In the resulting <b>hypergraph</b> representation, tools to identify structures and central nodes are scarce. We are working on developing a series of <b>methods</b> specifically designed to analyse the <b>topological properties of hypergraphs</b> at multiple scales. <br><br>
    - Mancastroppa M. et al, <a href="https://doi.org/10.1038/s41467-023-41887-2">Nat Commun <b>14</b>, 6223 (2023)</a><br>
    - Mancastroppa M. et al, <a href="https://doi.org/10.1140/epjds/s13688-024-00490-1">EPJ Data Science <b>13</b>, 50 (2024)</a><br>
    </p>

* * *

<b style="color: #155799; font-size: 24px;">Complex dynamic processes</b>
<p id="dynH"></p>
<p>
    <img src="/pictures/OP.png" alt="OP" class="image-left">
    <b>Complex dynamic processes</b> are based on <b>intrinsically higher-order mechanisms</b>, where multiple exposure and group reinforcement are active, requiring to consider multi-body interactions. Higher-order interactions give rise to both novel structures and phenomena, deeply affecting dynamical processes. We are interested in investigating how the higher-order structure of the interactions affects the dynamical processes and how these differ from <b>simple dynamics on pairwise networks</b>. <br><br>
    - Mancastroppa M. et al, <a href="https://doi.org/10.1038/s41467-023-41887-2">Nat Commun <b>14</b>, 6223 (2023)</a><br>
    - Cencetti G. et al, <a href="https://doi.org/10.1103/PhysRevLett.130.247401">PRL <b>130</b>, 247401 (2023)</a><br><br>
</p>

* * *

<b style="color: #155799; font-size: 24px;">Temporal hypergraphs generation</b>
<p id="TempH"></p>
<p>
    <img src="/pictures/Ht.png" alt="Ht" class="image-right">
    <b>Temporal hypergraphs</b> represent a powerful framework to describe complex systems composed of elements interacting in groups, with interactions evolving over time. Designing <b>models of temporal hypergraphs</b> is crucial for generating surrogates of real observed dynamics, and also for understanding the role of topological and temporal properties on dynamical processes. We work on building new models of higher-order networks <b>replicating features and mechanisms observed</b> in empirical systems.<br><br>
    -Mancastroppa M. et al, <a href="https://doi.org/10.1140/epjds/s13688-024-00490-1">EPJ Data Science <b>13</b>, 50 (2024)</a><br>
</p>

* * *

<b style="color: #155799; font-size: 24px;">Adaptive temporal networks</b>
<p id="adaptive"></p>
<p>
     <img src="/pictures/adaptive.png" alt="adaptive_temp" class="image-left">
    <b>Adaptive temporal networks</b> represent a powerful paradigm for modelling the spread of epidemics, accounting for the coupling between epidemic processes and social interactions: human interactions are <b>continuously rearranged over time</b>, affecting the epidemic; the epidemic induces <b>adaptive behaviours</b> with which the population responds to the spread of the pathogen, affecting the social dynamics. Our work consists in understanding the <b>interplay between epidemic dynamics and adaptive behaviors</b>, which is essential to improve <b>response strategies</b> to epidemics.<br><br>
    - Mancastroppa M. et al, <a href="https://doi.org/10.1103/PhysRevResearch.6.033159">PRResearch <b>6</b>, 033159 (2024)</a><br>
    - Mancastroppa M. et al, <a href="https://doi.org/10.1103/PhysRevE.102.020301">PRE <b>102</b>, 020301(R) (2020)</a><br>
</p>

* * *

<b style="color: #155799; font-size: 24px;">Contact tracing for epidemic mitigation</b>
<p id="CT"></p>
<p>
    <img src="/pictures/CT.png" alt="CT" class="image-right">
    Isolation of symptomatic individuals, tracing and testing of their nonsymptomatic contacts are fundamental adaptive behaviours that populations exposed to epidemics can implement. Moreover, <b>effective contact tracing</b> is crucial to containing epidemic spreading <b>without disrupting societal activities</b>. Within the framework of <b>adaptive temporal networks</b>, we investigate the effectiveness of different <b>contact tracing strategies</b> in curbing the epidemic and keeping the population activity. <br><br>
    - Mancastroppa M. et al, <a href="https://doi.org/10.1038/s41467-021-22082-7">Nat Commun <b>12</b>, 1919 (2021)</a><br>
    - Mancastroppa M. et al, <a href="https://doi.org/10.1098/rsif.2022.0048">J. R. Soc. Interface <b>19</b>, 20220048 (2022)</a><br>
</p>

* * *

<b style="color: #155799; font-size: 24px;">Dynamical processes on temporal networks</b>
<p id="bursty"></p>
<p>
    <img src="/pictures/dyn_temp.png" alt="Dyn_temp" class="image-left">
    Many complex systems present time-varying interactions, which follow specific dynamics: these systems are represented using <b>temporal networks</b>. Dynamic processes on temporal networks are strongly impacted by the network dynamics, especially when the <b>dynamics of and on the network have comparable time scales</b>. We are interested in how <b>temporal properties</b> of the network influence <b>dynamic processes unfolding upon it</b>.<br><br>
    - Mancastroppa M. et al, <a href="https://doi.org/10.1088/1742-5468/ab16c4">Journal of Statistical Mechanics: Theory and Experiment 053502 (2019)</a><br>
</p>

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
    <li><b>Alessandro De Gaetano</b>, CPT, CNRS, Aix-Marseille Université), ISI Turin</li>
    <li><b>Juliette Gambaudo</b>, Centre de Physique Théorique (CNRS, Aix-Marseille Université)</li>
    <li><a href="https://scholar.google.it/citations?user=nqXUx9cAAAAJ&hl=it"><b>Andrea Guizzo</b></a>, Fondazione Bruno Kessler, FBK, Trento</li>
    <li><a href="https://iaciac.github.io/author/iacopo-iacopini/"><b>Iacopo Iacopini</b></a>, Network Science Institute, Northeastern University London</li>
    <li><a href="https://scholar.google.com/citations?user=9YHHXwgAAAAJ&hl=en"><b>Razieh Masoumi</b></a>, University of Padova</li>
    <li><b>Gabriel Maurial</b>, Centre de Physique Théorique (CNRS, Aix-Marseille Université)</li>
    <li><a href="https://www.nicolaperra.com"><b>Nicola Perra</b></a>, Queen Mary University of London</li>
    <li><a href="http://lordgrilo.github.io"><b>Giovanni Petri</b></a>, Network Science Institute, Northeastern University London, CENTAI</li>
    <li><a href="https://scholar.google.it/citations?user=Z7zwwb8AAAAJ&hl=it"><b>Alessandro Vezzani</b></a>, IMEM-CNR, University of Parma, INFN</li>
</ul>
