---
layout: page
permalink: /
title: Home
description:
profile:
  image: avatar.jpg
  address: >

nav: false
news: true # includes a list of news items
education: true
---

<div style="display: flex; align-items: center; gap: 80px;">
  <span style="font-size: 1.2em;">
    Ph.D. Student @ETH Zürich & @ETH AI Center <br> Previously Research Intern @Amazon, @EPFL, and @MIT <br> Working on self-supervised representation learning, <br> multimodal learning and generative modelling
  </span>
  <img class="img-responsive rounded-circle profile" src="assets/img/avatar.jpg" alt="Profile photo" style="max-width: 200px; margin-right: 30px;">
</div>

## About Me

<div markdown="1"> 

  I am a Doctoral Student at [ETH Zürich](https://ethz.ch/) and an [ETH AI Center](https://ai.ethz.ch/) fellow. In 2024, I was an intern at [Amazon Research](https://www.amazon.science) in Tübingen, DE. 

  I am broadly interested in **representation learning, (probabilistic) self-supervised (SSL) methods and generative modelling**, more specifically **understanding** how current methods work and leverage this knowledge to **build better representations**. 
  
  During my PhD, I have been thinking about how we learn representations from observations in unsupervised settings. While discriminative methods (e.g., SimCLR, DINO) generally outperform reconstruction/generative ones (e.g., VAE, MAE), they often rely on less principled approaches. Instead reconstruction-based approach carry their load of challenges, limiting there performance but are driven by principled objectives. 
  
  Early on during my PhD, I used Identifiability and Causal Representation Learning to better understand discriminative SSL in multi-modal settings. Later on, I explored latent variable models as a mean to explain SSL and unify discriminative and generative methods. More recently, I've explored Masked Autoencoders and proposed the space of principal components as a more principled and effective masking space for reconstructive SSL. Finally, I am currently looking into the training dynamics of discriminative SSL, specifically how data characteristics affect these dynamics.

  In 2020, I graduated from [EPFL](https://www.epfl.ch/) after a Master's Thesis at the [Senseable Intelligence Group, MIT](https://sensein.group) under the supervision of Prof. Satrajit Ghosh. After working on the modelling of 3D brain scans using GANs at MIT, I joined the ETH AI Center in Zürich for my Ph.D. under the supervision of Prof. Julia Vogt and Prof. Bernhard Schölkopf. 

  More information about me can be found in my<a href="/assets/pdf/cv.pdf"><span style="color: #6495ED;"> resume</span></a>


</div>

## Publications

<div class="publications">
  <div class="table-responsive">
    <table class="table table-sm table-borderless">
    {% assign publications = site.publications | sort: 'date' | reverse %}
    {% for publi in publications %}
      {% if publi.show %}
        {% include publication.html %}
      {% endif %}
    {% endfor %}
    </table>
  </div>
</div>

## News

{% if page.news %}
{% include news.html %}
{% endif %}

## Education

{% if page.education %}
{% include education.html %}
{% endif %}

## Personal Information

- <img src="../assets/img/placeholder.png" style="max-width: 20px;"> Zürich, Switzerland
- <img src="../assets/img/house.png" style="max-width: 20px;"> in Maastricht, Liège, Paris & Zürich
