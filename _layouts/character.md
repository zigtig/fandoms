# Character info

##{{ page.name }}

__{{ page.show }}__

{% if page.image %}
    ![{{page.name}}](/assets/images/{{page.image}})
{% endif %}

{{ page.conent | markdownify }}
