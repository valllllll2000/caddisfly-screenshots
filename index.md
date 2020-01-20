## Screenshots

{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
   <img src="https://valllllll2000.github.io/test-pages/{{myimage.path}}" width="200"/>
{% endfor %}
