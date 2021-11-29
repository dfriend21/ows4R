
# **[ows4R 0.2](https://github.com/eblondel/ows4R/issues?milestone=2)**

## **_0.2_** | [![CRAN_Status_Badge](https://img.shields.io/badge/CRAN-unavailable-red.svg)](https://cran.r-project.org/package=ows4R)

**Corrections**

- [#45](https://github.com/eblondel/ows4R/issues/45) WFS featureType getDescription fails as prettified when missing properties
- [#49](https://github.com/eblondel/ows4R/issues/49) OWS Capabilities components not correctly parsed when ref namespace is from service (eg. wms)

**Enhancements**

- [#41](https://github.com/eblondel/ows4R/issues/41) Add control on hasGeometry in case geom excluded from propertyNames
- [#42](https://github.com/eblondel/ows4R/issues/42) Support other WFS output formats than GML
- [#44](https://github.com/eblondel/ows4R/issues/44) Warning raised when reading WFS capabilities / proj4 with +init

**New features**

- [#10](https://github.com/eblondel/ows4R/issues/10) Support WPS client version 1.0.0
- [#15](https://github.com/eblondel/ows4R/issues/15) Generalize auth to clients/requests
- [#43](https://github.com/eblondel/ows4R/issues/43) Support WMS GetCapabilities, GetFeatureInfo requests


# **[ows4R 0.1](https://github.com/eblondel/ows4R/issues?milestone=1)**

## **_0.1-5_** | [![CRAN_Status_Badge](https://img.shields.io/badge/CRAN-published-blue.svg)](https://cran.r-project.org/package=ows4R)

**Enhancements**

* [#34](https://github.com/eblondel/ows4R/issues/34) WFS – Support coercing of date/datetime fields
* [#35](https://github.com/eblondel/ows4R/issues/35) WFS – Improve support of WFS 2.0
* [#36](https://github.com/eblondel/ows4R/issues/36) WFS – findFeatureTypeByName fixes
* [#37](https://github.com/eblondel/ows4R/issues/37) WFS – Support for xsd:float primitive type
* [#38](https://github.com/eblondel/ows4R/issues/38) WFS – add pretty option for feature type description
* [#39](https://github.com/eblondel/ows4R/issues/39) CSW – fix getRecordById for feature catalogue (ISO 19110) parsing

## **_0.1-4_** | [![CRAN_Status_Badge](https://img.shields.io/badge/CRAN-published-blue.svg)](https://cran.r-project.org/package=ows4R)

**Corrections**

*[#32](https://github.com/eblondel/ows4R/issues/32) Regression with WFS getfeatures - issue when setting CQL_filter

## **_0.1-3_** | [![CRAN_Status_Badge](https://img.shields.io/badge/CRAN-published-blue.svg)](https://cran.r-project.org/package=ows4R)

**Corrections**

* [#14](https://github.com/eblondel/ows4R/issues/14) debug parameter shouldn't be passed to OWS requests
* [#30](https://github.com/eblondel/ows4R/issues/30) WFS - Handle Resulttype Hits get features response

**Enhancements**

_No enhancements_

**New Features**

* [#16](https://github.com/eblondel/ows4R/issues/26) Add support for Bearer (token) authentication
* [#28](https://github.com/eblondel/ows4R/issues/28) Support geometa record validate/inspire options in CSW-T

## **_0.1-2_** | [![CRAN_Status_Badge](https://img.shields.io/badge/CRAN-published-blue.svg)](https://cran.r-project.org/package=ows4R)

**Corrections**

* [#12](https://github.com/eblondel/ows4R/issues/12) Issue with maxRecords parameter scope in getRecords 
* [#13](https://github.com/eblondel/ows4R/issues/13) Bad XML encoding of OGC BBOX Expression
* [#19](https://github.com/eblondel/ows4R/issues/19) mapping FeatureType datatypes fails with case sensitive datatypes

**Enhancements**

* [#18](https://github.com/eblondel/ows4R/issues/18) Issue with missing EPSG:404000 code not found in init file
* [#20](https://github.com/eblondel/ows4R/issues/20) WFS FeatureTypeElement support xs/xsd types & elements restrictions
* [#24](https://github.com/eblondel/ows4R/issues/24) improve getFeatureTypes
* [#21](https://github.com/eblondel/ows4R/issues/21) Test insertion / update of multi-lingual metadata records

**New Features**

* [#16](https://github.com/eblondel/ows4R/issues/16) add function to reload client capabilities

## **_0.1-1_** | [![CRAN_Status_Badge](https://img.shields.io/badge/CRAN-archived-brown.svg)](https://cran.r-project.org/src/contrib/Archive/ows4R/ows4R_0.1-1.tar.gz)

**Corrections**

* [#12](https://github.com/eblondel/ows4R/issues/12) Issue with maxRecords parameter scope in getRecords
* [#13](https://github.com/eblondel/ows4R/issues/13) Bad XML encoding of OGC BBOX Expression
* [#19](https://github.com/eblondel/ows4R/issues/19) mapping FeatureType datatypes fails with case sensitive datatypes (support to [#17](https://github.com/eblondel/ows4R/issues/17))

**Enhancements**

* [#16](https://github.com/eblondel/ows4R/issues/16) Add function to reload client capabilities
* [#18](https://github.com/eblondel/ows4R/issues/18) Handle specific CRS wildcard EPSG:404000
* [#20](https://github.com/eblondel/ows4R/issues/20) WFS FeatureTypeElement support xs/xsd types & elements restrictions (support to [#17](https://github.com/eblondel/ows4R/issues/17))
* [#21](https://github.com/eblondel/ows4R/issues/21) Test insertion / update of multi-lingual metadata records


**New Features**

_No new features at now_

## **_0.1-0_** | [![CRAN_Status_Badge](https://img.shields.io/badge/CRAN-archived-brown.svg)](https://cran.r-project.org/src/contrib/Archive/ows4R/ows4R_0.1-0.tar.gz)

**New features**
  
* [#8](https://github.com/eblondel/ows4R/issues/8) Allow authentication on OWS Requests
* [#7](https://github.com/eblondel/ows4R/issues/7) Prepare 1st release on CRAN
* [#6](https://github.com/eblondel/ows4R/issues/6) Set up travis-ci build for integration tests / quality assurance
* [#5](https://github.com/eblondel/ows4R/issues/5) OGC Filter Encoding + XML representation
* [#4](https://github.com/eblondel/ows4R/issues/4) OWS (Common Web-Service) OGC - OWS
* [#3](https://github.com/eblondel/ows4R/issues/3) CSW Client, versions ``2.0.2`` (including ``Transaction`` and ``Harvest``), partial support for ``3.0``
* [#2](https://github.com/eblondel/ows4R/issues/2) WFS Client, versions ``1.0.0``, ``1.1.0``, ``2.0.0`` for main operations (``GetCapabilities``, ``DescribeFeatureType``, ``GetFeature``
* [#1](https://github.com/eblondel/ows4R/issues/1) Set-up package structure
