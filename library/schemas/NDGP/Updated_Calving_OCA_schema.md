---
layout: default  
title: Calving File Layout  
parent: NDGP  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Calving File Layout  
**Description**: Data schema for the pedigree file layout for Leveraging Genomics To Achieve Dairy Net-Zero (NDGP) 
**Classification**: RDF402  
**Author**: Ricarda E. Jahnel   
**Author Email**: rjahnel@uoguelph.ca  
**ICT Group**: NDGP  
**Schema package SAID**: EM0sWar0Ibu4VCRNqpUw6qECm3ko1mVYHF7_i8dWZyw9  

[Download schema](Updated_Calving_OCA_package.json)


[Download LinkML Schema](Calving_LinkML/schema.json) ([yaml](Calving_LinkML/schema.yaml); table view: [fields](https://github.com/ClimateSmartAgCollab/HUB-Harmonization/blob/main/library/schemas/NDGP/Calving_LinkML/schema_slots.tsv), [picklists](https://github.com/ClimateSmartAgCollab/HUB-Harmonization/blob/main/library/schemas/NDGP/Calving_LinkML/schema_enums.tsv))

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| FILE_TYPE | FILE_TYPE |  |
| ANIMAL_ID | ANIMAL_ID | INTERBULL REGISTRATION CODE WHICH HAS EXACTLY 19 CHARACTERS. MADE UP OF FOUR COMPONENTS: BREED (3), COUNTRY (3), SEX(1), REGISTRATION NUMBER(12) |
| CALVING_DATE | CALVING_DATE |  |
| TRANSACTION_TYPE | TRANSACTION_TYPE |  |
| COUNTRY_OF_ORIGIN | COUNTRY-OF-ORIGIN |  |
| HERD_CODE | HERD_CODE |  |
| LACTATION_NUMBER | LACTATION_NUMBER |  |
| CONCEPTION_DATE | CONCEPTION_DATE |  |
| SOURCE_OF_DATA | SOURCE_OF_DATA | See contacts list under \'Source of Data\' column |
| PROJECT | PROJECT |  |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Calving File Layout | Data schema for the pedigree file layout for the Net-Zero Dairy Genome Project |

## Selection lists

### English

#### FILE_TYPE entry codes

| Entry code | Label |
| --- | --- |
| 01 | Pedigree |
| 02 | Calving |
| 03 | Production |
| 04 | Events |
| 05 | Genotype |
| 06 | Milk data |

#### PROJECT entry codes

| Entry code | Label |
| --- | --- |
| 1000 | EDGP |
| 1100 | EDGP & RDGP |
| 1110 | EDGP & RDGP & NAEX |
| 0100 | RDGP |
| 0110 | RDGP & NAEX |
| 0010 | NAEX |
| 1010 | EDGP & NAEX |
| 0001 | NDGP |
| 1101 | EDGP & RDGP & NDGP |
| 1111 | EDGP & RDGP & NDGP & NAEX |
| 0101 | RDGP & NDGP |

#### TRANSACTION_TYPE entry codes

| Entry code | Label |
| --- | --- |
| U | Update |
| D | Delete |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry |
| --- | --- | --- | --- | --- | --- |
| FILE_TYPE | false |  | Text | utf-8 | false |
| ANIMAL_ID | false |  | Text | utf-8 | false |
| CALVING_DATE | false |  | DateTime | utf-8 | false |
| TRANSACTION_TYPE | false |  | Text | utf-8 | false |
| COUNTRY_OF_ORIGIN | false |  | Text | utf-8 | false |
| HERD_CODE | false |  | Text | utf-8 | false |
| LACTATION_NUMBER | false |  | Numeric | utf-8 | false |
| CONCEPTION_DATE | false |  | DateTime | utf-8 | false |
| SOURCE_OF_DATA | false |  | Text | utf-8 | false |
| PROJECT | false |  | Text | utf-8 | false |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| FILE_TYPE | FILE_TYPE |  | Pedigree, Calving, Production, Events, Genotype, Milk data |
| ANIMAL_ID | ANIMAL_ID | INTERBULL REGISTRATION CODE WHICH HAS EXACTLY 19 CHARACTERS. MADE UP OF FOUR COMPONENTS: BREED (3), COUNTRY (3), SEX(1), REGISTRATION NUMBER(12) | Not a list |
| CALVING_DATE | CALVING_DATE |  | Not a list |
| TRANSACTION_TYPE | TRANSACTION_TYPE |  | Update, Delete |
| COUNTRY_OF_ORIGIN | COUNTRY-OF-ORIGIN |  | Not a list |
| HERD_CODE | HERD_CODE |  | Not a list |
| LACTATION_NUMBER | LACTATION_NUMBER |  | Not a list |
| CONCEPTION_DATE | CONCEPTION_DATE |  | Not a list |
| SOURCE_OF_DATA | SOURCE_OF_DATA | See contacts list under \'Source of Data\' column | Not a list |
| PROJECT | PROJECT |  | EDGP, EDGP & RDGP, EDGP & RDGP & NAEX, RDGP, RDGP & NAEX, NAEX, EDGP & NAEX, NDGP, EDGP & RDGP & NDGP, EDGP & RDGP & NDGP & NAEX, RDGP & NDGP |

## Schema SAIDs

**Capture base**: EDditR13zUmSMI51UvtexeThxTbcmMWs65fciY-evEW2

**Bundle**: EAcoM1e_RcuPGfeLLufbqvPNl3N14yfHA6lP3IgDcWDy

**Package**: EM0sWar0Ibu4VCRNqpUw6qECm3ko1mVYHF7_i8dWZyw9

| Layer | SAID | Type |
| --- | --- | --- |
| character_encoding | EJdgao2MpYeKsBdj6MlYtSGD1n6SKJ-SToD3TTHD9WF8 | spec/overlays/character_encoding/1.1 |
| conformance | ENGMBmKaNUYapVe1NeICSsTnM2hjkmYr5BjnM8DLW-hq | spec/overlays/conformance/1.1 |
| entry (eng) | ENCEi5EYz2uDAUngApW9geD2USvNYNbl48A23ltM1GKE | spec/overlays/entry/1.1 |
| entry_code | EPTPCKWX9YVGMTrvC92c6e61FhzhTwJ4wN0OGIiAPooR | spec/overlays/entry_code/1.1 |
| information (eng) | EJZDfgU36-k5P7zYqXTQ175cjMAFjpkSH_AZsqaiA3YW | spec/overlays/information/1.1 |
| label (eng) | EJwtWdAFqVSshZjuUiuHowtgYTSBANPO3Sw6lTkZ_rSE | spec/overlays/label/1.1 |
| meta (eng) | EJMlW4RujajP8SqprrpQzR8h9wQrgIHeuAAHcp1bqXBn | spec/overlays/meta/1.1 |
| ordering | EM0Eem-umOyrzzQ3kfN4p1PPK72ByUpum6xA6oN-Lk_C | community/overlays/adc/ordering/1.0 |

**Date created**: 2026-01-28 09:55:21

