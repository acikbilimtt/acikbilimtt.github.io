---
layout: page
title: Yazılar
---
<ul class="posts">
  {% for post in site.posts %}

    {% unless post.next %}
      <h3>{{ post.date | date: '%Y' }}</h3>
    {% else %}
      {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
      {% capture nyear %}{{ post.next.date | date: '%Y' }}{% endcapture %}
      {% if year != nyear %}
        <h3>{{ post.date | date: '%M %Y' }}</h3>
      {% endif %}
    {% endunless %}

    <li itemscope>
      <a href="{{ site.github.url }}{{ post.url }}">{{ post.title }}</a>
      <p class="post-date"><span><i class="fa fa-calendar" aria-hidden="true"></i> {{ post.date | date: "%d/%m/%Y" }} - <i class="fa fa-pencil" aria-hidden="true"></i> {% assign author = site.authors | where: 'code_name', post.authors | first %}{% if author %}<a href="{{ author.url }}">{{ author.name }}</a>{% endif %} - <i class="fa fa-clock-o" aria-hidden="true"></i> {% include read-time.html %}</span></p>
    </li>

  {% endfor %}
</ul>
