<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p><i>{{ post.date  | date: "%-d %B %Y"}} - written by {{ post.author }}</i></p>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
