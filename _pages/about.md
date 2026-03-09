---
permalink: /
title: "Ioannis Farmakis, PhD"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p>
    As a postdoctoral researcher, I collaborate with teams to design and apply deep learning methods for geo-environmental and structural monitoring applications.
    This journey has already taken me to the <a href="https://www.newcastle.edu.au">University of Newcastle</a> 🇦🇺, <a href="https://www.uniroma1.it/en">Sapienza University of Rome</a> 🇮🇹, and the <a href="https://www.ntua.gr/en/">National Technical University of Athens</a> 🇬🇷.
    Before that, I completed my PhD on <em>"3D Point Clouds and Machine Learning Applications in Rock Slope Modelling"</em> at <a href="https://www.queensu.ca">Queen's University</a> 🇨🇦.
    <br><br>

</p>

{% if site.news %}
News
------
{% for post in site.news reversed %}
    {% include archive-single-news.html %}
{% endfor %}
{% endif %}