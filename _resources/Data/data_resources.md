---
title: "Data Resources"
layout: single
classes: wide
toc: true
toc_sticky: true
permalink: /resources/data-resources
author_profile: false
collection: resources
---
Below we have collated some core data sources and curated data lists which may be useful for research and innovators in decarbonisation research.

## Energy Sector

The following are data sources which are useful for energy research.

### Energy Networks

In the UK due to the Presumed Open Data Principle within the [data best practice guidence](https://www.ofgem.gov.uk/sites/default/files/2024-10/Track_Changes_Data_Best_Practice_Guidance_v301728394292260.pdf), many datasets have been made available on the network operators own data hubs. Some of the main hubs are listed below.
* **NESO [Data Portal](https://www.neso.energy/data-portal)** : The national system operator hub contains a large amount of data on balancing and ancillary including balancing mechanism units, forecasts, and costs. 
* **Elexon BSC [Insights Solutions](https://bmrs.elexon.co.uk/)** : Contains data on balancing mechanism and settlement. 
*	**National Gas [data portal](https://data.nationalgas.com/)**, the gas transmission operator for GB, contains data on gas flows, system status and forecasts.
* **Low Carbon Contracts Company** [data portal](https://dp.lowcarboncontracts.uk/dataset/) contains data relevant to the CfD markets. 

Each **Transmission Network Operator** has its own data portals of which there are three in the UK for different areas of the UK. These have data on the network infrastructure, fault levels, circuits etc.:
* **Scottish and Southern Electricity Networks– Transmission** - covers North of Scotland: [data portal](https://ssentransmission.opendatasoft.com/pages/homepage/)
* **Scottish Power Transmission** – covers South Scotland: [data portal](https://spenergynetworks.opendatasoft.com/pages/home/)
* **National Grid Electricity Transmission** – covers England and Wales

Each electricity **distribution network operator (DNO)** also has its own data hub focused on their own areas and also often includes telemetry data for demand and generation, data from innovation trials, and aggregated smart meter data:
* **National Grid Electricity Distribution** ([data portal](https://connecteddata.nationalgrid.co.uk/))
* **Scottish Power Electricity Networks** ([data portal](https://spenergynetworks.opendatasoft.com/pages/home/))
* **Scottish and Southern Electricity Networks** ([data portal](https://data.ssen.co.uk/))
* **Northern Powergrid** ([data portal](https://northernpowergrid.opendatasoft.com/pages/home/))
* **Electricity Northwest** ([data portal](https://www.enwl.co.uk/future-energy/data-and-digitalisation/data-portal/))
* **UK Power networks** ([data portal](https://www.ukpowernetworks.co.uk/our-company/open-data-portal))

Each of the four Gas Distribution Network Operator also has data portal containing information like pipe infrastructure, demand data, and linepack:
* **Cadent Gas** ([data portal](https://cadentgas.opendatasoft.com/pages/welcome/))
* **Scottish Gas Networks** ([data portal](https://www.sgn.co.uk/open-data-sharing-portal))
* **Wales and West utilities** ([data page](https://www.wwutilities.co.uk/about-us/data-digitalisation/))
* **Northern Gas Networks** ([data portal](https://northerngasopendataportal.co.uk/))

### Curated Datasets
Some novel and valuable datasets are not available openly, and often are only available from innovation projects. Some of these are available on the energy companies portals, but finding specific data sets relevant to specific applications are not always available. There are several catalogues of data sets useful in energy, some are listed below:
* **Open Power Systems Data**, an open [data platform](https://open-power-system-data.org/) containing generation, demand and weather data.
* **Low Voltage Load Forecasting [data](https://low-voltage-loadforecasting.github.io/)**:  a curated list of time series data for use in load forecasting from household up to low voltage substation level.
* **IEEE PES Intelligence Systems Subcommittee** [open data sets]( https://site.ieee.org/pes-iss/data-sets/) aimed at research in power and energy areas, including data for EV’s, consumption, wind and weather etc.
* The **openmod** initiative shares a curated [list of energy data sets](https://wiki.openmod-initiative.org/wiki/Data) relevant for energy modelling.
* **[Open Energy Data Initiative](https://data.openei.org/)**, a repository of high-value energy research datasets aggregated from US Department of Energy’s programs and Offices.
* **Monash Time Series Forecasting [Repository](https://forecastingdata.org/)** curated datasets for time series forecast, including energy data.


### Synthetic Data
Some data is difficult to share in large amounts, in these cases synthetic data can be valuable to help provide insights in lieu of real data. Below are a few tools for generating synthetic data. 
* **[OpenSynth](https://lfenergy.org/projects/opensynth/)**, an LF Energy community for open sharing of synthetic energy data, includes Centre for Net Zero’s [Faraday]( https://www.centrefornetzero.org/technologies/faraday) tool for generation synthetic smart meter data.
* **Renewables.ninja** simulated PV and wind [generation data](https://data.open-power-system-data.org/ninja_pv_wind_profiles/2020-09-16)
* **When2Heat** simulated [heating profiles]( https://data.open-power-system-data.org/when2heat/2023-07-27) is open synthetic building heat pump data for 28 European countries. 

### Tools for data extraction
Collating and aggregating data from multiple sources can be time consuming especially if the data uses different standards and formats, and has different access options. Below will be an list of some tools to support these extraction efforts. 
* **[Weave](https://weave.energy/)** is a python tool from the Centre for AI and Climate and CEIMIA (Centre d’expertise internationale de Montréal pour l’avancement de l’intelligence artificielle) which helps to extract and join the aggregated half hourly smart meter data from various UK DNOs.

If you have relevant datasets you wish to add to the list please get in contact at advice@turing.ac.uk