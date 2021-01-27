---
toc: true
layout: post
description: An easy guide in using the CSW endpoint on geo.ca
categories: [markdown]
title: An easy guide in using the CSW endpoint on geo.ca
---
# Geo.ca CSW How-to

## The CSW and HNAP standard

The Catalogue Service for the Web (CSW) is an Open Geospatial Consortium (OGC) standard used to publish and search for metadata, services and related information objects. On geo.ca, the metadata standard is structured according to the North American Profile of ISO 19115:2003 (NAP). 

Due to the flexible nature of the NAP standard, the Government of Canada has created a Harmonized North American Profile (HNAP) which takes the elements provided in the NAP but adjusts the cardinalities of the elements. In addition, specific Government of Canada business rules have been added to the HNAP profile in order to control the values allowed in elements. For example, keywords used in metadata records must be supplied from the [Government of Canada Core Subject Thesaurus](https://canada.multites.net/cst/def.asp?lang=en&n=E5807AB0-1).

## Geo.ca CSW How-to

The geo.ca uses the OGC Certified Compliant CSW implementation [pycsw](https://pycsw.org/). 
