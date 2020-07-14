# Life Cycle Assessment of Technical Building Services of Large Residential Building Stocks Using Semantic 3D City Models

This repository contains the visualisation of the studies result, presented and published at the
[3D GeoInfo 2020 conference](https://www.ucl.ac.uk/3dgeoinfo/),
in the [3D City Database Web-Map-Client (3D web client)](https://github.com/3dcitydb/3dcitydb-web-map/).
The here as example presented results refer to the specific primary energy demand [kWh/m²&middot;a]
for the use stage of all 115,306 residential buildings in Munich. Thus, all color-coded buildings are
residential buildings and all non-colored, non-residential buildings. The coloring is done using the color
scheme on the energy-related evaluation band of the German energy certificates, according to EnEV (see
following figure).

<p align="center">
  <img src="EvaluationBand.png" width="500" />
</p>

The results for the various scenarios can be selected in the toolbox on the top left. Here, for example, the results for the scenario *Status Quo* and *Scenario 1*  can be selected and shown (see following figures). The toolbox can also display the vegetation model and the results from the solar tool mentioned in the paper.

<p align="center">
<img src="PEDStatusQuo.png" width="800" />
</p>

<p align="center">
<img src="PEDSzenario1.png" width="800" />
</p>

## More information

The **3DCityDB-Web-Map-Client** is a web-based front-end of the 3DCityDB for high-performance 3D
visualization and interactive exploration of **arbitrarily large semantic 3D city models in CityGML**.
It utilizes the [Cesium Virtual Globe](http://cesiumjs.org/index.html) as its 3D geo-visualization engine
based on HTML5 and Web Graphics Library (WebGL) to provide hardware acceleration and cross-platform
functionalities like displaying 3D graphic contents on web browsers without the needs of additional
plugins.

[OGC CityGML](https://www.opengeospatial.org/standards/citygml) is an open data model and XML-based format
for the storage and exchange of semantic 3D city models. It is an application schema for the
[Geography Markup Language version 3.1.1 (GML3)](https://www.opengeospatial.org/standards/gml),
the extendible international standard for spatial data exchange issued by the Open Geospatial Consortium
(OGC) and the ISO TC211. The aim of the development of CityGML is to reach a common definition of the
basic entities, attributes, and relations of a 3D city model.

CityGML is an international OGC standard and can be used free of charge.
