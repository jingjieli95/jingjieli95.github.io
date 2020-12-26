---
layout: page
permalink: /research/
title: Research
---

The following posts describe my featured research projects.

<ul class="listing">
{% for post in site.posts %}
  {% capture y %}{{post.date | date:"%Y"}}{% endcapture %}
  <li class="listing-item">
  	<b>{{ post.title }}</b> {{ post.description }} 
    <a href="{{ site.baseurl }}{{ post.url }}" title="{{ post.title }}">[show more]</a>
    <hr>  
  </li>
{% endfor %}
</ul>
<!-- <a href="{{ site.baseurl }}{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a> -->
<!-- "{{ site.baseurl }}{{ post.url }}" -->
<!-- <h2>Publications</h2>
<ul>
	<li>
		<b>"Paper title #1"</b><br>
		<i>List of authors</i><br>
		Conference, Year<br>
		<a href=""><div class="color-button">pdf</div></a><a href=""><div class="color-button">cite</div></a><a href=""><div class="color-button">code</div></a>
	</li><br>
	<li>
		<b>"Paper title #1"</b><br>
		<i>List of authors</i><br>
		Conference, Year<br>
		<a href=""><div class="color-button">pdf</div></a><a href=""><div class="color-button">cite</div></a><a href=""><div class="color-button">code</div></a>
	</li><br>
</ul>

<h2>Research Projects</h2>
<ul>
	<li>
		<b>Project title</b><br>
		University, Duration<br>
		<i>Other details such as advisor's name may go here</i><br>
		<a href=""><div class="color-button">report</div></a><a href=""><div class="color-button">code</div></a>
	</li><br>
	<li>
		<b>Project title</b><br>
		University, Duration<br>
		<i>Other details such as advisor's name may go here</i><br>
		<a href=""><div class="color-button">report</div></a><a href=""><div class="color-button">code</div></a>
	</li><br>
</ul>

<h2>Research Implementations</h2>
<ul>
	<li>
		<b>Title #1</b>: Brief description of this research implementation.<br>
		<a href=""><div class="color-button">paper</div></a><a href=""><div class="color-button">report</div></a><a href=""><div class="color-button">code</div></a>
	</li><br>
	<li>
		<b>Title #2</b>: Brief description of this research implementation.<br>
		<a href=""><div class="color-button">paper</div></a><a href=""><div class="color-button">report</div></a><a href=""><div class="color-button">code</div></a>
	</li><br>
</ul> -->