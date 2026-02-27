---
excerpt: " Ready. Set. Swing!" # NOTE: space at the beginning for alignment
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/img/landing.jpg
#   caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
  actions:
    - label: "What We Offer"
      url: "/#main" 
# grid offerings
feature_row:
  - image_path: /assets/img/camp_feature2.jpg
    alt: "Camp"
    title: "Summer Camp"
    url: "#test-link"
    btn_label: "Learn More"
    btn_class: "btn--inverse"
    excerpt: "We offer full and half day camps on weekdays from June to August. We guarantee a student:coach ratio of 10:1 or less, and a minimum of 4 hours on court (weather permitting)."
  - image_path: /assets/img/kids_feature3.jpg
    title: "Kids"
    excerpt: "We offer year round lessons that follow Tennis Canada’s Progressive Tennis framework, which uses modified courts, balls, and racquets so players learn skills in the most effective and enjoyable way possible."
    url: "#test-link"
    btn_label: "Learn More"
    btn_class: "btn--inverse"
  - image_path: /assets/img/adult_feature4.jpg
    title: "Adult"
    url: "#test-link"
    btn_label: "Learn More"
    btn_class: "btn--inverse"
    excerpt: "Our adult programs are designed for players who want to learn properly, improve efficiently, and actually enjoy playing tennis. Classes are grouped by playing level, so you’re always training with players at a similar stage."
feature_row_newtonbrook:
  - image_path: /assets/img/newtonbrook.jpeg
    title: "Newtonbtook"
    excerpt: '227 Otonabee Ave, North York, ON M2M 2S9 <br> <br> Available: <br> Privates <br>Semi-privates'
    # url: "#test-link" 
    # btn_label: "Book"
    # btn_class: "btn--inverse"
feature_row_maryvale:
  - image_path: /assets/img/maryvale.jpeg
    title: "Maryvale"
    excerpt: '5 Trestleside Grove, Scarborough, ON M1R 5A9 <br> <br> Available: <br> Adult group <br>Kids group <br>Summer camp <br>Privates  <br>Semi-privates'
    # url: "#test-link"
    # btn_label: "Book"
    # btn_class: "btn--inverse"
feature_row_dunlace:
  - image_path: /assets/img/dunlace.jpeg
    title: "Dunlace"
    excerpt: '28 Dunlace Dr, North York, ON M2L 2S1 <br> <br> Available: <br> Adult group <br>Kids group <br>Summer camp <br>Privates  <br>Semi-privates'
    # url: "#test-link"
    # btn_label: "Book"
    # btn_class: "btn--inverse"

permalink: /
---

{% include feature_row %}

{% include figure image_path="/assets/img/clubs_header.png" %}

{% include feature_row id="feature_row_maryvale" type="left" %}

{% include feature_row id="feature_row_dunlace" type="left" %}
{% include feature_row id="feature_row_newtonbrook" type="left" %}