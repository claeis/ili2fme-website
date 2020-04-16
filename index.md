---
title: ili2fme - INTERLIS-plugin for FME
permalink: /
---

## Features

- reads INTERLIS 2 transfer files (2.2+2.3)
- writes INTERLIS 2 transfer files (2.2+2.3)
- reads INTERLIS 1 transfer files
- writes INTERLIS 1 transfer files

## Use cases

One user reported, that ili2fme successfully converted 1 GB INTERLIS 1 data into 4.5 GB INTERLIS 2 data.

## Status

ili2fme is in stable state.

## License

ili2fme is licensed under the LGPL (Lesser GNU Public License).

## System Requirements

For the current version of ili2fme, you will need a JRE (Java Runtime Environment) installed on your system, version 1.6.0 or later.
The JRE (Java Runtime Environment) can be downloaded for free from the Website http://www.java.com/.

## Installing ili2fme

Please note that Safe Software
distributes the ili2fme format with FME as a convenience.

The [Licensing options](https://www.safe.com/pricing/fme-desktop/) for 
this format begin with FME Desktop Professional Edition.

The methods below are only required, if you want to override the version of ili2fme 
that is distributed by Safe Software.

### by using the MSI file
just double-click the msi file (This will install ili2fme into your current FME software folder)

### by using the ZIP file

To install ili2fme, choose a directory and extract the distribution file there.
Copy the files and subdirectories of "${ili2fme}/FME Suite" to your FME directory.

To use ili2fme with the FME Universal Viewer, FME requires you to set an
environment variable: FME_VIEWER_THREADING=SINGLE.

You may add your commonly used private Interlis models to the directory "${FME}/plugins/interlis2/ilimodels".

## Running ili2fme

ili2fme is called by FME, if you select "Swiss INTERLIS (ili2fme)" as file format.

INTERLIS 2 is read/written if you select xtf or xml as file extension.
INTERLIS 1 is read/written if you select itf as file extension (but you have to select "Swiss INTERLIS (ili2fme)" in FME).
You should read .ili files (INTERLIS 1 or 2) to import feature types into the workbench.

## Limitations

- custom line forms
- XTF line attributes


## Price

ili2fme is free.

## Support

- Ask other users [here](http://gis.stackexchange.com/)
- Get a support contract from a consultant.

## Tutorial

- [Kleines Beispiel INTERLIS 1 nach 2](http://www.youtube.com/watch?v=o-_5NhnXkcE)
- [Kleines Beispiel INTERLIS nach shp](http://www.youtube.com/watch?v=Jkj6kWQKnSw)
- [Kleines Beispiel shp nach INTERLIS](http://www.youtube.com/watch?v=he-UID34BB0)

