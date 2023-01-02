---
layout: page
title: Approach
categories: NABC
excerpt: "Developments in microcontrollers, ICT and miniaturization of spectral sensors have paved the way for innovations also in soil sensing. Grounded in the rapid progress, xSpectre has developed a handheld soil laboratory that easily, quickly and cheaply analyze soils and their properties, in-situ or in the kitchen."
tags:
  - Approach
  - research
  - policy
date: '2023-01-02 11:00'
modified: '2023-01-02 11:00'
comments: true
share: true
---

We have created a solution to easily, quickly and cheaply analyze soils and their properties with a hand-held spectrometer directly in the field, at home in the kitchen or in the lab. The translation into soil properties takes place via a cross platform app that connects the spectral signal with a database and that uses both AI and a patent-pending mathematical-geometric model. The translation requires that the relationship between spectral signal and soil properties be defined in advance. In December 2021, the [Open Soil Spectral Library (OSSL)](https://soilspectroscopy.org) was launched, which in addition to spectra also contains wet chemical analysis results. With the OSSL global coverage as a basis, it is possible to create regional a-priori models. With the help of external sensors connected to xSpectre's spectrometer+, users can create/improve their own local models with higher accuracies.

Our solution can deliver information, for advanced users also translated into maps and vehicle/equipment control files via satellite and drone, at a precision and cost that does not exist today. Our solution could also be a cornerstone in the transition to climate-smart agriculture and to verify soil carbon credits.

#### Value offer

xSpectre's scalable solution is basically Software as a Service (SaaS) subscriptions combined with an initial hardware cost. The hardware cost includes one or more spectrometers and various external sensors (for example for humidity, salinity, pH and NPK). Annual subscriptions give access to the online resources, including storage space for spectral signals, regional and local spectral libraries and predefined global and regional translation models. The modelling, analysis and reporting that is supported as SaaS depends on the subscription level. As an outset, xSpectre's business concept identifies three customer segments:

- regular users ("small"),
- precision farmers ("medium"), and
- advisors ("large").

While the initial hardware included with each segment varies, there is no limit for different subscribers to purchase additional spectrometers, external sensors or storage space for more spectral signals. The core difference between the customer segments lies in the offered SaaS  that can only be upgraded by changing to medium or large.  

The simplest subscription (regular or small) would include only the spectrometer (with no **+**), a smaller number of annual spectra (maybe 500) and with analysis restricted to existing, a-priori defined, translation models. The medium (precision farmer) level hardware offer also contains external sensors for field use and additives for spectral analysis also of liquids and gases (for example methane and carbon dioxide), and more storage and analysis capacity (maybe 2000 samples per annum). For the medium segment, AI interpolation from point measurements to map data is offered using AI, elevation data and humidity index from satellite radar images. The most advanced level (advisor or large) would include 3 fully equipped spectrometers (and maybe 6000 spectra per annum), external Ion Selective Electrodes for lab-quality analysis of key soil constituents (pH, NO<sub>3</sub><sup>-</sup>, NH<sub>4</sub><sup>+</sup>, K<sup>+</sup>, Ca<sup>2+</sup>) and support for connecting models to drone and satellite images and thus map images of soil properties and generate control files for precision agriculture produced via AI and an expanded image and map base.

#### Partners and value chain

In the short term, the value chain consists of:

- spectrometer with external sensors,
- cross platform app,
- modeling and analysis tools,
- Subscription-based internet service (SaaS),
- marketing and sales, and
- basic user support.

In the longer term, additional services need to be developed:

- online training modules,
- support for model development,
- publication of 3rd party models,
- subscription and payment schemes for 3rd party models, and
- link to external resources (advertised or subscribed).

We collaborate with an electronics expert regarding the design and development of microcontrollers and printed circuit boards (PCBs) and we have leased out the manufacturing of the PCB. We manufacture the hardware shells ourselves using 3D printing. Most external sensors are purchased as "plug-and-play" ready components, but some require manual soldering for adding the connection plug. The existing hardware production chain can be used for producing limited test-series of tens of spectrometers+. Stepping up production to hundreds would require leasing out the 3D printing of shells, the soldering of external probes plugs and assembly. Turning to a full production chain (more than 1000 spectrometers) would require setting up an international production chain.

The mobile app as well as model and analysis tools are developed internally, with some consultant support. Databases and connection to mobile and further to the server side are developed internally; the development within cloud-based services and apps (e.g. Google Cloud Run) towards more efficient and flexible solutions requires external support. As the principal app and server side components are already defined and functional, the additional resource required for shifting to Google Cloud Run are, however, limited.

The in-house development and support of the app and backend cloud-based services can only support the adopter category "Innovators", willing to accept a lower user-friendliness and somewhat flawed services. To bring the Information and Communications Technology (ICT) solution to a level where it could be used in niche application ("early adopters"), including dedicated climate smart farmers/advisors or higher education, requires further, but still minor, improvements of the cross platform app and the server solution. To reach larger markets (crossing the chasm to early and late majorities) is in a different ballpark.

#### Minimum Viable Product (MVP)

There is a mismatch between the simplest (minimum) product (spectrometer without external probes) and the initial customer segments of innovators (precision farmers or medium). The adopter category innovators, and probably also a large fraction of the early adopters, are looking for a system that can be verified - that is a spectroemter+ with external probes for both field and laboratory. Our market research shows that the farmers and advisors that have tested, or are knowledgeable about, NIR technology for soil sensing, want more proof of accuracies (see the LEAD trainee report linked at the bottom).

#### Unique Selling Point (USP)

To create our Unique Selling Point (USP) and reach the market can thus either be via extensive in-house tests of the accuracies and then launch a spectrometer without external probes (no **+**), or to launch a test-series of subsidised, or free, spectrometer+ for innovators that are willing to collect data and give feedback on the development of both the hardware and the software solutions.

The latter approach is more in line with our USP vision of establishing a user community of citizen scientists. It is also not per-se more expensive compared to in-house development. To approach the approximately 20 innovators that we have identified, of which half are composed of Swedish and other European carbon farming advisors and the other half European research organisations dealing with soil characterization, would cost approximately USD 25,000 in hardware (including external probes).

#### Revenue stream

The production cost per spectrometer is currently around USD 400, excluding any external probes. This cost can drop to half already at a volume in the hundreds, and even further with an international production chain and new microcontrollers and sensors. The margin on sales should be possible to set at 100% at the two latter production volumes. Sales and marketing costs (Customer Acquisition Cost, CAC), however, would erode this margin over the first years.

Costs for subscriptions and services for existing solutions at any point in time and for each customer segment should also be possible to be set with margins of 100% - but we expect that the development costs over the first years will consume also these margins.

We thus believe that the revenue stream could start generate a profit when we reach a thousand users and can establish an international production chain. This will take 2 to 4 years dependent on the investments we can raise.

#### Challenges for reaching the majority market

The biggest technical challenges for reaching the market are to develop the user-friendliness and verify the reliability and accuracy of NIR sensing technology. As outlined above, we have reduced costs and streamlined the hardware production by developing our own circuit boards but need to develop this further, partly to be able to replace the spectral sensor with newer, better and cheaper alternatives, partly to include a touch screen and internal data storage for improved user-friendliness. The estimated costs for technical development allowing us to reach out to hundreds of early adopters we estimate to be in the range of 150,000 to 200,000 USD. this includes freely distributing 20 to 30 spectrometer+ to innovators willing to contribute in the development of both the hardware and the software.

In order to reach the customers, the entire chain from measurement, data transfer, storage, analysis, information extraction and reporting as both graphics and text needs to work seamless; while all parts are operational and the system works smoothly "on a sunny day" the interconnection needs to be improved (also for rainy days). We estimate the cost for software and platform development for reaching early adopters to also be in the range of 150,000 to 200,000 USD.

The business side needs to be defined and priced in order to offer solutions customized for each category of clients. We estimate that launching a viable product for each of our envisioned customer segments would cost 50,000 to 75,000 USD. We further estimate the Customer Acquisition Cost (CAC) for the first hundred early adopters to be in the range 250 to 500 USD per user to then decline to perhaps 50 to 100 USD.

Reaching beyond the innovators and early adopters, and entering the majority markets, will demand stepping up the user-friendliness further, launching training modules and more comprehensive support, and then also adding solutions for allowing 3rd party model publication and add-on subscription for those. The cost for closing the chasm to the larger market sections we estimate to be at least double the costs for reaching the early adopters (350,000 to 500,000 USD) - but with substantial lower costs for CAC.
