---
layout: splash
author_profile: true
classes: landing
header:
  overlay_color: "#0078f4"
  overlay_filter: "0.5"
  overlay_image: /assets/images/header-os-1.svg
  actions:
    - label: "See more about FCA Services"
      url: "/FCA/"
  caption: "Detailed FCA services with Obermajer"
excerpt: "Innovating against Flood Risk: our focus is to make communities safer from flooding"
intro: 
  - excerpt: 'Obermajer`type="center"`'
feature_row:
  - image_path: assets/images/pat-photo.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: assets/images/ober_civils.png
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "/About/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: assets/images/ober_civils.png
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."

feature_row2:
  - image_path: /assets/images/pat-photo.jpg
    alt: "placeholder image 2"
    title: "Pat Obermajer"
    excerpt: 'Pat holds an MEng degree in Civil Engineering. He currently works as a civil engineer and flood risk consultant. His specialities include: \n - Flood Consequence Assessments \n - Civil Engineering Design \n - Programming, Data, GIS, and creating bespoke software tools'
    text: "Pat holds an MEng degree in Civil Engineering. He currently works as a civil engineer and a flood risk consultant. His specialities include: \n - Flood Consequence Assessments \n - Civil Engineering Design \n - Programming, Data, GIS, and creating bespoke software tools"
    url: "/About/"
    btn_label: "Read More About Us"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/FCA-Services.png
    alt: "placeholder image 2"
    title: "Find out about Flood Consequence Assessment Services"
    excerpt: 'Find out about FCA services and how we can assist with your project`'
    text: "Find out about FCA services and how we can assist with your project"
    url: "/FCA/"
    btn_label: "Read More About Our FCA Services"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/OBER-CIVILS-SPLASH.png
    alt: "placeholder image 4"
    title: "Discover Ober Civils Toolkit"
    excerpt: 'TDiscover Ober Civils Toolkit - a bespoke civil engineering, earthworks, and drainage design tool for AutoCAD"
    url: "#test-link'
    text: "Discover Ober Civils Toolkit - a bespoke civil engineering, earthworks, and drainage design tool for AutoCAD"
    url: "https://patryk-obermajer.github.io/help.html"
    btn_label: "More About Ober Civils Toolkit"
    btn_class: "btn--primary"
feature_row5:
  - image_path: /assets/images/portfolio.png
    alt: "placeholder image 4"
    title: "See Pat's Coding Portfolio"
    excerpt: "Find out more about Pat's coding projects"
    text: "Find out more about Pat's coding projects"
    url: "/programming-portfolio/"
    btn_label: "See Portfolio"
    btn_class: "btn--primary"

---
{% include feature_row id="intro" type="center" %}
<!-- 
{% include feature_row %} -->

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="left" %}
{% include feature_row id="feature_row5" type="right" %}


## Connect
Feel free to complete the form below and reach out:
{: .text-justify}


<!-- ![Pat juggling](assets/images/pat-juggling.png) -->

<form
  action="https://formspree.io/f/mjvnerzy"
  method="POST"
  
>
  <label>
    Your email:
    <input type="email" name="email">
  </label>
  <label>
    Your message:
    <textarea name="message" rows="3"></textarea>
  </label>
  <!-- your other form fields go here -->
  <button type="submit" class="btn btn--primary">Send</button>
</form>