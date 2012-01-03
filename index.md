---
layout: base
title: Welcome ...
menu: menuHome
submenu: xyz
---


[<img alt="D&ouml;rte Hessler" src="images/me_web.png" class="rechts">] (/contact)

... on my webpage! For now you will find here mainly information about my research:
I recently finished my PhD research in Neurolinguistics at the University of Groningen. Now I work there as an assistant professor.
My main task is to set-up and coordinate the Center of Expertise for Language and Communication Disorders, which is a collaboration of the Faculty of Arts,
the Faculty of Behavioral and Social Sciences and the University Medical Center Groningen. More information about the center will be put here soon.
Next to the work for the center I also teach in the department of Neurolinguistics. 
On this website you can find a short description of my PhD project. You can also find information on publications, talks and previous work. Also you might want to have a look at some links I can recommend!

   
If you want to contact me please send a mail to: me (at) doerte (dot) eu     
  
<h2>Latest Blogposts</h2>

{% for post in site.posts limit:3 %}
  <div class="post">
    {{ post.date | date_to_string }} &raquo; <a href="{{ post.url }}">{{ post.title }}</a>
	</div>
{% endfor %}

More entries and my Twitter feed can be found in my [blog](/Blog).



