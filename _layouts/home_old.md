<!-- THIS PART IS THE ORIGINAL FILE
<div class="article-author-side">
  {% include _author-bio.html %}
</div>
<article>
  <h1>{{ page.title }}</h1>
  <div class="article-wrap">
    {{ content }}
  </div><!-- /.article-wrap
  {% if site.owner.disqus-shortname and page.comments == true %}
    <section id="disqus_thread"></section><!-- /#disqus_thread -->
<!--{% endif %}
</article>
</div>

<!-- /#index -->


<!-- THIS PART CALLS THE ARCHIVE LIST FOR THE HOME
<div id="index">
  
  <h2><a href="{{ site.baseurl}}/p-posts/">Recent Publications</a></h2>
  {% for post in site.posts limit:5 %}    
  <article>
    {% if post.link %}
      <h2 class="link-post"><a href="{{ site.baseurl }}{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a> <a href="{{ post.link }}" target="_blank" title="{{ post.title }}"><i class="fa fa-link"></i></h2>
    {% else %}
      <h2><a href="{{ site.baseurl }}{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt | strip_html | truncate: 120 }}</p>
    {% endif %}
  </article>
  {% endfor %}
</div><!-- /#index -->

<!-- THIS PART IS THE ORIGINAL FILE

<div class="footer-wrap">
  <footer>
    {% include _footer.html %}
  </footer>
</div><!-- /.footer-wrap -->
<!--{% include _scripts.html %}
  
</body>
</html>
