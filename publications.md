---
layout: page
title: Publications
permalink: /publications/
---

Explore our Publications section to discover our latest scientific research. These publications are available for verification via the Web of Science [(link WoS)](https://www.webofscience.com/wos/author/record/R-7254-2019) and Scopus [(link Scopus)](https://www.scopus.com/authid/detail.uri?authorId=57189249053).

<table>
  {% for row in site.data.articles %}
    {% if forloop.first %}
    <tr>
      {% for pair in row %}
        <th>{{ pair[0] }}</th>
      {% endfor %}
    </tr>
    {% endif %}

    {% tablerow pair in row %}
      {{ pair[1] }}
    {% endtablerow %}
  {% endfor %}
</table>