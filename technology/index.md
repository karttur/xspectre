---
layout: page
title: Technology
excerpt: "Spectrometer miniaturization and Artificial Intelligence (AI) drives a new era in spectral sensing."
search_omit: true
---

## NIR spectroscopy

Near Infra Red (NIR) spectroscopy is today's leading analysis method for rapid quality analysis of e.g. grain and roughage and to some extent also laboratory soil analyzes. With NIR spectroscopy it is possible to easily and quickly make both qualitative and quantitative measurements. The need for sample preparation is small and the measurement itself only takes a few seconds. While the method has entered laboratories, it is not widely spread as a field instrument, also because of the high prizes of the present generation of field-tuned spectrometers.

NIR includes electromagnetic radiation within the wavelengths ~700 and ~2500 nano meters (nm). For soil analysis a wide beam light source illuminates the sample and the reflected light is sensed, a method called diffuse NIR spectroscopy. The NIR radiation has a fairly low energy content, which means that no protective equipment or dilution is required. Another advantage of NIR is that the sample is not affected by the measurement and can thus be saved for more measurements.

The spectrum a NIR measurement generates is due to different molecules being able to absorb certain, and only certain, energy (wavelengths). The wavelengths absorbed depends on the kinds of molecules and bonds represented in a sample. Because the light is scattered when it is reflected and everything that is not absorbed thus does not reach the measuring probe (diffuse reflectance), it is not clear that the absorbance, i.e. the inverted reflectance, is directly proportional to a concentration. The absorption peaks therefore become unclear and overlapping and it is not possible to read a concentration directly from a spectrum.

Calibration is thus an important step in NIR analysis. The number of samples needed depends on what is being analyzed and the variation in the data material. Through statistical calculations revealing how analytical values ​​correlate with the reflectance spectrum, a model for predicting unknown samples can be created.

## Reference probing

As noted above, the interpretation of a spectral signal  requires a-priori knowledge on the typical spectral signal variation for the kind of sample that is analysed. Put differently, the translation from spectra to content requires a dedicated spectral library. The typical reference method for creating a spectral library for soils is to acquire both a spectra and perform a wet-chemistry laboratory analysis.

