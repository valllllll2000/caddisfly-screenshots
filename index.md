<style>
.image {
   display: inline-block;
   margin: 2px 2px 2px 2px;
}
</style>

{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
   <div class="image" style="max-width: 30%;">
      <img src="https://akvo.github.io/caddisfly-screenshots/{{myimage.path}}"/>
   </div>
{% endfor %}
