---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD Candidate at <a href="https://www.imt-atlantique.fr">IMT Atlantique</a> and a research scientist at <a href="https://www.lab-sticc.fr">Lab-STICC</a> in the field of <strong>Machine Learning (Deep Learning)</strong>. I am also a collaborator of <a href="https://meridian.cs.dal.ca">MERIDIAN</a> and a mentor at <a href="https://funix.edu.vn">FUNiX</a>. My research interests focus on <strong>time series analysis</strong>, especially on modeling stochastic, noisy and irregularly sampled data using variational deep learning approaches.

## Recent posts
{% for post in site.posts %}
   - {{ post.date | date_to_string }} » [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}
