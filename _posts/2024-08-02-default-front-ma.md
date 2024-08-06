---
layout: "Layout1"
title: "Default front matter example"
permalink: "/default-front-matter"
---


Default front matter Navigation list

{% for post in site.posts%}
<li>
<a href="{{post.url}}"> {{post.title}}</a>
</li>
{% endfor %}



{% for people in site.data.people %}
{{people.name}} , {{people.Occupation}}
<br>
{% endfor %}
