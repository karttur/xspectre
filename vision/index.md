---
layout: page
title: Vision
excerpt: "Combining modern soil sensing with a user community enabling local knowledge for solving global problems."
search_omit: true
---

## Supporting farmer livelihood

The escalating costs for fuels and fertilizers jeopardise the economy of farmers, herders and ranchers. Widespread loss in soil fertility and soil health threaten not only the economic sustenance of farming but also the ecological foundation of the soil itself. Soils contribute about 5 % of the human caused global warming by the lost soil carbon entering the atmosphere as the green house gas carbon dioxide. New approaches and solutions for both economic and ecological sustainability are urgently required. xSpectre's _Swiss army knife for soil sensing_ is a toolset for supporting eco-sustainability in farming, herding and ranching.

## Climate impact

The climate and soil health effects of regenerative farming are difficult and costly to monitor and verify. Yet it has the potential to reverse the flux of climate gases and turn soils from decaying and releasing green house gases to capturing carbon and improving soil health by increasing the soil organic carbon (SOC) content. The pocket sized soil laboratory developed by xSpectre is an advanced and cost-effective instrument for monitoring, reporting and verifying soil carbon content and fluxes.

## Local knowledge for solving global problems

Farmer livelihood and regenerative farming improving soil health while capturing atmospheric carbon dioxide go hand in hand. xSpectre's vision is that this win-win solution for farmers and climate (and thus society at large) requires soil information that is best supported through a combination of modern sensing technology, local knowledge and Artificial Intelligence.

<ul class="post-list">
{% for post in site.categories.vision %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>
