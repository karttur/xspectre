---
layout: page
title: Solution
excerpt: "Harvesting local knowledge for improving soil knowledge and supporting soil health."
search_omit: true
---

We have created a solution to easily, quickly and cheaply analyze soils and their properties with a hand-held spectrometer directly in the field or at home in the kitchen. The translation of spectral signals into soil properties takes place via a mobile app that connects with a database and then uses both AI and a patent-pending mathematical-geometric model for predicting soil properties. The translation requires that the relationship between spectral signals and soil properties be defined in advance.

Our solution can deliver information, for advanced users also translated into maps and vehicle control files utilizing satellite and drone imagery, at a precision and cost that does not exist today.

The economic incentive for using our solution is not primarily increased yield, but rather reduced costs and improved soil health. Our solution is a cornerstone for  precision agriculture and regeneration of soil health. In addition to supporting increased efficiency and profit margins, the solution is a tool for monitoring, reporting and verifying (MRV) soil carbon and soil health - a prerequisite for accessing the growing market of soil carbon credits.

#### The spectrometer+

At its core xSpectre innovative tool is a handheld light sensor, or spectrometer. Measuring and analysis spectral signals for revealing the molecular composition of different substances is commonly used in astronomy (to reveal the compositions of stars and now also the atmosphere of planets in other solar systems), industrial production (to adjust the processing in real time in for instance pharmaceutical and food processing industries) and in science (including for soil characterisation).

The spectrometer developed by xSpectre also contains external ports that allows additional sensors to be added, thus the **+** in spectrometer+. External sensors include stainless steel probes for field sampling (for example for humidity, salinity, pH and NPK) and laboratory Ion Selective Electrodes (for example for pH, NO<sub>3</sub><sup>-</sup>, NH<sub>4</sub><sup>+</sup>, K<sup>+</sup>, Ca<sup>2+</sup>). The external probes convert the spectrometer+ from a light sensor to a _swiss army knife for soil sensing_.

#### Spectral libraries and the model tool

In December 2021, the [Open Soil Spectral Library (OSSL)](https://soilspectroscopy.org) was launched, which in addition to spectra also contains wet chemical analysis results. OSSL has a global coverage and is expanding rapidly. With OSSL as a basis it is possible to create _regional_ a-priori models for the translation of spectral signals to soil properties.

With the help of the external sensors connected to xSpectre's spectrometer+, the user can create or improve their own _local_ models with higher precision. The formulation of models from spectral libraries is facilitated by the patent-pending mathematical-geometric modelling framework. The framework by default uses AI for supporting the formulation of translation models, but does so confining AI to logical domains that are intelligible to the user (farmer or ag-tech specialists). Also the results of a spectral analysis are presented using the same, interpretable, graphical interface, along with ordinary numerals.

#### The cross platform app

The cross platform app acts as the graphical interface and is used for operating the spectrometer and transmitting the results of a spectral analysis to the user. Apart from being used as an Information and Communication Technology (ICT) center, the app is also used for edge (or fog) computing, and for recording positions (e.g. using builtin GPS) when sensing in-situ data in the field.

#### The user community platform

Perhaps the most Unique Selling Point (USP) of our solution is the openness and user community driven development of local and regional translation models. The graphical interface of the mathematical-geometric modeling framework helps domain experts interpret and understand the results of the spectral sensing. It also allows them to refine translation models and improve predictions based on local knowledge. We regard our customers as citizen scientists.

#### Summary

In summary our solution is constructed on four pillars:

- a cheap and robust handheld spectrometer with add-on sensors (**+**) for various soil properties,
- a cross platform mobile app for operating the spectromter+ and that works as a communication center with the online storage and analysis,
- an intelligible translator, that operate with or without AI, for converting spectral signals to soil properties and report results in an intuitive graphical interface, and
- a user community for harvesting local knowledge and improving local and regional predictions of soil properties.

#### Appendices

<ul class="post-list">
{% for post in site.categories.technology %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>
