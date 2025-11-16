# DigitalSEE Project Documentation

## Overview

This project is part of the [**DigitalSEE (Digital South-Eastern Europe)**](https://digitalsee.epistone.net/) initiative, which focuses on cataloging and digitizing cultural heritage sources from the South-Eastern European region. The project utilizes XML-based metadata to organize information about archaeological sites, objects, and cultural artifacts extracted from various historical and contemporary sources.

## Project Structure

The project contains structured XML metadata that captures comprehensive information about:
- Archaeological sites and objects
- Geographic locations and coordinates
- Historical dating and provenance information
- Source citations and bibliographic references
- Contemporary and historical names and descriptions

## DigitalSEE Categories and Source Types

The following table illustrates the DigitalSEE categories applied in this project to different source materials:

| **Source Type** | **DigitalSEE Category** | **Description** | **Examples** |
|---|---|---|---|
| Woodcuts | Ancient Monuments | Historical prints depicting structures and artifacts | 16th-18th century prints of fortifications |
| Old Printed Books | Manuscripts / Publications | Travelogues, geographic descriptions, and historical accounts | 17th-19th century travel narratives |
| Etchings | Ancient Monuments / Inscriptions | Detailed artistic renderings of sites and inscribed objects | Archaeological site illustrations |
| Maps | Communications / Geographic Records | Historical maps showing roads, settlements, and geographic features | Period maps of trade routes and territories |
| Manuscripts | Manuscripts | Original handwritten documents and records | Archival manuscripts and correspondence |
| Inscriptions | Inscriptions | Epigraphic records and carved/written text | Ancient stone inscriptions and tablets |
| Fortification Records | Fortifications | Documentation of defensive structures and military sites | Castle and fortress descriptions |
| Religious Documentation | Cult Sites | Records of temples, churches, and sacred sites | Religious site descriptions and records |
| Photographs | Archaeological Documentation | Historical and contemporary photographs of artifacts | Early archaeological expedition photos |

## Key Metadata Fields

The project employs the following main XML metadata fields:

### Basic Information
- **author**: Team member responsible for the entry
- **nameSource**: Original name according to source material
- **nameContemporary**: Modern/contemporary name of the site or object
- **description**: Detailed description including form and dimensions

### Geographic Data
- **latitude/longitude**: Geographic coordinates
- **geonamesLink**: Reference to Geonames database
- **pleiadesLink**: Reference to Pleiades gazetteer
- **currentLocation**: Current museum or storage location

### Temporal Information
- **date**: Dating according to source material
- **datingCriteria**: Criteria used for dating
- **age**: Historical period (Prehistory, Iron Age, Roman Age, Late Antiquity, Middle Ages, Ottoman Period)
- **ageContemporary**: Modern historical period classification

### Source Documentation
- **sourceInformation**: Bibliographic and archival information
- **originalLanguage**: Original language of the source
- **publicationLanguage**: Language of the version consulted
- **authorPublication**: Author of the source material
- **copyrightStoragePlace**: Copyright and storage location

### Categorization
- **desc**: Primary category (Inscriptions, Manuscripts, Cult Sites, Communications, Fortifications, Ancient Monuments, Other)
- **list**: Subcategory within the primary category
- **keyword**: Keywords for file organization

### Provenance Tracking
- **provenanceOrigin**: Original location information
- **provenanceObservedIn**: Subsequent locations where object was observed
- **provenanceOtherLocations**: Additional locations in object history
- **geographicCoordinatesObserved/Current**: Location coordinates at different time periods

## Additional Resources

- **VIAF**: Virtual International Authority File reference for authors
- **IIIF**: International Image Interoperability Framework for digital images
- **Annotation**: Team commentary on entries

## Notes

- Fields marked with * in the "Required" column indicate conditional requirements based on data availability
- Fields marked with ** indicate requirements when applicable location information is known
- All dates follow standardized historical period classifications
- Geographic coordinates are recorded in decimal degree format (latitude/longitude)
