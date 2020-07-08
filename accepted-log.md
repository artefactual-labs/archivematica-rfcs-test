---
title: Accepted log
---

## Currently accepted records

<!-- markdownlint-disable MD013 -->

{% assign subpage = site.pages | where: 'status', 'accepted' %}
{% for item in subpage %}* [{{ item.adr }}-{{ item.title }}]({{ item.url }}) - {{ item.title }}
{% endfor %}

## Currently proposed records

{% assign subpage = site.pages | where: 'status', 'proposed' %}
{% for item in subpage %}* [{{ item.adr }}-{{ item.title }}]({{ item.url }}) - {{ item.title }}
{% endfor %}

<!-- adrlogstop -->

<!-- markdownlint-enable MD013 -->

<!-- markdownlint-disable MD013 -->

<!-- markdownlint-enable MD013 -->

<!-- ## Proposed records -->

<!-- ## Superseded records -->

<!-- ## Rejected records -->

<!-- ## Deprecated records -->
