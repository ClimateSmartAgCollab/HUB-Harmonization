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
**Schema package SAID**: EOv3TSb3EDIZYdOtPIPTgtg2bNfgKwG_HNrqdGILz_WM  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| FILE_TYPE | FILE_TYPE |  |
| ANIMAL_ID | ANIMAL_ID | INTERBULL REGISTRATION CODE WHICH HAS EXACTLY 19 CHARACTERS. MADE UP OF FOUR COMPONENTS: BREED (3), COUNTRY (3), SEX(1), REGISTRATION NUMBER(12) |
| TRANSACTION_TYPE | TRANSACTION_TYPE |  |
| SIRE_ID | SIRE_ID | 12 DIGIT ALPHANUMERIC FIELD THAT CONTAIN THE UNIQUE IDENTIFICATION NUMBER ASSIGNED TO THE ANIMAL BY THE RESPECTIVE BREED ASSOCIATION. IT HAS TO BE RIGHT JUSTIFIED IN THE FIELD (WITH LEADING '0'S). |
| DAM_ID | DAM_ID | 12 DIGIT ALPHANUMERIC FIELD THAT CONTAIN THE UNIQUE IDENTIFICATION NUMBER ASSIGNED TO THE ANIMAL BY THE RESPECTIVE BREED ASSOCIATION. IT HAS TO BE RIGHT JUSTIFIED IN THE FIELD (WITH LEADING '0'S). |
| BIRTH_DATE | BIRTH_DATE |  |
| REGISTERED_NAME | REGISTERED_NAME |  |
| SOURCE_OF_DATA | SOURCE_OF_DATA | See contacts list under 'Source of Data' column |
| PROJECT | PROJECT |  |

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
| TRANSACTION_TYPE | false |  | Text | utf-8 | false |
| SIRE_ID | false |  | Text | utf-8 | true |
| DAM_ID | false |  | Text | utf-8 | true |
| BIRTH_DATE | false |  | DateTime | utf-8 | false |
| REGISTERED_NAME | false |  | Text | utf-8 | true |
| SOURCE_OF_DATA | false |  | Text | utf-8 | false |
| PROJECT | false |  | Text | utf-8 | false |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| FILE_TYPE | FILE_TYPE |  | Pedigree, Calving, Production, Events, Genotype, Milk data |
| ANIMAL_ID | ANIMAL_ID | INTERBULL REGISTRATION CODE WHICH HAS EXACTLY 19 CHARACTERS. MADE UP OF FOUR COMPONENTS: BREED (3), COUNTRY (3), SEX(1), REGISTRATION NUMBER(12) | Not a list |
| TRANSACTION_TYPE | TRANSACTION_TYPE |  | Update, Delete |
| SIRE_ID | SIRE_ID | 12 DIGIT ALPHANUMERIC FIELD THAT CONTAIN THE UNIQUE IDENTIFICATION NUMBER ASSIGNED TO THE ANIMAL BY THE RESPECTIVE BREED ASSOCIATION. IT HAS TO BE RIGHT JUSTIFIED IN THE FIELD (WITH LEADING '0'S). | Not a list |
| DAM_ID | DAM_ID | 12 DIGIT ALPHANUMERIC FIELD THAT CONTAIN THE UNIQUE IDENTIFICATION NUMBER ASSIGNED TO THE ANIMAL BY THE RESPECTIVE BREED ASSOCIATION. IT HAS TO BE RIGHT JUSTIFIED IN THE FIELD (WITH LEADING '0'S). | Not a list |
| BIRTH_DATE | BIRTH_DATE |  | Not a list |
| REGISTERED_NAME | REGISTERED_NAME |  | Not a list |
| SOURCE_OF_DATA | SOURCE_OF_DATA | See contacts list under 'Source of Data' column | Not a list |
| PROJECT | PROJECT |  | EDGP, EDGP & RDGP, EDGP & RDGP & NAEX, RDGP, RDGP & NAEX, NAEX, EDGP & NAEX |

## Schema SAIDs

**Capture base**: EKBa-ldXtgfZMXdjIwTeoccKLyJ9KlsDSIiPr737hh2R

**Bundle**: EHFHRC3XvgklWxlyXILLenKrdk9PN9bZSgNp_7l5t8nZ

**Package**: EOv3TSb3EDIZYdOtPIPTgtg2bNfgKwG_HNrqdGILz_WM

| Layer | SAID | Type |
| --- | --- | --- |
| character_encoding | EIj4bv1fC5EW4jwyw_ovMhJsDItL85ZixNelORZSyLDW | spec/overlays/character_encoding/1.1 |
| conformance | ENKUvpp6xxWoeRjWxHWyoEsiapP_qQjqtF9wEEgz3dCe | spec/overlays/conformance/1.1 |
| entry (eng) | EFDF3wqCrP2Ec1XtBjjWiCv4jcG7dRHo3cJxPfezxh3M | spec/overlays/entry/1.1 |
| entry_code | EEov_xnPMh2v2qUgTYZZ6tdJTOOdO4FBaW0hURSMGxcC | spec/overlays/entry_code/1.1 |
| information (eng) | EL9Id-flLeDFBILdbRpUU75lYeTY8bOHYNMPvtBbe4w1 | spec/overlays/information/1.1 |
| label (eng) | EBdKjDEVlcjirq6DfYxWpsxuWK56dtPvhQOKJTGV_XIn | spec/overlays/label/1.1 |
| meta (eng) | ENXWXXPkDubfnMP1WwuBhdtFWcRPgJGeQ3ghgMYy2ZxD | spec/overlays/meta/1.1 |
| ordering | EHJtLg0zRs-6OgAM_bXWINPNGm-3z2nV6LH03FOGVtzO | community/overlays/adc/ordering/1.1 |

**Date created**: 2025-04-14 16:07:02

