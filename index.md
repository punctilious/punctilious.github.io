<ul class="postlist">
  {% assign sorted = (site.posts | sort: 'date') | reverse %}
  {% for post in sorted %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    </li>
  {% endfor %}
</ul>
