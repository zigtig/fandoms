---
layout: character
---
Info:

{% if page.image %}
    ![{{page.name}}](/assets/img/{{page.image}})
{% endif %}

{{ page.conent | markdownify }}

<hr>

{% include character_shows.html character=page.show %}
