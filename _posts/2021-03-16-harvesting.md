---
toc: true
layout: post
description: FGP/CGP Harvesting and Data Integration
categories: [csw, pygeoapi, ogc, api]
title: Harvesting technologies used by the Federal Geospatial Platform
---
# Overview of Harvesting Technologies

## The OGC API standards

Geo.ca uses a suite of Open Geospatial Consortium (OGC) standards to make metadata accessible and interoperable. To this end, the legacy OGC standard, Catalogue Service for the Web or CSW, is the current mechanism to accomplish these goals. 

As a Strategic Partner of the OGC (through GeoConnections - Natural Resources Canada), geo.ca supports the development of the OGC API - Records standard to make geospatial content access using modern web practices.

Below is a high-level architecture of metadata harvesting and publication workflow.

<iframe frameborder="0" style="width:100%;height:765px;" src="https://viewer.diagrams.net/?highlight=0000ff&edit=_blank&layers=1&nav=1&title=current_future_harvesting_workflow.drawio#Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fbo-lu%2Fgeoca_developers_page%2Fmaster%2Fassets%2Fcurrent_future_harvesting_workflow.drawio"></iframe>


## More information

For more information on the OGC API standards, please visit the [OGC API Roadmap](https://ogcapi.ogc.org/).

Geo.ca uses the OGC Certified Compliant CSW implementation [pycsw](https://pycsw.org/). At the time of this writing the version of pycsw is 2.7.0

Geo.ca uses the OGC Certified Compliant implementation [pygeoapi](https://pygeoapi.io/). At the time of this writing the version of pygeoapi is 0.10

