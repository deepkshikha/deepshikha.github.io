---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div style="text-align: justify">   


Deepshikha is a  <strong>Sr. Data Scientist at <a href="https://www.nvidia.com/en-in/">NVIDIA</a><strong>. where her efforts are focused on building deep learning powered products and solutions . She has an experience of development of DL/ML products and solutions end to end.  Deepshikha is a Researcher with a background in Computer Science. Prior to NVIDIA, she worked as a AI researcher in NetApp R&D where she was focused on computer Vision algorithms. She holds a master’s degree in computer science  and Mathematics from Indian Institute of Technology, Patna where she mainly worked on NLP and Textual data under supervision of Dr. Pushpak Bhattacharyya. In her bachelor she worked on Autonomous robot as her Bachelor thesis. 

Her current research areas include – Multimodal Networks, Uncertainty in models,  Reinforcement learning and Autonomous application.


<!--</div>
<div style="text-align: justify">-->
</div>

## Recent posts
{% for post in site.posts %}
   - {{ post.date | date_to_string }} » [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}

