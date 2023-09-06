---
layout: default
title: Mirador
nav_order: 4
---
# Mirador: What is it?

Mirador is a IIIF viewer that enables you to compare and annotate images from any digital collection that supports IIIF.

The "official" Mirador how-to site can be found here: [https://iiif.io/explainers/using_iiif_resources/#mirador](https://iiif.io/explainers/using_iiif_resources/#mirador)

To try Mirador viewer, you will need the address of a "Mirador viewer instance" - that means somewhere that someone is hosting the viewer itself. 

- UWM Libraries Mirador viewer - [https://liblamp.uwm.edu/IIIF/mirador3.html](https://liblamp.uwm.edu/IIIF/mirador3.html)
- Next, you'll need to find the "manifest URL" for images you'd like to compare. In the UWM Digital Collections, the manifest URL is identified in the metadata record:
  
  <img src="/assets/images/iiif-manifest-uwm.png" width="200">


To view IIIF resources in the Mirador viewer, you need to construct the URL of the IIIF Presentation API manifest. The following is the formula to generate the manifest URL of resources in the libraries' digital collections. 

https://[CONTENTdm Server Address]/iiif/info/[Digital Collection ID]/[Item ID]/manifest.json
CONTENTdm Server Address: cdm17272.contentdm.oclc.org or collections.lib.uwm.edu
Digital Collection ID
Item ID
example: 
https://collections.lib.uwm.edu/digital/collection/mke-polonia/id/33962
https://cdm17272.contentdm.oclc.org/iiif/info/mke-polonia/33962/manifest.json
Note: The IIIF Manifest URL is linked in the digital collection. Access the object's metadata to copy/paste the URL into the Mirador Viewer. 

Follow the video tutorials on the next tab to explore the Mirador viewer. 
