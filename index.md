# Homepage
Here are where you can find my write ups for each week in Oregon State's Defense Against the Dark Arts class!

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/CS373/{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>