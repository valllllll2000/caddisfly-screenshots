<style>
.image {
   display: inline-block;
}
</style>

{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
   <div class="image" style="max-width: 30%;">
      <img src="https://valllllll2000.github.io/test-pages/{{myimage.path}}"/>
   </div>
{% endfor %}
