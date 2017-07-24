# Willkommen auf upfing.de!

Upfing.de ist eine privat betriebene, nicht kommerzielle Plattform, die Interessantes aus oder für die Region Germering berichtet. Mehr über upfing.de findet ihr [hier](about.md)

## Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | prepend: site.github.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
