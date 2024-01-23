# Character info

##{{ page.name }}

__{{ page.show }}__

{% if page.image %}
    ![{{page.name}}](/assets/img/{{page.image}})
{% endif %}

{{ page.conent | markdownify }}
