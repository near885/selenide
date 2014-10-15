<ul class="main-menu-pages">
  <li><a href="{{ BASE_PATH }}/quick-start.html">Quick start</a></li>
  <li><a href="{{ BASE_PATH }}/documentation.html">Documentation</a></li>
  <li><a href="{{ BASE_PATH }}/faq.html">FAQ</a></li>
  <li><a href="{{ BASE_PATH }}/blog.html">Blog</a></li>
  <li><a href="{{ BASE_PATH }}/javadoc.html">Javadoc</a></li>
  <li><a href="{{ BASE_PATH }}/users.html">Users</a></li>
  <li style="display:none;"><a href="{{ BASE_PATH }}/quotes.html">What users say?</a></li>
  <li><a href="{{ BASE_PATH }}/contacts.html">Feedback</a></li>
  <li style="display:none;"><a href="{{ BASE_PATH }}/thanks.html">Our thanks</a></li>
</ul>

<div class="news">
  <div class="news-line"><a class="video" href="//vimeo.com/107647158">How to write UI test in 10 minutes</a></div>
</div>

<h3 style="display:none">Blog</h3>
<div class="archive" style="display:none">
  {% assign posts_collate = site.posts %}
  {% include JB/posts_collate %}
  <a href="{{ BASE_PATH }}/archive.html" class="right small">Blog archive</a>
</div>