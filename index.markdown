---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

{%- for item in site.data.navigation.main -%}
  <a href="{{ item.url }}">{{ item.title }}</a>&nbsp;|&nbsp;
{%- endfor -%} <br />

The mirroring is triggered every sunday, every time there is a git push event, and every time a github issue is placed in the `mirror` repo.

| name | This mirror's file | source | last updated |
| ---- | ------------------ | ------ | ------------ |
| NCBI Taxonomy | [taxdump.tar.gz]({{ site.baseurl }}/assets/taxdump.tar.gz) | [NCBI Taxonomy](https://ftp.ncbi.nih.gov/pub/taxonomy/taxdump.tar.gz) | {{ site.data.taxdump_download.last_download }} |
