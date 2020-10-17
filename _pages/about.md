---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD Candidate at <a href="https://www.imt-atlantique.fr">IMT Atlantique</a> and a research scientist at <a href="https://www.lab-sticc.fr">Lab-STICC</a>. I am also a collaborator of <a href="https://meridian.cs.dal.ca">MERIDIAN</a>. My research interests focus on  the study of <strong>Machine Learning (Deep Learning)</strong> for <strong>time series analysis</strong>, especially for stochastic, noisy and irregularly sampled data.

## Recent posts
{% for post in site.posts %}
   - {{ post.date | date_to_string }} » [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}
