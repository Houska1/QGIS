# About QGIS

[![Tests](https://github.com/qgis/QGIS/workflows/QGIS%20tests/badge.svg)](https://github.com/qgis/QGIS/actions?query=workflow%3A%22QGIS+tests%22)
[![Docker Status](https://img.shields.io/docker/automated/qgis/qgis.svg)](https://hub.docker.com/r/qgis/qgis/tags)
[![Build Status](https://dev.azure.com/qgis/QGIS/_apis/build/status/qgis.QGIS?branchName=master)](https://dev.azure.com/qgis/QGIS/_build/latest?definitionId=1&branchName=master)
![Windows cross build with MXE](https://github.com/qgis/QGIS/workflows/Windows%20cross%20build%20with%20MXE/badge.svg)

QGIS is a full-featured, user-friendly, free-and-open-source (FOSS) geographical 
information system (GIS) that runs on most Unix platforms, Windows, and MacOS.

Features include

**1. Flexible visualization and editing of geospatial data**
* Raster, vector, mesh layers in range of formats
* Local files as well as remote (webserver, database/PostGIS, tiled)
* Variety of rendering options and reprojection on the fly
* Numerical and visual digitizing and editing
* Temporal support
* 3D visualization

**2. Beautiful cartography**
* Fine control over symbology, labeling, legends and additional graphical elements for visually beautiful maps
* Saved map layouts to recreate maps of specified scale, extent, and style
* Atlases to generate range of maps with same layout
* Flexible output as image (raster), PDF, SVG; camera-ready or suitable for further customization 

**3. Advanced GIS analysis**
* Geospatial database engine that is as close to datasource- and format-independent as possible (joins, relations, forms, etc.)
* 150+ geoprocessing algorithms
* Graphical modeler
* Access to additional algorithms via GDAL, GRASS, SAGA

**4. Wide customization**
* Scripting via Python
* Rich ecosystem of plugins, data connectors, advanced analysis and charting tools, in-the-field data capture
* Python and C++ API for standalone applications

**5. Server**
* Serve up geospatial data as well as rendered, beautiful QGIS maps
* Industry-standard protocols (WMS, WFS, OGC) allow plug-n-play with any client GIS/visualization software
* Works with any web server software
* Fully customizable, Python scripting

## Under the hood

QGIS is developed using the [Qt toolkit](https://qt.io) and C++ since 2002.  It has a pleasing, easy to use graphical
user interface with multilingual support. It is maintained by an active developer team and supported by vibrant community of GIS professionals and enthusiasts as well as geospatial data publishers and endusers. Releases follow a time-based schedule, with a new release every four months, interim bug-fix releases monthly, and a stable long-term release (LTR) once a year.

QGIS is released under the GNU Public License (GPL) Version 2 or above.
Developing QGIS under this license means that you can (if you want to) inspect
and modify the source code and guarantees that you, our happy user will always
have access to a GIS program that is free of cost and can be freely
modified.

QGIS is part of the Open-Source Geospatial Foundation ([OSGeo](https://www.osgeo.org/)), offering a range of complementary open-source GIS software projects.

## Supported formats

Supported raster formats include GeoTIFF, GRASS, ArcInfo binary and ASCII grids, ERDAS Imagine SDTS, WMS, WCS, PostgreSQL/PostGIS, and [all other formats supported by GDAL](https://gdal.org/drivers/raster/index.html).

Supported vector formats include GeoPackage, ESRI Shapefiles, GRASS, SpatiaLite, PostgreSQL/PostGIS, MSSQL, Oracle, WFS, and [other OGR supported formats](http://www.gdal.org/ogr_formats.html).

Supported mesh formats include NetCDF, GRIB, 2DM, and [other MDAL supported formats](https://github.com/lutraconsulting/MDAL#supported-formats).

## Installing and using QGIS

(Fill this in)

Please follow the installation instructions carefully.
After extracting the distribution, please check the
[documentation](https://qgis.org/en/docs/index.html)

## Help us
Please submit bug reports using the [QGIS bug tracker](https://github.com/qgis/QGIS/issues/).

## Support
You can get support in the following ways:

 -  Using the QGIS community site at https://qgis.org
 -  Joining the [qgis-users mailing list](https://lists.osgeo.org/mailman/listinfo/qgis-user)
 -  Chatting with us real-time.
    Please wait around for a response to your question as many folks
    on the channel are doing other things and it may take a while for
    them to notice your question.
    The following paths all take you to the same chat room:
     - Using an IRC client and joining the [#qgis](http://webchat.freenode.net/?channels=#qgis) channel on irc.freenode.net.
     - Using a Matrix client and joining the [#qgis:matrix.org](http://matrix.to/#/#qgis:matrix.org) room.
     - Using [Gitter](https://gitter.im/qgis/QGIS?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) chat.
 - At the [GIS stackexchange](https://gis.stackexchange.com/) or [r/QGIS reddit](https://www.reddit.com/r/QGIS/), which are not maintained by the QGIS team, but where the QGIS and broader GIS community provides lots of advice.

## Contribute

QGIS is on GitHub at https://github.com/qgis/QGIS. If you wish to contribute
patches you can [fork the project](https://help.github.com/forking/), make your changes, commit to your
repository, and then [create a pull request](https://help.github.com/articles/creating-a-pull-request-from-a-fork/). The development team can then review your contribution and commit it upstream as appropriate.

If you commit a new feature, add [FEATURE] to your commit message AND give a clear description of the new feature. A webhook will automatically create an issue on the QGIS-Documentation repo to tell people to write documentation about it.

If you are not a developer, there are many other possibilities which do not require programming skills to help QGIS to evolve. Check our [project homepage for more information](http://qgis.org/en/site/getinvolved/index.html).

### Building from source

The [building guide](INSTALL.md) can be used to get started with building QGIS from source.
