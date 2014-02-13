---
layout: default
title: Home
---

<!DOCTYPE HTML>
<html>
	<head>
		<title>Advanced Web Design Class</title>
	</head>
	<body>
	
	<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


	  	<a href="index.html"><h1>Japheth Crawford - Advanced Web Design</h1></a>
		<a href="blog1.html"><h3>Week One - Project Status</h3></a>
		<a href="blog2.html"><h3>Week One - Favorite Internet Things</h3></a>
		<a href="blog4.html"><h3>Week Two - Project Status</h3></a>
		<a href="blog3.html"><h3>Week Two - Favorite Internet Things</h3></a>
		<a href="blog6.html"><h3>Week Three - Project Status</h3></a>
		<a href="blog5.html"><h3>Week Three - Favorite Internet Things</h3></a>
		
	</body>
</html>