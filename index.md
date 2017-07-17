<ul>
  {% assign sorted = (site.posts | sort: 'date') | reverse %}
  {% for post in sorted %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
