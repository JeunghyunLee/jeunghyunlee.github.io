--- 
layout: single
permalink: /
hidden: true
header:
  overlay_color: "#66b5ed"
  overlay_filter: "0.7"
  overlay_image: /assets/images/home_image.png
  text_color: black
  actions:
  - label: "<i class='fa-solid fa-volume'></i> How to read my name "
    url: "http://ipa-reader.xyz/?text=%CA%A4%C9%9B%C5%8B%20hj%CA%8Cn&voice=Nicole"

intro:
  - excerpt: 'I study *clinical psychology* using *neuroimaging techniques* and *computational modeling*.'
  
feature_row:
  - image_path: assets/images/splash-idea.png
    alt: "projects"
    title: "Projects"
    excerpt: "My recent **projects** and **presentations**"
    url: "https://jeunghyunlee.github.io/research-interests/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: assets/images/splash-cv.png
    alt: "cv"
    title: "CV"
    excerpt: "Curriculum Vitae."
    url: "https://jeunghyunlee.github.io/cv/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: assets/images/splash-blogs.png
    alt: "publications"
    title: "Publications"
    excerpt: "My recent publication"
    url: "https://jeunghyunlee.github.io/publications-archive/"
    btn_label: "Read More"
    btn_class: "btn--primary"
---
{% include header id="header" type="center" %}

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

