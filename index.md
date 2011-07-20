---
layout: base
title: Welcome
menu: menuHome
---


Welcome...
-----------

[<img alt="D&ouml;rte Hessler" src="images/me_web.png" class="rechts">] (/contact)

... on my webpage! For now you will find here mainly information about my research:
Currently I am a PhD-student in Neurolinguistics at the University of Groningen.  Next to a description of the project I am working on now, you can also find information on publications, talks and previous work. Also you might want to have a look at some links I can recommend!

   
If you want to contact me please send a mail to: me (at) doerte (dot) eu     
  
<h2>Latest Blogposts</h2>

{% for post in site.posts limit:3 %}
  <div class="post">
    {{ post.date | date_to_string }} &raquo; <a href="{{ post.url }}">{{ post.title }}</a>
	</div>
{% endfor %}

More entries and my Twitter feed can be found in my [blog](/Blog).



