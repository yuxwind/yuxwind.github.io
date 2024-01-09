---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Research experience
======

* University of Utah                                        Salt Lake City, UT
    * Research Assistant, Computer Vision Group and Data Group 2016.8 - Present
        * On SLAM                    
            * Proposed a system to register sparse 3D scans using alternating projection~\cite{ranade2020mapping}
            * Built an image-based localization system for vehicles by aggregating image \\ semantic edges~\cite{yu2018vlase}
        * On Network Pruning      
            * Studying network pruning with Bayesian variable selection and combinatorial \\ optimization methods
            * Built a linear programming system to scale up exact neural network compression \\by ReLU stability~\cite{serra2021scaling}            
            * Proposed a layer-wise pruning algorithm to achieve strict identity mappings \\ in deep residual networks~\cite{yu2018learning}     
        * On 3D Reconstruction        
            * Proposed a GCN framework for 3D face reconstruction 
            * from a single image \\ with SOTA performance
        * on Sentiment Analysis       
            * Built a framework of spatio-temporal sentiment analysis on tweets to predict \\ the US election 2016~\cite{paul2017compass}

* Mitsubishi Electric Research Laboratories                Cambridge, MA

    * Research Intern, Computer Vision Group                   2019.5 - 2019.11
        * Intern project: 3D Human Shape Recovery from A Single Image with Bilayer-Graph
        * Proposed a deep human shape reconstruction framework with SOTA performance

Education
======

* Master in Computer Science, University of Utah, 2016 - 2018
* Ph.D in Computer Science, University of Utah, 2018 - Now

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<!---
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
--->

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* PC Member / Reviewers for RIOS
