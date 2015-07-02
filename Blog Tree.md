---
layout: page
title: Blog Tree
---

<!-- List all Posts -->
{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}

<!-- List all Categories -->

<h1>Categories in Blog:</h1>
<ul>
{% for category in site.categories %}
  <li><a name="{{ category | first }}">{{ category | first }}</a>
    <ul>
    {% for posts in category %}
      {% for post in posts %}
        <li>
        <a href="{{ post.url }}">{{ post.title }}</a>, 
    <span class="date">{{ post.date | date: "%B %-d, %Y"  }}</span>
        </li>
      {% endfor %}
    {% endfor %}
    </ul>
  </li>
{% endfor %}
</ul>

<!-- List all Tags -->

<h1>Tags in Blog:</h1>
<ul>
{% for tag in site.tags %}
  {% assign t = tag | first %}
  {% assign posts = tag | last %}

<li>{{ t | downcase }}</li>
<ul>
{% for post in posts %}
  {% if post.tags contains t %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>, 
    <span class="date">{{ post.date | date: "%B %-d, %Y"  }}</span>
  </li>
  {% endif %}
{% endfor %}
</ul>
{% endfor %}
</ul>