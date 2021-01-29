---
toc: true
layout: post
description: An easy guide in using the CSW endpoint
categories: [markdown, csw, pycsw, ogc, hnap]
title: An easy guide in using the CSW endpoint
---
# How to use the geo.ca CSW endpoint

## The CSW and HNAP standard

Catalogue Service for the Web (CSW) is an Open Geospatial Consortium (OGC) standard used to publish and search for metadata, services and related information objects. On geo.ca, the metadata standard is structured according to the North American Profile of ISO 19115:2003 (NAP). 

However, due to the flexible nature of the NAP standard, the Government of Canada has created a Harmonized North American Profile (HNAP) which takes the elements provided in the NAP but adjusts the cardinalities of the elements and specific business rules to control the values allowed in certain elements. For example, keywords used in metadata records must be recorded in the [Government of Canada Core Subject Thesaurus](https://canada.multites.net/cst/def.asp?lang=en&n=E5807AB0-1).

## Geo.ca CSW How-to

The geo.ca uses the OGC Certified Compliant CSW implementation [pycsw](https://pycsw.org/). At the time of this writing the version of pycsw is 2.7.0
