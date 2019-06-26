# XML examples

## Overview

This folder includes examples of XML/GML responses to illustrate how the
OpenAPI fragments used to define the requirements for the
Core requirements class are expressed in XML using the
[OGC API Features Core XML Schema](https://raw.githubusercontent.com/opengeospatial/WFS_FES/master/core/xml/core.xsd).

## Responses to path `/`

* A [landing page](LandingPage.xml).

## Responses to path `/conformance`

* A [conformance declaration](ConformsTo.xml). This server conforms to the recommended requirements classes, plus the GML Simple Features Profile, Level 0.

## Responses to path `/collections`

* A [feature collections resource](Collections.xml). This service offers three feature collections (airport facilities, roads, inland water areas).

## Responses to path `/collections/{collectionId}`

* A [feature collection resource](Collection.xml). Only the information for the selected feature collection (roads) is included in the response.

## Responses to path `/collections/{collectionId}/items`

* A [features resource](FeatureCollection.xml). This response contains 2 features of the airport facilities collection and has a link to the next features.