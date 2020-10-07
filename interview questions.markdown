---
layout: page
title: Interview Questions
permalink: /interview/
---

Interview questions and answers goes here!!

<ul>
{% for val in site.data.java %}
  <li>
	  <b>{{ val.question }}</b>
      {{ val.ans }}
   
  </li>
{% endfor %}
</ul>