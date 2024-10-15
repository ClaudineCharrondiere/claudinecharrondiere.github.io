---
permalink: /
title: "About me"
excerpt: "Claudine Charrondière"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

With a doctorate and research experience in environmental fluid mechanics, I specialize in understanding complex atmospheric and mechanical phenomena from different scales ranging from turbulent scales, to the scale of the atmospheric boundary layer. My work has taken me from the steep alpine slopes of the French Alpes to the atmospheric research lab of Innsbruck and and its extensive network of measurement sites, where I’ve led experiments and collected meteorological data. Along the way, I’ve developed expertise in experimental research, data analysis, and advanced computational tools, with a focus on fluid dynamics in natural environments. My connection to the LEGI in Grenoble led me to analyze the environnemental fluids with the support of theoretical and industrial fluid mechanics knowledges. 

Environmental Fluid Dynamics Researcher
======
Driven by a passion for applied research, I have contributed to international projects such as the ERC UNICORN and TEAMx initiatives. My academic journey has been recognized with awards such as the Jean Valembois Prize for Fluid Mechanics, and I have published papers in leading scientific journals.
Currently, I am thrilled to expand my expertise into numerical modeling and industrial applications, where I aim to bridge the gap between academic research and practical, real-world solutions. My goal is to contribute to solving complex environmental challenges through innovative approaches in fluid dynamics.


Publications
======
Below are listed my publications, from the latest to the oldest. You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=dYquXRYAAAAJ).

{% for post in site.publications reversed %}
  {% include archive-single-short.html %}
{% endfor %}
