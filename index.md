<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p><i>{{ post.date  | date: "%-d %B %Y"}} - written by {{ post.author }}</i></p>
      {{ post.excerpt }}
      <p style="text-align: right;"><a href="{{ post.url }}">Continue reading...</a></p>
    </li>
  {% endfor %}
</ul>
