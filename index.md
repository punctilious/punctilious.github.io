<ul class="postlist">
  {% assign sorted = (site.posts | sort: 'date') | reverse %}
  {% for post in sorted %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    </li>
  {% endfor %}
</ul>
