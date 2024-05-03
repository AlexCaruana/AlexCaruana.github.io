---
layout: archive
# title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
 -->

Publications
======
## Peer-reviewed Publications:
[2] **Caruana A**, Camilleri B, Farrugia L, Jones JPG. 2024. Mechanical excavation of wetland habitat failed to eradicate invasive American red swamp crayfish (Procambarus clarkii) in Malta. Ecological Solutions and Evidence. [https://doi.org/10.1002/2688-8319.12325](https://doi.org/10.1002/2688-8319.12325)

[1] Shackelford, N., [and 76 others, including **Caruana, A.**] et. al. 2021. Drivers of seedling establishment success in dryland restoration efforts. Nature Ecology and Evolution. [https://www.nature.com/articles/s41559-021-01510-3](https://www.nature.com/articles/s41559-021-01510-3)

## Reports:
[1] **Caruana A**, Farrugia L. 2023. Assessment of Red Swamp Crayfish presence, distribution and abundance within the Fiddien valley system. Pages 1–53. Applied Ecological Resources. [https://www.britishecologicalsociety.org/applied-ecology-resources/document/20240157815/](https://www.britishecologicalsociety.org/applied-ecology-resources/document/20240157815/)

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}