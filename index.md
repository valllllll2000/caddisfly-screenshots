{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
   <img style="max-width:20%" src="https://valllllll2000.github.io/test-pages/{{myimage.path}}"/>
{% endfor %}
