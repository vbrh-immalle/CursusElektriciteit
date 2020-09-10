
# Time

{{ site.time }}

# Collections

<!-- <ul>
{% for item in site.hst1 %}
    <li>
        {{ item.title }}
    </li>
{% endfor %}
</ul> -->

<!-- {{ site.hst1 }} -->


# Layout

{{ layout }}

# Page

{{ page }}

# Static files

{% for item in site.static_files %}

- {{ item }}

{% endfor %}

# Pages
{% for page in site.pages %}

- {{ page.name }} ({{ page.id }}) {{ page.collection }} {{ page.dir }} {{ page.path }}

{% endfor %}

# Site.Documents

{% for item in site.documents %}

- {{ item }}

{% endfor %}



