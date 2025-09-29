---
layout: default  
title: Bovine_Cells  
parent: Cell Cultured Meat  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Bovine_Cells  
**Description**: Information on bovine tissue collected and the subsequent cell populations sorted using fluorescence activated cell sorting.  
**Classification**: RDF106  
**Author**: Alexandra Steele  
**Author Email**: steela2@mcmaster.ca  
**ICT Group**: Cell Cultured Meat  
**Schema package SAID**: EFVDZj-_8GEThJumshsAeNhyD5FfR1b5Xcvp7WAaFb74  

[Download Schema](Bovine_Cells_OCA_package.json)

[Download LinkML Schema](Bovine_LinkML/schema.json) ([yaml](Bovine_LinkML/schema.yaml); table view: [fields](https://github.com/ClimateSmartAgCollab/HUB-Harmonization/blob/main/library/schemas/Cell_cultured/Bovine_LinkML/schema_slots.tsv), [picklists](https://github.com/ClimateSmartAgCollab/HUB-Harmonization/blob/main/library/schemas/Cell_cultured/Bovine_LinkML/schema_enums.tsv))

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| number_of_cells | Number of Cells | Number of cells in the sorted population. |
| animal_ID | Animal Number | Animal species and number. |
| collection_date | Collection Date | Date tissue was collected on. |
| collection_site | Collection Location | Location tissue was collected from. |
| percentage | Percentage of Cells | What percentage the sorted population made up of the total cell number. |
| sort_date | Sort Date | Date FACS was performed |
| sorted_population | Sorted Population | Include positive and negative sorting markers. |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Bovine_Cells | Information on bovine tissue collected and the subsequent cell populations sorted using fluorescence activated cell sorting. |

## Selection lists

### English

#### collection_site entry codes

| Entry code | Label |
| --- | --- |
| HP | Highland Packers |
| Guelph | Guelph CMIT |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry | Format rule |
| --- | --- | --- | --- | --- | --- | --- |
| number_of_cells | false |  | Numeric | utf-8 | false |  |
| animal_ID | false |  | Numeric | utf-8 | true |  |
| collection_date | false |  | DateTime | utf-8 | true | ^\(\\d\{4\}\)\-\(0\[1\-9\]\|1\[0\-2\]\)\-\(0\[1\-9\]\|\[12\]\\d\|3\[01\]\)$ |
| collection_site | false |  | Text | utf-8 | true |  |
| percentage | false |  | Numeric | utf-8 | false |  |
| sort_date | false |  | DateTime | utf-8 | false | ^\(\\d\{4\}\)\-\(0\[1\-9\]\|1\[0\-2\]\)\-\(0\[1\-9\]\|\[12\]\\d\|3\[01\]\)$ |
| sorted_population | false |  | Text | utf-8 | false |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| number_of_cells | Number of Cells | Number of cells in the sorted population. | Not a list |
| animal_ID | Animal Number | Animal species and number. | Not a list |
| collection_date | Collection Date | Date tissue was collected on. | Not a list |
| collection_site | Collection Location | Location tissue was collected from. | Highland Packers, Guelph CMIT |
| percentage | Percentage of Cells | What percentage the sorted population made up of the total cell number. | Not a list |
| sort_date | Sort Date | Date FACS was performed | Not a list |
| sorted_population | Sorted Population | Include positive and negative sorting markers. | Not a list |

## Schema SAIDs

**Capture base**: EFIJzEQT0Q_41ZVne-5lVLsdoTMS3nx8CT7HomMJLYad

**Bundle**: EM-83B569XnkfKU3qwOnXdjfIiQlgM-h2MZrwBWNuWh7

**Package**: EFVDZj-_8GEThJumshsAeNhyD5FfR1b5Xcvp7WAaFb74

| Layer | SAID | Type |
| --- | --- | --- |
| character_encoding | EBD6v2Cn-IX-xgBxDMtVQ8ZB6aR4u7Yb0Ohmi8jNGp7G | spec/overlays/character_encoding/1.1 |
| conformance | EJPgoHJEvqPklZm39fBIu9uNXhNXGLMRqpbV3FBsgQlo | spec/overlays/conformance/1.1 |
| entry (eng) | EI2ber_BhMkrl2htzbMym336SoXNdRFGWAV1QNqFHud1 | spec/overlays/entry/1.1 |
| entry_code | EDnCsuQTpbe4uxVKwWAJTklkvud_OdL_n6GPvfDSRLOa | spec/overlays/entry_code/1.1 |
| format | EBYsVWGfc36uDf-ClQyn1x2p-u1K2BB0J_0104TvpFdl | spec/overlays/format/1.1 |
| information (eng) | EBRN_keSI3lA8QUWIfr07Syq1vKBZFYddAargTiS6Rf9 | spec/overlays/information/1.1 |
| label (eng) | EHel-eR8V1BOyul1SMD1k_0kgJyKk2cWsaSeMH1CSmHb | spec/overlays/label/1.1 |
| meta (eng) | EPLNrx-hPr5Dp0P5pdzKlHtLLgBjD6VzmSGmQsjonexH | spec/overlays/meta/1.1 |
| ordering | EE3HJLUoBL5_PTMEa5OI72JXEgB5f66lCZG6hofW7KuJ | community/overlays/adc/ordering/1.1 |

**Date created**: 2025-05-02 10:50:51

