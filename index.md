---
layout: default
usemathjax: true
---

This site belongs to Jing-Jin Hu (胡京津) , a young condensed-matter physicist. She is currently in <a href="http://www.phy.pku.edu.cn/~xilin/index.html"> Prof. Xi Lin's group</a> at Peking University.

<h1><a name="ResearchInterest">Research Interests</a></h1>
* Low temperature electronic transport;
* Novel material.

<h1><a name="Projects">Projects</a></h1>

## Current Projects

<li>
<a href="projects/2DEG">
	<img src="images/2DEG/IMG_0118.PNG" width="400px">
	2D electron gas (2DEG) on liquid Helium.
</a>
</li>
* Electronic transport in factal structures.

## Previous Projects

* 1.8K refrigerator. 

<h1>Building Blog</h1>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>