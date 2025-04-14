---
layout: default  
title: Pedigree File Layout  
parent: NDGP  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Pedigree File Layout  
**Description**: Data schema for the pedigree file layout for the Resilient Dairy Genome Project  
**Classification**: RDF402  
**Author**: Michelle Edwards  
**Author Email**: edwardsm@uoguelph.ca  
**ICT Group**: NDGP  

[Download Schema](Pedigree_OCA_bundle.zip)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| ANIMAL_ID | ANIMAL_ID | INTERBULL REGISTRATION CODE WHICH HAS EXACTLY 19 CHARACTERS. MADE UP OF FOUR COMPONENTS: BREED (3), COUNTRY (3), SEX(1), REGISTRATION NUMBER(12) |
| BIRTH_DATE | BIRTH_DATE |  |
| DAM_ID | DAM_ID | 12 DIGIT ALPHANUMERIC FIELD THAT CONTAIN THE UNIQUE IDENTIFICATION NUMBER ASSIGNED TO THE ANIMAL BY THE RESPECTIVE BREED ASSOCIATION. IT HAS TO BE RIGHT JUSTIFIED IN THE FIELD (WITH LEADING '0'S). |
| FILE_TYPE | FILE_TYPE |  |
| PROJECT | PROJECT |  |
| REGISTERED_NAME | REGISTERED_NAME |  |
| SIRE_ID | SIRE_ID | 12 DIGIT ALPHANUMERIC FIELD THAT CONTAIN THE UNIQUE IDENTIFICATION NUMBER ASSIGNED TO THE ANIMAL BY THE RESPECTIVE BREED ASSOCIATION. IT HAS TO BE RIGHT JUSTIFIED IN THE FIELD (WITH LEADING '0'S). |
| SOURCE_OF_DATA | SOURCE_OF_DATA | See contacts list under "Source of Data" column |
| TRANSACTION_TYPE | TRANSACTION_TYPE |  |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Pedigree File Layout | Data schema for the pedigree file layout for the Resilient Dairy Genome Project |

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
| 06 | Milk Data |

#### PROJECT entry codes

| Entry code | Label |
| --- | --- |
| 100 | EDGP |
| 101 | EDGP & NAEX |
| 110 | EDGP & RDGP |
| 111 | EDGP & RDGP & NAEX |
| 001 | NAEX |
| 010 | RDGP |
| 011 | RDGP & NAEX |

#### TRANSACTION_TYPE entry codes

| Entry code | Label |
| --- | --- |
| D | Delete |
| U | Update |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry |
| --- | --- | --- | --- | --- | --- |
| ANIMAL_ID | false |  | Text |  | false |
| BIRTH_DATE | false |  | DateTime |  | false |
| DAM_ID | false |  | Text |  | true |
| FILE_TYPE | false |  | Text |  | false |
| PROJECT | false |  | Text |  | false |
| REGISTERED_NAME | false |  | Text |  | true |
| SIRE_ID | false |  | Text |  | true |
| SOURCE_OF_DATA | false |  | Text |  | false |
| TRANSACTION_TYPE | false |  | Text |  | false |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| ANIMAL_ID | ANIMAL_ID | INTERBULL REGISTRATION CODE WHICH HAS EXACTLY 19 CHARACTERS. MADE UP OF FOUR COMPONENTS: BREED (3), COUNTRY (3), SEX(1), REGISTRATION NUMBER(12) | Not a list |
| BIRTH_DATE | BIRTH_DATE |  | Not a list |
| DAM_ID | DAM_ID | 12 DIGIT ALPHANUMERIC FIELD THAT CONTAIN THE UNIQUE IDENTIFICATION NUMBER ASSIGNED TO THE ANIMAL BY THE RESPECTIVE BREED ASSOCIATION. IT HAS TO BE RIGHT JUSTIFIED IN THE FIELD (WITH LEADING '0'S). | Not a list |
| FILE_TYPE | FILE_TYPE |  | Pedigree, Calving, Production, Events, Genotype, Milk Data |
| PROJECT | PROJECT |  | EDGP, EDGP & NAEX, EDGP & RDGP, EDGP & RDGP & NAEX, NAEX, RDGP, RDGP & NAEX |
| REGISTERED_NAME | REGISTERED_NAME |  | Not a list |
| SIRE_ID | SIRE_ID | 12 DIGIT ALPHANUMERIC FIELD THAT CONTAIN THE UNIQUE IDENTIFICATION NUMBER ASSIGNED TO THE ANIMAL BY THE RESPECTIVE BREED ASSOCIATION. IT HAS TO BE RIGHT JUSTIFIED IN THE FIELD (WITH LEADING '0'S). | Not a list |
| SOURCE_OF_DATA | SOURCE_OF_DATA | See contacts list under "Source of Data" column | Not a list |
| TRANSACTION_TYPE | TRANSACTION_TYPE |  | Delete, Update |

## Schema SAIDs

**Capture base**: E_Pb-4ttzG9Wgo4r904yVpok9eN3012Ta8qzZa7eYEmo

| Layer | SAID |
| --- | --- |
| character_encoding | ET_Ohs8ySIksijaIcRobBlT5RUHIMS-pjgEywnqjtPQY |
| conformance | EMMe2y8Uzan3b9dH0mEq1lrzkOh1LnQMbD_NduG1OBrw |
| entry (en) | E6hHdvC2NWhNGfekf3aBfUbEBTwTApuq6S4FxDm2gzjw |
| entry_code | ELiS9kL2rviDEPqzdmm7-mz13PiOXj7D0DYvSQfxyDD8 |
| information (en) | EADjMfs60CknrBIi2AULudeEkb02CzWtBPVSU9wd96Rg |
| label (en) | Ezj97fYN5Gr11xEGmQqfJtAv4Msr9dzNgB-W5oyJAH9k |
| meta (en) | E9hGlMfRmK9qX0jJrXcBuom23cEI_aMSZNW4XCEH4vAc |

**Date created**: 2025-04-14 15:38:47

