<div class="posts">
  <ul>
    <h1>All Posts</h1>
    {% for post in site.posts %}
      <li>
        <a href="{{ post.url }}">
          <h2>{{ post.title }}</h2>
        </a>
      </li>
    {% endfor %}
  </ul>
</div>   