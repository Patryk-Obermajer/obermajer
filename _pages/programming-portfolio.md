---
permalink: /programming-portfolio/
layout: single
author_profile: true
layout: single
classes: wide
title: "Portfolio"

feature_row0:
  - image_path: assets/images/Ober-pipe-classifier.png
    alt: "Ober Pipe Condition Classifier"
    title: "Ober Pipe Condition Classifier"
    text: "A Convolutional Neural Network sequential model, trained from scratch on drainage survey footage. We are using Keras library for image classification based on condition of the drains and then export it as a Tensor Flow Lite model. "
    url: "https://github.com/Patryk-Obermajer/Ober-Pipe-Condition-Detector"
    btn_label: "Code on GitHub"
    btn_class: "btn--primary"

feature_row1:
  - image_path: assets/images/ober_civils.png
    alt: "Ober Civils Toolkit"
    title: "Ober Civils Toolkit"
    text: "Civil Engineering Toolkit for AutoCAD: The Toolkit helps improve efficiency of civil engineering tasks within AutoCAD, focusing on the day-to-day needs of residential engineers. It streamlines a wide range of routine tasks and also offers automation for various non-residential but essential operations. It is widely adopted by numerous civil and residential-structural engineers in the field."
    url: "https://github.com/"
    btn_label: "Details"
    btn_class: "btn--primary"
    tags:
        - Civil Engineering Design Tool
        - VLISP
        - AutoLISP

feature_row2:
  - image_path: assets/images/polynomial.png
    alt: "Polynomial Curve Fitting"
    title: "Polynomial Curve Fitting"
    text: "Here's a quick exercise in curve fitting to reverse-engineer an old CWI/SAAR plot from NERC (1975) Flood Studies Report (FSR) - Plot of catchment wetness index, CWI, against mean annual rainfall, SAAR. We aim to replace repetitive graph referencing with a single equation. We work out a polynomial expression that will get the CWI value for a given SAAR. All we are using is pandas, numpy, and matplotlib for the plots."
    url: "https://github.com/Patryk-Obermajer/CWI-vs-SAAR---Polynomial-Interpolation/"
    btn_label: "Code on GitHub"
    btn_class: "btn--primary"
    # tags:
    #     - Civil Engineering Design Tool
    #     - VLISP
    #     - AutoLISP

feature_row3:
  - image_path: assets/images/maths.png
    alt: "Quick multiplication by two with TensorFlow"
    title: "Quick multiplication by two with TensorFlow"
    text: "We're training a simple neural network, with one neuron at both the input and output, to double numbers in NumPy arrays, multiplying them by 2. It obviously learns to do this for any new numbers it encounters, without ever seeing the multiplication formula."
    url: "https://github.com/Patryk-Obermajer/Multiplication-Learning-with-Keras"
    btn_label: "Code on GitHub"
    btn_class: "btn--primary"

    # tags:
    #     - Civil Engineering Design Tool
    #     - VLISP
    #     - AutoLISP

# feature_row4:
#   - image_path: assets/images/QBAR-Calc.png
#     alt: "QBAR Calculator"
#     title: "QBAR Calculator in C#"
#     text: "We're training a simple neural network, with one neuron at both the input and output, to double numbers in NumPy arrays, multiplying them by 2. It obviously learns to do this for any new numbers it encounters, without ever seeing the multiplication formula."
#     url: "https://github.com/Patryk-Obermajer/Multiplication-Learning-with-Keras"
#     btn_label: "Code on GitHub"
#     btn_class: "btn--primary"

---

Below is a small selection of the plethora of scripts, projects, and little repos I wrote over the years.


{% include feature_row id="feature_row0" type="left" %}
<a name="Ober Pipe Condition Classifier"></a>
{% include feature_row id="feature_row1" type="left" %}
<a name="Ober Civils Toolkit"></a>
{% include feature_row id="feature_row2" type="left" %}
<a name="Polynomial Curve Fitting"></a>
{% include feature_row id="feature_row3" type="left" %}
<a name="Quick multiplication"></a>
{% include feature_row id="feature_row4" type="left" %}
<a name="QBAR Calc"></a>

Get in touch using the form below if you'd like.

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