---
layout: default  
title: Events File Layout  
parent: NDGP  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Events File Layout  
**Description**: Data schema for the pedigree file layout for the Leveraging Genomics To Achieve Dairy Net-Zero (NDGP)  
**Classification**: RDF402  
**Author**: Ricarda E. Jahnel   
**Author Email**: rjahnel@uoguelph.ca  
**ICT Group**: NDGP  
**Schema package SAID**: EFyJo7JVs_fOkRWd-RMHG6ASJYviP_Gh_mXAV2Tr7dFR 

[Download schema](Updated_Events_OCA_package.json)

[Download LinkML Schema](Events_LinkML/schema.json) ([yaml](Events_LinkML/schema.yaml); table view: [fields](https://github.com/ClimateSmartAgCollab/HUB-Harmonization/blob/main/library/schemas/NDGP/Events_LinkML/schema_slots.tsv), [picklists](https://github.com/ClimateSmartAgCollab/HUB-Harmonization/blob/main/library/schemas/NDGP/Events_LinkML/schema_enums.tsv))

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| FILE_TYPE | FILE_TYPE |  |
| ANIMAL_ID | ANIMAL_ID | INTERBULL REGISTRATION CODE WHICH HAS EXACTLY 19 CHARACTERS. MADE UP OF FOUR COMPONENTS: BREED (3), COUNTRY (3), SEX(1), REGISTRATION NUMBER(12) |
| TEST_DATE | TEST_DATE |  |
| TRANSACTION_TYPE | TRANSACTION_TYPE |  |
| COUNTRY_OF_ORIGIN | COUNTRY_OF_ORIGIN |  |
| HERD_CODE | HERD_CODE |  |
| TRIAL | TRIAL |  |
| 24H_DRY_MATTER_INTAKE | 24H_DRY_MATTER_INTAKE |  |
| 24H_DRY_MATTER_INTAKE_MEASUREMENT_ESTIMATE | 24H_DRY_MATTER_INTAKE_MEASUREMENT_ESTIMATE |  |
| PERCENTAGE_OF_DIGESTIBLE_NUTRIENTS | PERCENTAGE_OF_DIGESTIBLE_NUTRIENTS |  |
| LIVE_BODY_WEIGHT | LIVE_BODY_WEIGHT |  |
| LIVE_BODY_WEIGHT_MEASUREMENT_ESTIMATE | LIVE_BODY_WEIGHT_MEASUREMENT_ESTIMATE |  |
| BODY_CONDITION_SCORE | BODY_CONDITION_SCORE |  |
| 24H_WATER_INTAKE | 24H_WATER_INTAKE |  |
| 24H_WATER_INTAKE_MEASUREMENT_ESTIMATE | 24H_WATER_INTAKE_MEASUREMENT_ESTIMATE |  |
| CH4_EMISSION | CH4_EMISSION |  |
| CH4_EMISSION_MEASUREMENT_ESTIMATE | CH4_EMISSION_MEASUREMENT_ESTIMATE |  |
| STANDARD_DEVIATION_CH4_EMISSION | STANDARD_DEVIATION_CH4_EMISSION |  |
| CH4_EMISSION_PPM | CH4_EMISSION_PPM |  |
| CH4_EMISSION_MEASUREMENT_ESTIMATE_PPM | CH4_EMISSION_MEASUREMENT_ESTIMATE_PPM |  |
| STANDARD_DEVIATION_CH4_EMISSION_PPM | STANDARD_DEVIATION_CH4_EMISSION_PPM |  |
| CO2_EMISSION | CO2_EMISSION |  |
| CO2_EMISSION_MEASUREMENT_ESTIMATE | CO2_EMISSION_MEASUREMENT_ESTIMATE |  |
| STANDARD_DEVIATION_CO2_EMISSION | STANDARD_DEVIATION_CO2_EMISSION |  |
| CO2_EMISSION_PPM | CO2_EMISSION_PPM |  |
| CO2_EMISSION_PPM_MEASUREMENT_ESTIMATE | CO2_EMISSION_PPM_MEASUREMENT_ESTIMATE |  |
| STANDARD_DEVIATION_SD_CO2_PPM | STANDARD_DEVIATION_SD_CO2_PPM |  |
| CH4_MEASURE_METHOD | CH4_MEASURE_METHOD |  |
| SOURCE_OF_DATA | SOURCE_OF_DATA | See contacts list under \'Source of Data\' column |
| PROJECT | PROJECT |  |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Events File Layout | Data schema for the pedigree file layout for the Net-Zero Dairy Genome Project |

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
| TEST_DATE | false |  | DateTime | utf-8 | false |
| TRANSACTION_TYPE | false |  | Text | utf-8 | false |
| COUNTRY_OF_ORIGIN | false |  | Text | utf-8 | false |
| HERD_CODE | false |  | Text | utf-8 | false |
| TRIAL | false |  | Text | utf-8 | false |
| 24H_DRY_MATTER_INTAKE | false | G/DAY | Numeric |  | false |
| 24H_DRY_MATTER_INTAKE_MEASUREMENT_ESTIMATE | false |  | Text | utf-8 | false |
| PERCENTAGE_OF_DIGESTIBLE_NUTRIENTS | false | % | Numeric | utf-8 | false |
| LIVE_BODY_WEIGHT | false | KG | Numeric | utf-8 | false |
| LIVE_BODY_WEIGHT_MEASUREMENT_ESTIMATE | false |  | Text | utf-8 | false |
| BODY_CONDITION_SCORE | false | Score | Numeric | utf-8 | false |
| 24H_WATER_INTAKE | false | DL | Numeric | utf-8 | false |
| 24H_WATER_INTAKE_MEASUREMENT_ESTIMATE | false |  | Text | utf-8 | false |
| CH4_EMISSION | false | G/DAY | Numeric | utf-8 | false |
| CH4_EMISSION_MEASUREMENT_ESTIMATE | false |  | Text |  | false |
| STANDARD_DEVIATION_CH4_EMISSION | false | G/DAY | Numeric |  | false |
| CH4_EMISSION_PPM | false | PPM | Numeric |  | false |
| CH4_EMISSION_MEASUREMENT_ESTIMATE_PPM | false |  | Text |  | false |
| STANDARD_DEVIATION_CH4_EMISSION_PPM | false | PPM | Numeric |  | false |
| CO2_EMISSION | false | G/DAY | Numeric |  | false |
| CO2_EMISSION_MEASUREMENT_ESTIMATE | false | G/DAY | Numeric |  | false |
| STANDARD_DEVIATION_CO2_EMISSION | false | G/DAY | Numeric |  | false |
| CO2_EMISSION_PPM | false | PPM | Numeric |  | false |
| CO2_EMISSION_PPM_MEASUREMENT_ESTIMATE | false |  | Text |  | false |
| STANDARD_DEVIATION_SD_CO2_PPM | false | PPM | Numeric |  | false |
| CH4_MEASURE_METHOD | false |  | Text |  | false |
| SOURCE_OF_DATA | false |  | Text | utf-8 | false |
| PROJECT | false |  | Text | utf-8 | false |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| FILE_TYPE | FILE_TYPE |  | Pedigree, Calving, Production, Events, Genotype, Milk data |
| ANIMAL_ID | ANIMAL_ID | INTERBULL REGISTRATION CODE WHICH HAS EXACTLY 19 CHARACTERS. MADE UP OF FOUR COMPONENTS: BREED (3), COUNTRY (3), SEX(1), REGISTRATION NUMBER(12) | Not a list |
| TEST_DATE | TEST_DATE |  | Not a list |
| TRANSACTION_TYPE | TRANSACTION_TYPE |  | Update, Delete |
| COUNTRY_OF_ORIGIN | COUNTRY_OF_ORIGIN |  | Not a list |
| HERD_CODE | HERD_CODE |  | Not a list |
| TRIAL | TRIAL |  | Not a list |
| 24H_DRY_MATTER_INTAKE | 24H_DRY_MATTER_INTAKE |  | Not a list |
| 24H_DRY_MATTER_INTAKE_MEASUREMENT_ESTIMATE | 24H_DRY_MATTER_INTAKE_MEASUREMENT_ESTIMATE |  | Not a list |
| PERCENTAGE_OF_DIGESTIBLE_NUTRIENTS | PERCENTAGE_OF_DIGESTIBLE_NUTRIENTS |  | Not a list |
| LIVE_BODY_WEIGHT | LIVE_BODY_WEIGHT |  | Not a list |
| LIVE_BODY_WEIGHT_MEASUREMENT_ESTIMATE | LIVE_BODY_WEIGHT_MEASUREMENT_ESTIMATE |  | Not a list |
| BODY_CONDITION_SCORE | BODY_CONDITION_SCORE |  | Not a list |
| 24H_WATER_INTAKE | 24H_WATER_INTAKE |  | Not a list |
| 24H_WATER_INTAKE_MEASUREMENT_ESTIMATE | 24H_WATER_INTAKE_MEASUREMENT_ESTIMATE |  | Not a list |
| CH4_EMISSION | CH4_EMISSION |  | Not a list |
| CH4_EMISSION_MEASUREMENT_ESTIMATE | CH4_EMISSION_MEASUREMENT_ESTIMATE |  | Not a list |
| STANDARD_DEVIATION_CH4_EMISSION | STANDARD_DEVIATION_CH4_EMISSION |  | Not a list |
| CH4_EMISSION_PPM | CH4_EMISSION_PPM |  | Not a list |
| CH4_EMISSION_MEASUREMENT_ESTIMATE_PPM | CH4_EMISSION_MEASUREMENT_ESTIMATE_PPM |  | Not a list |
| STANDARD_DEVIATION_CH4_EMISSION_PPM | STANDARD_DEVIATION_CH4_EMISSION_PPM |  | Not a list |
| CO2_EMISSION | CO2_EMISSION |  | Not a list |
| CO2_EMISSION_MEASUREMENT_ESTIMATE | CO2_EMISSION_MEASUREMENT_ESTIMATE |  | Not a list |
| STANDARD_DEVIATION_CO2_EMISSION | STANDARD_DEVIATION_CO2_EMISSION |  | Not a list |
| CO2_EMISSION_PPM | CO2_EMISSION_PPM |  | Not a list |
| CO2_EMISSION_PPM_MEASUREMENT_ESTIMATE | CO2_EMISSION_PPM_MEASUREMENT_ESTIMATE |  | Not a list |
| STANDARD_DEVIATION_SD_CO2_PPM | STANDARD_DEVIATION_SD_CO2_PPM |  | Not a list |
| CH4_MEASURE_METHOD | CH4_MEASURE_METHOD |  | Not a list |
| SOURCE_OF_DATA | SOURCE_OF_DATA | See contacts list under \'Source of Data\' column | Not a list |
| PROJECT | PROJECT |  | EDGP, EDGP & RDGP, EDGP & RDGP & NAEX, RDGP, RDGP & NAEX, NAEX, EDGP & NAEX, NDGP, EDGP & RDGP & NDGP, EDGP & RDGP & NDGP & NAEX, RDGP & NDGP |

## Schema SAIDs

**Capture base**: ECqSU5M69bxho9srO6db-V441HKMxZ7vL9wElMDb5DDW

**Bundle**: EDhk4HFeHc1ICrlGVvVKYXNCb5Kae96Dz0BBIWNb2xi2

**Package**: EFyJo7JVs_fOkRWd-RMHG6ASJYviP_Gh_mXAV2Tr7dFR

| Layer | SAID | Type |
| --- | --- | --- |
| character_encoding | EJ4w4D49h2gG33h-CzNWJShbV7WgE3TfINvBu4P6cR-r | spec/overlays/character_encoding/1.1 |
| conformance | EGWWUHEvQtYMAYMa-pw5oeXcQ2CHQhcCM2m3XPB5YD1f | spec/overlays/conformance/1.1 |
| entry (eng) | ELz0bwkb3Jo1JjQD3grRcfFJhPpug64Eqiqk5rspyIgE | spec/overlays/entry/1.1 |
| entry_code | EAIOeIZwCd3k7taoy5klaJ0giSbwGW16VeyVS2CSSbeg | spec/overlays/entry_code/1.1 |
| information (eng) | EFzNLAzkJuHnB_a84_0uzCQo_JZeZyrqf_fE0vMJP5rZ | spec/overlays/information/1.1 |
| label (eng) | EDDyN5I8SF3zGJfGkYRR2SUOaMjuqFeYL-8oDqQDwZSw | spec/overlays/label/1.1 |
| meta (eng) | EGYwmTaU4PLjHlJVSlA17_a_jYc76SMvw5LhB3LFwUVU | spec/overlays/meta/1.1 |
| unit | EDjRHOxkO7kqmYVsr2eKnAj3h5G5SDXLJkO0uUOaiRYx | spec/overlays/unit/1.1 |
| ordering | EN5xuiILqnuX0rZjPGyQhofqE4opZT9i9ZgykIDTMcgN | community/overlays/adc/ordering/1.0 |

**Date created**: 2026-01-28 09:55:57

