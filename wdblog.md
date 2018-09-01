---
layout: default

---
<div class="about-img">
</div>

<h1> Eternally Evolving Developer </h1>
<p> Continuously improving myself and learning new things.
  This is an archive of miscellaneous and noteworthy web development tidbits & hacks I've picked up.
</p>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>




<!--
You can find the source code for Jekyll at GitHub:
[jekyll][jekyll-organization] /
[jekyll](https://github.com/jekyll/jekyll)


[jekyll-organization]: https://github.com/jekyll -->
