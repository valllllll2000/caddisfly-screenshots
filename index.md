## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/valllllll2000/test-pages/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/valllllll2000/test-pages/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

---
layout: default
images:
  - image_path: /images/cakes/apple-pie.jpg
    title: Apple Pie
  - image_path: /images/cakes/birthday-cake.jpg
    title: Birthday Cake
  - image_path: /images/cakes/black-forest.jpg
    title: Black Forest
  - image_path: /images/cakes/brownie.jpg
    title: Brownie
  - image_path: /images/cakes/cheese-cake.jpg
    title: Cheese Cake
  - image_path: /images/cakes/chocolate-cake.jpg
    title: Chocolate Cake
  - image_path: /images/cakes/fruit-cake.jpg
    title: Fruit Cake
  - image_path: /images/cakes/lamington.jpg
    title: Lamington
  - image_path: /images/cakes/lemon-cake.jpg
    title: Lemon Cake
---
<ul class="photo-gallery">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>
