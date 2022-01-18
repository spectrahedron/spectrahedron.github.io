<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ page.date  | date: "%-d %B %Y"}} - written by {{ page.author }}</p>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
