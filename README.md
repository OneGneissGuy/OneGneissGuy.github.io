<div class="posts">   
  <ul>
    <h1>Recent Posts</h1>
    {% for post in site.posts limit: 3 %}
      <li>
        <a href="{{ post.url }}">
          <h2>{{ post.title }}</h2>
        </a>
      </li>
    {% endfor %}
  </ul>
</div>

I post about electronics and software projects that I work on in my daily life. I'll typically write about electronics like environmental sensors, microcomputers (ala Raspberry Pi and Arduino) and remote control and autonomous (drones) planes, helicopters and quadcopters.   

I'll also post about my forays into data science using Python and R.

Check out my [GitHub]({{ site.github.owner_url }}) contributions.

Learn more [about]({{ site.baseUrl }}/about) me.
