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
**Description**: Data schema for the pedigree file layout for the Net-Zero Dairy Genome Project  
**Classification**: RDF402  
**Author**: Ricarda E. Jahnel   
**Author Email**: rjahnel@uoguelph.ca  
**ICT Group**: NDGP  
**Schema package SAID**: EJ1CMgbOrNg_pVKR0iBarsr_JaiQoHU56SG0QAIlsqIF  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| FILE_TYPE | FILE_TYPE |  |
| ANIMAL_ID | ANIMAL_ID | INTERBULL REGISTRATION CODE WHICH HAS EXACTLY 19 CHARACTERS. MADE UP OF FOUR COMPONENTS: BREED (3), COUNTRY (3), SEX(1), REGISTRATION NUMBER(12) |
| TRANSACTION_TYPE | TRANSACTION_TYPE |  |
| SIRE_ID | SIRE_ID | 12 DIGIT ALPHANUMERIC FIELD THAT CONTAIN THE UNIQUE IDENTIFICATION NUMBER ASSIGNED TO THE ANIMAL BY THE RESPECTIVE BREED ASSOCIATION. IT HAS TO BE RIGHT JUSTIFIED IN THE FIELD (WITH LEADING \'0\'S). |
| DAM_ID | DAM_ID | 12 DIGIT ALPHANUMERIC FIELD THAT CONTAIN THE UNIQUE IDENTIFICATION NUMBER ASSIGNED TO THE ANIMAL BY THE RESPECTIVE BREED ASSOCIATION. IT HAS TO BE RIGHT JUSTIFIED IN THE FIELD (WITH LEADING \'0\'S). |
| BIRTH_DATE | BIRTH_DATE |  |
| REGISTERED_NAME | REGISTERED_NAME |  |
| SOURCE_OF_DATA | SOURCE_OF_DATA | See contacts list under \'Source of Data\' column |
| PROJECT | PROJECT |  |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Pedigree File Layout | Data schema for the pedigree file layout for the Net-Zero Dairy Genome Project |

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
| SIRE_ID | SIRE_ID | 12 DIGIT ALPHANUMERIC FIELD THAT CONTAIN THE UNIQUE IDENTIFICATION NUMBER ASSIGNED TO THE ANIMAL BY THE RESPECTIVE BREED ASSOCIATION. IT HAS TO BE RIGHT JUSTIFIED IN THE FIELD (WITH LEADING \'0\'S). | Not a list |
| DAM_ID | DAM_ID | 12 DIGIT ALPHANUMERIC FIELD THAT CONTAIN THE UNIQUE IDENTIFICATION NUMBER ASSIGNED TO THE ANIMAL BY THE RESPECTIVE BREED ASSOCIATION. IT HAS TO BE RIGHT JUSTIFIED IN THE FIELD (WITH LEADING \'0\'S). | Not a list |
| BIRTH_DATE | BIRTH_DATE |  | Not a list |
| REGISTERED_NAME | REGISTERED_NAME |  | Not a list |
| SOURCE_OF_DATA | SOURCE_OF_DATA | See contacts list under \'Source of Data\' column | Not a list |
| PROJECT | PROJECT |  | EDGP, EDGP & RDGP, EDGP & RDGP & NAEX, RDGP, RDGP & NAEX, NAEX, EDGP & NAEX, NDGP, EDGP & RDGP & NDGP, EDGP & RDGP & NDGP & NAEX, RDGP & NDGP |

## Schema SAIDs

**Capture base**: EKBa-ldXtgfZMXdjIwTeoccKLyJ9KlsDSIiPr737hh2R

**Bundle**: EPsE3RKKNkm3Rj6bly6zwISmfEzscvj6HX7gSwodetOe

**Package**: EJ1CMgbOrNg_pVKR0iBarsr_JaiQoHU56SG0QAIlsqIF

| Layer | SAID | Type |
| --- | --- | --- |
| character_encoding | EIj4bv1fC5EW4jwyw_ovMhJsDItL85ZixNelORZSyLDW | spec/overlays/character_encoding/1.1 |
| conformance | ENKUvpp6xxWoeRjWxHWyoEsiapP_qQjqtF9wEEgz3dCe | spec/overlays/conformance/1.1 |
| entry (eng) | EALfsSQptCDbS5AC-6A1mcZJbnDIi_DVYXY7FN0YHHK- | spec/overlays/entry/1.1 |
| entry_code | EMkEJs6tO1ZRhnsnft9ibLVrf8U33nqm8dqPMCJVfPzT | spec/overlays/entry_code/1.1 |
| information (eng) | EPJj122y6xz3i02B6yRZn5L9aKMnJmHLW9ub21Ettl8O | spec/overlays/information/1.1 |
| label (eng) | EBdKjDEVlcjirq6DfYxWpsxuWK56dtPvhQOKJTGV_XIn | spec/overlays/label/1.1 |
| meta (eng) | EAQVebNHzo9vo5TETymJyOkiQTDKdsijFmCrLQNDbxr4 | spec/overlays/meta/1.1 |
| ordering | EN3mSyDmggOV-D6E-edW525e1E2GSnLh6SEPvCqYXDgs | community/overlays/adc/ordering/1.0 |

**Date created**: 2026-01-28 09:56:57

