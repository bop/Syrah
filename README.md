# Syrah
Wine and Dine

<h2>{{ site.data.samplelist.docs_list_title }}</h2>
<ul>
   {% for item in site.data.samplelist.docs %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
   {% endfor %}
</ul>

## Red red
It seems just like a dream

[2](./page2.md) - [3](./page3.md)
