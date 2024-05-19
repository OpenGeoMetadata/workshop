# Medley of Metadata Workflows

This repository contains set of Jupyter Notebooks for batch metadata processes.

## 01_CSV-2-JSON

* CSV template for OGM Aardvark metadata
* Jupyter Notebook that transforms the CSV into OGM Aardvark JSONs


## 02_JSON-2-CSV

* directory of sample OGM Aardvark JSONs, taken from the OpenGeoMetadata shared repositories.
* Jupyter Notebook that transforms the JSONs into a CSV

## 03_harvest-DCAT

* CSV listing a few ArcGIS Hubs, including each site's DCAT JSON API and default metadata values
* Jupyter Notebook that harvests metadata from the ArcGIS Hubs and writes a CSV

## 04_clean-validate

* CSV of sample OGM Aardvark metadata that has missing or incorrect values
* Jupyter Notebook scans the metadata, fixes it, and produces a log of actions taken


## aardvark-profile

* aardvark.csv: Documentation of the OGM Aardvark profile
* referenceURIs.csv: Keys and values of the types of references specified in the OGM Aardvark profile and viewable with GeoBlacklight
