---
layout: default  
title: Milk Production File Layout  
parent: NDGP  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Milk Production File Layout  
**Description**: Data schema for the pedigree file layout for the Net-Zero Dairy Genome Project  
**Classification**: RDF402  
**Author**: Ricarda E. Jahnel  
**Author Email**: rjahnel@uoguelph.ca  
**ICT Group**: NDGP  
**Schema package SAID**: ELDo8X-M9e0qi5AZUqsSDEpv2VwspfzoDqMvGVybVwH_  

[Download schema](Milk_OCA_package.json)

[Download LinkML Schema](Milk_LinkML/schema.json) ([yaml](Milk_LinkML/schema.yaml); table view: [fields](https://github.com/ClimateSmartAgCollab/HUB-Harmonization/blob/main/library/schemas/NDGP/Milk_LinkML/schema_slots.tsv), [picklists](https://github.com/ClimateSmartAgCollab/HUB-Harmonization/blob/main/library/schemas/NDGP/Milk_LinkML/schema_enums.tsv))

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| FILE_TYPE | FILE_TYPE |  |
| ANIMAL_ID | ANIMAL_ID | INTERBULL REGISTRATION CODE WHICH HAS EXACTLY 19 CHARACTERS. MADE UP OF FOUR COMPONENTS: BREED (3), COUNTRY (3), SEX(1), REGISTRATION NUMBER(12) |
| TEST_DATE |  |  |
| TRANSACTION_TYPE | TRANSACTION_TYPE |  |
| COUNTRY_OF_ORIGIN | COUNTRY-OF-ORIGIN |  |
| HERD_CODE | HERD_CODE |  |
| MILK_YIELD | MILK_YIELD |  |
| FAT_YIELD | FAT_YIELD |  |
| PROTEIN_YIELD | PROTEIN_YIELD |  |
| LACTOSE_YIELD | LACTOSE_YIELD |  |
| SOMATIC_CELL_COUNT | SOMATIC_CELL_COUNT |  |
| MILK_UREA_NITROGEN | MILK_UREA_NITROGEN |  |
| BETA_HYDROXYBUTYRATE | BETA_HYDROXYBUTYRATE |  |
| INTEGER_OF_MILKING_PER_DAY | INTEGER_OF_MILKING_PER_DAY |  |
| MILKING_PROGRAM | MILKING_PROGRAM |  |
| FAT_PROTEIN_CORRECTED_YIELD | FAT_PROTEIN_CORRECTED_YIELD |  |
| SOURCE_OF_DATA | SOURCE_OF_DATA | See contacts list under 'Source of Data' column |
| PROJECT | PROJECT |  |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Milk Production File Layout | Data schema for the pedigree file layout for the Net-Zero Dairy Genome Project |

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
| 100 | EDGP |
| 110 | EDGP & RDGP |
| 111 | EDGP & RDGP & NAEX |
| 010 | RDGP |
| 011 | RDGP & NAEX |
| 001 | NAEX |
| 101 | EDGP & NAEX |
| 102 | NDGP |

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
| MILK_YIELD | false | KG | Numeric | utf-8 | false |
| FAT_YIELD | false | KG | Numeric | utf-8 | false |
| PROTEIN_YIELD | false | KG | Numeric | utf-8 | false |
| LACTOSE_YIELD | false | KG | Numeric | utf-8 | false |
| SOMATIC_CELL_COUNT | false | 1000/ML | Numeric | utf-8 | false |
| MILK_UREA_NITROGEN | false | MG/KG | Numeric | utf-8 | false |
| BETA_HYDROXYBUTYRATE | false | MMOL/L MULTIPLIED PER 1000 | Numeric | utf-8 | false |
| INTEGER_OF_MILKING_PER_DAY | false |  | Numeric | utf-8 | false |
| MILKING_PROGRAM | false |  | Text | utf-8 | false |
| FAT_PROTEIN_CORRECTED_YIELD | false | KG | Numeric | utf-8 | false |
| SOURCE_OF_DATA | false |  | Text | utf-8 | false |
| PROJECT | false |  | Text | utf-8 | false |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| FILE_TYPE | FILE_TYPE |  | Pedigree, Calving, Production, Events, Genotype, Milk data |
| ANIMAL_ID | ANIMAL_ID | INTERBULL REGISTRATION CODE WHICH HAS EXACTLY 19 CHARACTERS. MADE UP OF FOUR COMPONENTS: BREED (3), COUNTRY (3), SEX(1), REGISTRATION NUMBER(12) | Not a list |
| TEST_DATE |  |  | Not a list |
| TRANSACTION_TYPE | TRANSACTION_TYPE |  | Update, Delete |
| COUNTRY_OF_ORIGIN | COUNTRY-OF-ORIGIN |  | Not a list |
| HERD_CODE | HERD_CODE |  | Not a list |
| MILK_YIELD | MILK_YIELD |  | Not a list |
| FAT_YIELD | FAT_YIELD |  | Not a list |
| PROTEIN_YIELD | PROTEIN_YIELD |  | Not a list |
| LACTOSE_YIELD | LACTOSE_YIELD |  | Not a list |
| SOMATIC_CELL_COUNT | SOMATIC_CELL_COUNT |  | Not a list |
| MILK_UREA_NITROGEN | MILK_UREA_NITROGEN |  | Not a list |
| BETA_HYDROXYBUTYRATE | BETA_HYDROXYBUTYRATE |  | Not a list |
| INTEGER_OF_MILKING_PER_DAY | INTEGER_OF_MILKING_PER_DAY |  | Not a list |
| MILKING_PROGRAM | MILKING_PROGRAM |  | Not a list |
| FAT_PROTEIN_CORRECTED_YIELD | FAT_PROTEIN_CORRECTED_YIELD |  | Not a list |
| SOURCE_OF_DATA | SOURCE_OF_DATA | See contacts list under 'Source of Data' column | Not a list |
| PROJECT | PROJECT |  | EDGP, EDGP & RDGP, EDGP & RDGP & NAEX, RDGP, RDGP & NAEX, NAEX, EDGP & NAEX, NDGP |

## Schema SAIDs

**Capture base**: EFWqArBOnIRCoaC8DjLjBH98ps1gwqTDmzDom6lyJuiP

**Bundle**: EHazaEgeeovTXFBopDOyCiiGyFUTxOkgFxBl5xM-AaI5

**Package**: ELDo8X-M9e0qi5AZUqsSDEpv2VwspfzoDqMvGVybVwH_

| Layer | SAID | Type |
| --- | --- | --- |
| character_encoding | ECCk-s0p3Oh6NxtEri7rfPgYRkCqyZPqoPNgfaW98Azc | spec/overlays/character_encoding/1.1 |
| conformance | ENITNlh8uQvOyvqubnNH8mkGJW4vtVycsU2dqoxkKpNK | spec/overlays/conformance/1.1 |
| entry (eng) | EBeI62PigdavYz7X-Vh6Q5EkDcovgWVmL81T9-znrfpR | spec/overlays/entry/1.1 |
| entry_code | ELf8n3Ywndr9tvBbhrB_26vjW-z0_d9L6rpNEp7DviUu | spec/overlays/entry_code/1.1 |
| information (eng) | EIA-omHLyHGVGLHHOVuFLbehpszrLBjj48vvcZ-dnYFD | spec/overlays/information/1.1 |
| label (eng) | EBu4fzc2yekXZX8xiCda2KRU2rM7sZiCSB1TyY_P5Cf1 | spec/overlays/label/1.1 |
| meta (eng) | EJYcAzd7E7ILu0IErWwluSfU7Lw8cYkaBnHh-Z1BpCKA | spec/overlays/meta/1.1 |
| unit | EAFINAzNfK6xIG4PtQDavnpfmAxfW1tbob97pF4wy3y0 | spec/overlays/unit/1.1 |
| ordering | ELDdA_zjknXOhHulfrbmRS5OpIR_kMNoF1jBgzmYyWRB | community/overlays/adc/ordering/1.1 |

**Date created**: 2025-05-13 13:12:12