In december 2021 the [Open Soil Spectral Library, OSSL](https://soilspectroscopy.org/introducing-the-open-soil-spectral-library/) was launched. OSSL contains soil spectra and laboratory results from around the world and allows the construction of both global and regional translation models from spectra to various soil properties. But not all the world's geographical regions are covered in OSSL. And as soil conditions can vary quite a lot within short distances, it is a great advantage to use local data for creating the translation models.

xSpectre's spectrometer+ is equipped with external ports that allows direct sensing of key soil properties. Hence the spectrometer+, preferably with OSSL as a foundation, can be used for creating local translation models without the need for costly wet-chemistry laboratory analysis. This translation is greatly facilitated by the patent pending mathematical-geometric modelling framework, even allowing individual farmers to develop there own farm adjusted models.

#### Field sensing with xSpectre's spectrometer+

For direct, in-situ field measurements xSpectre's spectrometer+ has a sturdy aviation (GX16) plug that can use direct sensing methods for:

- soil temperature,
- soil humidity,
- soil electric conductivity (EC),
- soil salinity,
- soil pH,
- soil Nitrogen (N), phosphorus (P) and potassium (K), or NPK

The temperature, humidity, EC and salinity probes have a high (scientific) precision while the pH and NPK sensors are more indicative and are better used for relative content within the same soil region. All sensors are built with stainless steel pins that can be pushed into the soil without any further tool requirements.

#### Laboratory sensing with xSpectre's spectrometer+

For laboratory soil sensing, xSpectre's spectrometer+ is equipped with a standard BNC connection for attaching Ion Selective Electrodes (ISEs). ISE is an analytical technique for determining the activity (concentration) of ions in aqueous solution by measuring relative electrical potential. The primary ions that can be monitored with xSpectre's spectrometmer+ include:

- H<sup>+</sup> (pH),
- NO<sub>3</sub><sup>-</sup>
- NH<sub>4</sub><sup>+</sup>,
- K<sup>+</sup>, and
- Ca<sup>2+</sup>.

## Spectral sensor minituarization

Over the past decade the developments of spectral sensors has closely reflected (!) the developments in computer chips; they have become smaller, cheaper and more efficient. xSpectre's spectrometers, that typically cover the visible (VIS, 400-700 nm) and short wave NIR (700-1100 nm) wavelengths, are built using miniature spectral sensors from [Hamamatsu](https://www.hamamatsu.com/eu/en/product/optical-sensors/spectrometers/mini-spectrometer/selection-guide.html) and [AMS](https://ams.com/en/spectral-sensing). New technological developments (summarized in the article [Miniaturization of optical spectrometers, by Yang et al](https://www.science.org/doi/full/10.1126/science.abe0722?casa_token=9AQF6q4SVNgAAAAA%3Adz8G738nIV5hEWzBrZhHcYK5S6dB7uuTrCljRFBIgYtIaRBLbwbUSL79IiiXEEsxVucuMy-_MmrzZhU) and published in the journal Science 2021) is paving the way for miniaturized sensors also at longer wavelength. At present (January 2023), xSpectre is designing a spectrometer for the spectral regions 1350-2150 nm using Hamamatsu [singel cell MEMS-FPI spectrum sensor with a tunable filter](https://www.hamamatsu.com/eu/en/product/optical-sensors/spectrometers/mems-fpi-spectrum-sensor.html). (Note that to cover the full wavelength region demands three individual sensor of the present generation: 1350-1650nm, 1150-1850nm and 1750-2150nm).

The rapid developments in both sensors and microcontroller chips means that the design of an electronic product need to be flexible to accommodate the latest technology. xSpectre cooperates with a set of high quality companies for producing customized printed circuit boards (PCBs) fitted to the latest technology. The redesign usually also demands a remoulding of the spectrometer shell, internal spaces and external openings. This is solved by a purpose built program that generates 3D printing instructions that are then printed on an intra-mural, semi-professional 3D printer.

## Microcontrollers

The past decade has seen a very rapid development in microcontrollers, both the hardware and programming languages. This development has been led by [Arduino](https://www.arduino.cc) and the C/C++ dialect used by them. xSpectre's spectrometer+ uses a microcontroller from Nordic Semiconductor and the Arduino C/C++ dialect for internal control functions, with commands and results sent either via USB-cable of Bluetooth Low Energy (BLE).

## Progressive Web App (PWA)

The spectrometer+ is operated by a cross-platform application (app) eveloped with Progressive Web Apps (PWA). In a nutshell PWA is a web-page that appears as an app and can be run on any browser (mobile, tablet or computer).

Through the app the user controls the spectrometer+ and the device that hosts the app (i.e. the mobile) is used as an Information and Communication Technology (ICT) center that links the spectrometer+ to xSpectre's backend server solution.

New developments in cloud services (e.g. Google Could Run) are improving the deployment of many internet solutions, including PWA; the novel services make it easier to administer internet resources, support automation for seamless integration of different services and offer leaner hosting that is charged only when used. xSpectre is hence at present (January 2023) shifting from an older deployment system to using Google Cloud Run.

## Mathematical-geometric modelling framework

One of the innovative parts of xSpectre's solution is the patent pending mathematical-geometric modelling framework. The framework serves two main purposes; the first is to facilitate for domain experts (farmers and ag-tech specialists regarding soil conditions) to construct spectral translation models; the second to graphically present results of spectral scannings, including contents, quantities, correlations and uncertainties.

The Swedish patent application is being finalized as this is written. The international, PCT, application was published 26 July 2022: [SE2150075 - A method and software product for providing a geometric abundance index of a target feature for spectral data](https://patentscope.wipo.int/search/en/detail.jsf?docId=SE372948068&_fid=WO2022159025).

The mathematical-geometric modelling framework predicts soil properties on par with AI models, also because it is a hybrid-method that employs AI for calibration. The primary advantage with the mathematical-geometric modelling framework is thus not the statistical performance as such, but the vast improvement in intelligibility allowing non-AI experts to develop and interpret spectral models.

## Summary

In summary, the technological backbone of xSpectre's handheld spectrometer+ builds on the general developments within the information technology sector, in particular the following fields:

- diffuse NIR spectroscopy,
- minituarized spectral sensors,
- smart phone and microcontroller capacities,
- AI,
- 3D printing, and
- Cloud solutions for building applications.

In addition the mathematical-geometric modelling framework is a resource that we believe will allow us to turn our users into a community of citizen scientists.

## Appendices

<ul class="post-list">
{% for post in site.categories.technology %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>
