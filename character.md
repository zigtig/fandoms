---
layout: character
---
Info:

{% if page.image %}
    ![{{page.name}}](/assets/img/{{page.image}})
{% endif %}

{{ page.conent | markdownify }}

<hr>

{% if page.show %}
    {% include character_show.html show=page.show %}
{% endif %}