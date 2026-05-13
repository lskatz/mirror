---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

The mirroring is triggered every sunday, every time there is a git push event, and every time a github issue is placed in the `mirror` repo.

| name | This mirror's file | source | last updated |
| ---- | ------------------ | ------ | ------------ |
| NCBI Taxonomy | [taxdump.tar.gz]({{ site.baseurl }}/assets/taxdump.tar.gz) | [NCBI Taxonomy](https://ftp.ncbi.nih.gov/pub/taxonomy/taxdump.tar.gz) | {{ site.data.taxdump_download.last_download }} |
| PubMLST dbases | [dbases.xml]({{ site.baseurl }}/assets/dbases.xml) | [PubMLST](https://pubmlst.org/data/dbases.xml) | {{ site.data.dbases_download.last_download }} |
