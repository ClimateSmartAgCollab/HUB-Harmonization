---
layout: default  
title: MIR File Layout  
parent: NDGP  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: MIR File Layout  
**Description**: Data schema for the pedigree file layout for the Net-Zero Dairy Genome Project  
**Classification**: RDF402  
**Author**: Ricarda E. Jahnel  
**Author Email**: rjahnel@uoguelph.ca  
**ICT Group**: NDGP  
**Schema package SAID**: ED8EaoqSjVqLKuiQjKNRNyOqKWg4Jr_oN6QVOs1HkOuu  

[Download schema](MIR_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| FILE_TYPE | FILE_TYPE |  |
| ANIMAL_ID | ANIMAL_ID | INTERBULL REGISTRATION CODE WHICH HAS EXACTLY 19 CHARACTERS. MADE UP OF FOUR COMPONENTS: BREED (3), COUNTRY (3), SEX(1), REGISTRATION NUMBER(12) |
| DATE_OF_TESTING | DATE_OF_TESTING |  |
| TRANSACTION_TYPE | TRANSACTION_TYPE |  |
| COUNTRY_OF_DATA_ORIGIN | COUNTRY_OF_DATA_ORIGIN |  |
| HERD_CODE | HERD_CODE |  |
| TYPE_OF_SPECTROMETER | TYPE_OF_SPECTROMETER |  |
| NUMBER_OF_DATA_POINTS | NUMBER_OF_DATA_POINTS |  |
| MILK_SPECTRAL_DATA | MILK_SPECTRAL_DATA | ULTIPLIED BY 100,000,000 |
| SOURCE_OF_DATA | SOURCE_OF_DATA | See contacts list under 'Source of Data' column |
| PROJECT | PROJECT |  |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | MIR File Layout | Data schema for the pedigree file layout for the Net-Zero Dairy Genome Project |

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
| FILE_TYPE | false |  | Text | utf-8 | true |
| ANIMAL_ID | false |  | Text | utf-8 | true |
| DATE_OF_TESTING | false | YYYYMMDD | DateTime | utf-8 | true |
| TRANSACTION_TYPE | false |  | Text | utf-8 | true |
| COUNTRY_OF_DATA_ORIGIN | false |  | Text | utf-8 | true |
| HERD_CODE | false |  | Text | utf-8 | true |
| TYPE_OF_SPECTROMETER | false |  | Text | utf-8 | false |
| NUMBER_OF_DATA_POINTS | false |  | Numeric | utf-8 | false |
| MILK_SPECTRAL_DATA | false |  | Numeric | utf-8 | true |
| SOURCE_OF_DATA | false |  | Text | utf-8 | true |
| PROJECT | false |  | Text | utf-8 | true |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| FILE_TYPE | FILE_TYPE |  | Pedigree, Calving, Production, Events, Genotype, Milk data |
| ANIMAL_ID | ANIMAL_ID | INTERBULL REGISTRATION CODE WHICH HAS EXACTLY 19 CHARACTERS. MADE UP OF FOUR COMPONENTS: BREED (3), COUNTRY (3), SEX(1), REGISTRATION NUMBER(12) | Not a list |
| DATE_OF_TESTING | DATE_OF_TESTING |  | Not a list |
| TRANSACTION_TYPE | TRANSACTION_TYPE |  | Update, Delete |
| COUNTRY_OF_DATA_ORIGIN | COUNTRY_OF_DATA_ORIGIN |  | Not a list |
| HERD_CODE | HERD_CODE |  | Not a list |
| TYPE_OF_SPECTROMETER | TYPE_OF_SPECTROMETER |  | Not a list |
| NUMBER_OF_DATA_POINTS | NUMBER_OF_DATA_POINTS |  | Not a list |
| MILK_SPECTRAL_DATA | MILK_SPECTRAL_DATA | ULTIPLIED BY 100,000,000 | Not a list |
| SOURCE_OF_DATA | SOURCE_OF_DATA | See contacts list under 'Source of Data' column | Not a list |
| PROJECT | PROJECT |  | EDGP, EDGP & RDGP, EDGP & RDGP & NAEX, RDGP, RDGP & NAEX, NAEX, EDGP & NAEX, NDGP |

## Schema SAIDs

**Capture base**: EDFE9GXdOORvDAXdxNms4OEB0FEZBY_V_HHgg3nWYb00

**Bundle**: EGBhO282aqbUetZ3vK2Hqe-4sCLPnWAJqhesI3-fPB83

**Package**: ED8EaoqSjVqLKuiQjKNRNyOqKWg4Jr_oN6QVOs1HkOuu

| Layer | SAID | Type |
| --- | --- | --- |
| character_encoding | EP-SImDTQ1cDbVnfdk9ZlrDKNwMziVZdrZiz0jI9h21I | spec/overlays/character_encoding/1.1 |
| conformance | ECsqf5yqetvOK2elS07Tmoh5T6uqUjkGgEcrDroZp8j5 | spec/overlays/conformance/1.1 |
| entry (eng) | EEBIBStnDHbQrJQ6l_EIksqQypLF8gTisVPrN44UVLsW | spec/overlays/entry/1.1 |
| entry_code | ECEpdbR2P0lBiDAKrQXWCUBEQn8cG60j-CI1AfriKXOm | spec/overlays/entry_code/1.1 |
| information (eng) | EKEaZrF5aKG4AwU9hl3Wqbv6q1B3jzm_ARkOgdWwjWsH | spec/overlays/information/1.1 |
| label (eng) | ENKn5HXNqsaYcu_Aiikup3sftycSDf4I7n04TcE6ZfsB | spec/overlays/label/1.1 |
| meta (eng) | ELvnyxQJ4ApfRZ4fPNi1S4ZB8JJRV32MnF0BhTIwt67P | spec/overlays/meta/1.1 |
| unit | ENBa94dsT7iKvbBL32PlFmn6ShOP9Yp6Aup-GjjjunNm | spec/overlays/unit/1.1 |
| ordering | EMY_jA2FDlooR2y06aTvy-GkprZhAaoyOjCV8w4XfdBH | community/overlays/adc/ordering/1.1 |

**Date created**: 2025-05-13 13:13:04

