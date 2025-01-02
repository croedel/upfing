# Willkommen auf upfing.de!

Upfing.de ist eine privat betriebene, nicht kommerzielle Plattform, die Interessantes aus oder für die Region Germering berichtet. Mehr über upfing.de findet ihr [hier](about.md)

## Fotos

[Fotos von Christian](https://cloud.upfing.de:5001/photo/mo/sharing/67Yfntn2k)

## Aktuelle Artikel

{% for category in site.categories %}
  <h3>{{ category[0] }}</h3>
  <ul>
    {% for post in category[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
