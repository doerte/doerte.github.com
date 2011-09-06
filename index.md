---
layout: base
title: Welcome
menu: menuHome
---


Welcome...
-----------

[<img alt="D&ouml;rte Hessler" src="images/me_web.png" class="rechts">] (/contact)

... on my webpage! For now you will find here mainly information about my research:
I recently finished my PhD research in Neurolinguistics at the University of Groningen. Now I work there as a part-time lecturer, teaching Psycholinguistics. Furthermore, I own a small translation company, called [Parolanto](http://parolanto.nl). On this website you can find a description of my PhD project. You can also find information on publications, talks and previous work. Also you might want to have a look at some links I can recommend!

   
If you want to contact me please send a mail to: me (at) doerte (dot) eu     
  
<h2>Latest Blogposts</h2>

{% for post in site.posts limit:3 %}
  <div class="post">
    {{ post.date | date_to_string }} &raquo; <a href="{{ post.url }}">{{ post.title }}</a>
	</div>
{% endfor %}

More entries and my Twitter feed can be found in my [blog](/Blog).



