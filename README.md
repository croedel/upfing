# Willkommen auf upfing.de!

Upfing.de ist eine privat betriebene, nicht kommerzielle Plattform für Autoren von Jung bis Alt, die Interessantes aus oder für der Region Germering zu berichten haben. Mehr über upfing.de findet ihr [hier](about.md)

## Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | prepend: site.github.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
