---
layout: page
title: Peer Reviews
permalink: /reviews/
---

# Verified Peer Reviews

These Verified Peer Reviews represent the records of reviews conducted for journals according to Web of Science (WoS) standards. You can verify these reviews by visiting the following link: [link to WoS profile](https://www.webofscience.com/wos/author/record/R-7254-2019).

<table>
  {% for row in site.data.reviews %}
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

