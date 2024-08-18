---
layout: "Layout1"
title: "Default front matter example"
permalink: "/default-front-matter"
---


<h3 style="color:white;">  Default front matter Navigation list </h3>

<div style="color:white">
{% for post in site.posts%}
<li>
<a style="color: darkblue" href="{{post.url}}"> {{post.title}}</a>
</li>
{% endfor %}



{% for people in site.data.people %}
{{people.name}} , {{people.Occupation}}
<br>
{% endfor %}

</div>
