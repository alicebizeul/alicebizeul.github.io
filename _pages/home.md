---
layout: page
permalink: /
title: Alice Bizeul
description:
profile:
  align: right
  image: avatar.jpg
  address: >

nav: false
news: true # includes a list of news items
education: true
---

<div style="display: flex; align-items: center; gap: 20px; flex-wrap: wrap; justify-content: center;">
  <span style="font-size: 1.2em;">
    Ph.D. Student @ETH Zürich <br> Previously @EPFL, @MIT, @Amazon <br> Working on self-supervised representation learning, <br> multimodal learning & generative modelling.
    <div class="social" style="font-size: 1.5em;">
        {% include social.html %}
    </div>
  </span>
  <img class="img-responsive rounded-circle profile" src="assets/img/avatar.jpg" alt="Profile photo" style="max-width: 200px;">
</div>

## About Me

<div markdown="1"> 

  I am a doctoral student at <a href="https://ethz.ch/"><span style="color: #6495ED;"> ETH Zürich</span></a> and an <a href="https://ai.ethz.ch/"><span style="color: #6495ED;"> ETH AI Center</span></a> fellow, advised by <a href="https://mds.inf.ethz.ch"><span style="color: #6495ED;">Prof. Julia Vogt</span></a> and <a href="https://ei.is.mpg.de"><span style="color: #6495ED;">Prof. Bernhard Schölkopf</span></a>. In 2024, I interned at <a href="https://www.amazon.science"><span style="color: #6495ED;"> Amazon Science</span></a> in Tübingen, Germany, where I worked on diffusion-based generative modelling. Prior to joining ETH, I graduated from <a href="https://www.amazon.science"><span style="color: #6495ED;">EPFL</span></a> after a Master's Thesis at the <a href="https://www.mit.edu"><span style="color: #6495ED;">MIT</span></a> under the supervision of <a href="https://sensein.group"><span style="color: #6495ED;">Prof. Satrajit Ghosh</span></a>. At MIT, I worked on the modelling of 3D brain scans using GANs.

  I am broadly interested in **representation learning, (probabilistic) self-supervised (SSL) methods and generative modelling**, more specifically **understanding** how current methods work to then leverage this knowledge to **build general representations**. 
  
  During my PhD, I have been thinking about how we learn representations from observations in unsupervised settings. While discriminative methods (e.g., SimCLR, DINO) generally outperform reconstruction/generative ones (e.g., VAE, MAE), they often rely on less principled approaches. Instead reconstruction-based approach carry their load of challenges, but are driven by principled objectives and require less on prior knowledge about the downstream tasks of interests. 
  
  Early on during my PhD, I used <a href="/assets/pdf/iclr2023.pdf"><span style="color: #6495ED;">identifiability and causal representation learning to better understand discriminative SSL in multi-modal settings</span></a>. Later on, I explored <a href="/assets/pdf/simvae.pdf"><span style="color: #6495ED;">latent variable models as a mean to explain SSL and unify discriminative and generative methods</span></a>. More recently, I've explored Masked Autoencoders and proposed the <a href="/assets/pdf/mae.pdf"><span style="color: #6495ED;">space of principal components as a more principled and effective masking space for reconstructive SSL</span></a>. Finally, I am currently looking into the <a href="/assets/pdf/diet.pdf"><span style="color: #6495ED;">training dynamics of discriminative SSL, specifically how data characteristics affect these dynamics</span></a>.

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
