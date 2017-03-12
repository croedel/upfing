# Willkommen auf upfing.de!

Upfing.de ist eine privat betriebene, nicht kommerzielle Plattform für Autoren von Jung bis Alt, die Interessantes aus oder für der Region Germering zu berichten haben.

Um Artikel kommentieren zu können, oder auch selbst Autor zu werden, benötigst du einen Account auf [github.com](https://github.com).

Die große Kreisstadt Germering liegt im Westen von München. Sie besteht aus 4 Stadtteilen: Germering, Neu-Germering, Unterpfaffenhofen und Harthaus.

Upfing ist eine Kunstwort aus Unterpfaffenhofen und Germering und findet Verwendung als liebervoller Spitzname für den Stadtteil Unterpfaffenhofen. Die Bewohner werden auch „Upfer“ genant.

Nähere Infos zu unserer Stadt findet ihr hier:

* [Homepage der Stadt Germering](http://www.germering.de)
* [Germering auf Wikipedia](http://de.wikipedia.org/wiki/germering)
  
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>  
