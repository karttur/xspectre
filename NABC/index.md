---
layout: page
title: Business model (NABC)
excerpt: "Spectrometer miniaturization and Artificial Intelligence (AI) drives a new era in spectral sensing."
search_omit: true
---

## NABC - Need, Approach, Benefit, Competition

xSpectre's business model is developed using the NABC framework, first put forward by the Stanford Research Institute (SRI). We participated in [Linköping University Entrepreneurship and Development (LEAD)](https://www.lead.se/en/) BootUp program during spring 2022. LEAD then used our innovation for a trainee program, [Entrepreneurs in Residence](https://www.lead.se/en/entrepreneur-programs/entrepreneurs-in-residence/), during the autumn of 2022. The report on xSpectre from the trainee program is linked below.

<ul class="post-list">
{% for post in site.categories.NABC reversed %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %}</a></article></li>
{% endfor %}

{% for post in site.categories.lead-report reversed %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>
