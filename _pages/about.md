---
permalink: /
title: 
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD. candidate in Economics at [New York University](https://as.nyu.edu/econ.html) and **I will be on the job market in 2024-2025**. 

I'm conducting research in Macroeconomics with particular interests in Labor and Firm Organization.

In 2024, I was a Dissertation Fellow at the Federal Reserve Bank of St. Louis and a PhD Summer Economics Fellow at the Federal Reserve Bank of Richmond.

My CV can be found [here](https://gstoledo.github.io/docs/Cv_GT.pdf)


## Job Market Paper

{% include base_path %}

{% for post in site.jmp reversed %}
{% include archive-single.html %}
{% endfor %}
