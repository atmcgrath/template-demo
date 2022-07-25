---
layout: single
permalink: /all/
title: List of contents
header:
    # image: /assets/images/home.jpg  # Putting the path to an image here will replace the header image.
    # alt: "Describe your image here" # It is good practice to include an image desription as alt text.
    # caption: # Put a caption for your image here. It will display in the bottom right corner of the image.
toc: false
toc_label: {{ page.title }}

sidebar: 
    nav: "categories"


---

<div >
  <ul>
  {% for item in site.projects %}

    <li>
      <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
      </a>
    </li>
  {% endfor %}
  </ul>
</div>