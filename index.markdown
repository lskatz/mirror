---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
---

{% for item in site.data.navigation %}
  <a href="{{ item.url }}">{{ item.title }}</a>
{% endfor %}

| name | file | src mirror | cadence |
| ---- | ---- | ---------- | ------- |
| NCBI Taxonomy | [taxdump.tar.gz]({{ site.baseurl }}/assets/taxdump.tar.gz) | <https://ftp.ncbi.nih.gov/pub/taxonomy/taxdump.tar.gz> | On git push and every Sunday |
