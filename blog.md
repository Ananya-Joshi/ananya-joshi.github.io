--- 
layout: default
title: Blog
permalink: /blog/ 
---
### Blogs and News


<div class="row">
<div class="col-1"> </div>
<h4 class="col-2">  </h4>
<h4 class="col-7"> </h4>
<h4 class="col-2 d-flex justify-content-center align-self-center">   Word Count </h4>
	<div class="col-4"> </div>
</div>
{% for post in site.posts %}
<div class="row">
<div class="col-1"> </div>
<div class="col-2 d-flex justify-content-center align-self-center"><span class="align-middle"> <p >{{ post.date | date: "%B %e, %Y" }}</p> </span></div>
  <div class="col-7">
  <h4><a href="{{ baseurl }}{{ post.url }}">{{ post.title }}</a></h4><p>{{ post.excerpt }}</p>
  <hr/>
</div>
<div class="col-2 d-flex justify-content-center align-self-center"><p>{{ post.content | strip_html | split: ' ' | size }}</p>
</div>
</div>
{% endfor %}