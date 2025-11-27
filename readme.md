# LatinNow Project data

## Description

This repo is comprised of two principal datasets produced by the ERC-funded [LatinNow project][1] (2017-2023) and used as the source material for the [open access volumes][2] published by the LatinNow team.

### 1. Inscribed Objects (LatinNowDB)
The first dataset is a relational database of inscribed epigraphic objects. It is comprised of 26 tables. These have been exported as tab-delimited file encoded in the UTF-8 character set, and may be found in the subdirectory titled `LatinNowDB tables`. (N.B., one table (latnow_source) has been compressed into a ZIP file to circumvent GitHub's 100 MB file size limit.) An SQL DDL file in MySQL format (LatinNowDB.sql) has been provided to allow recreation of the database. An entity relationship diagram (LatinNowDB Schema.pdf) representing the database schema has also been provided to facilitate an understanding of the database structure. Please report any errors to [Scott Vanderbilt](https://github.com/sarcanon).

If you would like to work with LatinNow's inscribed objects data without recreating the entire database, a complete set of all 129,502 records may be accessed by importing the table titled `latnow_inscrobj.txt` into a spreadsheet application such as Microsoft Excel or LibreOffice Calc. Please note that this top-level table contains only a small subset of all of the various types of metadata, geographical associations, bibliographical references, and texts that are available in the full database. But it should be sufficient to provide a taster of the dataset, and perhaps be adequate for some limited research purposes.

### 2. LatinNow GIS
The [LatinNow GIS](https://gis.latinnow.eu/) is made available here as a set of .geojson files, and may be found in the `GIS Layers` subdirectory. A readme file particular to these files may also be found in this directory.

## Authors

Alex Mullen, Scott Vanderbilt, Anna Willi, Pieter Houten, Simona Stoyanova (all University of Nottingham at the time of the data creation).

## Version History

* 0.1
    * Initial Release

## License

The data released in this repository is licensed under the Creative Commons Attribute License (CC-BY-4.0) - https://creativecommons.org/licenses/by/4.0/deed.en

## Acknowledgments

EAGLE Europeana Project, Francesca Cotugno, María José Estarán Tolosa, Javier Herrera Rando, Joaquín Gorrochategui, Frank Grieshaber, Pietro Liuzzo, Michael Loy, Noemí Monunill, Silvia Orlandi, María Paz de Hoz, Nathalie Prévôt, Coline Ruiz Darasse, Corinna Salomon, José Ángel Zamora.

[1]:https://latinnow.eu
[2]:https://latinnow.eu/publications-and-online-resources/
