---
layout: default  
title: Genotype File Layout  
parent: NDGP  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Genotype File Layout  
**Description**: Data schema for the pedigree file layout for the Net-Zero Dairy Genome Project  
**Classification**: RDF402  
**Author**: Ricarda E. Jahnel   
**Author Email**: rjahnel@uoguelph.ca  
**ICT Group**: NDGP  

[Download Schema](Genotype_OCA_bundle.zip)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| ANIMAL_ID | ANIMAL_ID | INTERBULL REGISTRATION CODE WHICH HAS EXACTLY 19 CHARACTERS. MADE UP OF FOUR COMPONENTS: BREED (3), COUNTRY (3), SEX(1), REGISTRATION NUMBER(12) |
| DATE_OF_GENOTYPE_TEST | DATE_OF_GENOTYPE_TEST |  |
| FILE_TYPE | FILE_TYPE |  |
| GENOTYPE | GENOTYPE | USING THE CDCB FORMAT ; THE GENOTYPE IS A VARIABLE LENGTH STRING OF 0,1,2,5 INDICATING SNP GENOTYPES OF BB, AB, AA, -- (1 BYTE PER SNP, NO COMMAS BETWEEN SNPS). FOR EXAMPLE '01252010250211110025.......'. |
| IMPUTATION_USED_TO_GENERATE_DATA | IMPUTATION_USED_TO_GENERATE_DATA | YES or NO |
| PANEL_TYPE_BEFORE_IMPUTATION | PANEL_TYPE_BEFORE_IMPUTATION |  |
| PROJECT | PROJECT |  |
| SAMPLE_ID | SAMPLE_ID | UNIQUELY IDENTIFIES GENOTYPE (ie. SENTRIX CODE); DO NOT USE THE ANIMAL_ID (REGISTRATION NUM) TO ALLOW FOR MULTIPLE GENOTYPES PER ANIMAL IF REQUIRED |
| SNP_CHIP_PANEL_TYPE | SNP_CHIP_PANEL_TYPE |  |
| SOURCE_OF_DATA | SOURCE_OF_DATA | See contacts list under 'Source of Data' column |
| TRANSACTION_TYPE | TRANSACTION_TYPE |  |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Genotype File Layout | Data schema for the pedigree file layout for the Net-Zero Dairy Genome Project |

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
| 101 | EDGP & NAEX |
| 102 | NDGP |
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
| ANIMAL_ID | false |  | Text | utf-8 | true |
| DATE_OF_GENOTYPE_TEST | false |  | DateTime | utf-8 | true |
| FILE_TYPE | false |  | Text | utf-8 | true |
| GENOTYPE | false |  | Text | utf-8 | true |
| IMPUTATION_USED_TO_GENERATE_DATA | false |  | Text | utf-8 | true |
| PANEL_TYPE_BEFORE_IMPUTATION | false |  | Text | utf-8 | false |
| PROJECT | false |  | Text | utf-8 | true |
| SAMPLE_ID | false |  | Text | utf-8 | true |
| SNP_CHIP_PANEL_TYPE | false |  | Text | utf-8 | true |
| SOURCE_OF_DATA | false |  | Text | utf-8 | true |
| TRANSACTION_TYPE | false |  | Text | utf-8 | true |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| ANIMAL_ID | ANIMAL_ID | INTERBULL REGISTRATION CODE WHICH HAS EXACTLY 19 CHARACTERS. MADE UP OF FOUR COMPONENTS: BREED (3), COUNTRY (3), SEX(1), REGISTRATION NUMBER(12) | Not a list |
| DATE_OF_GENOTYPE_TEST | DATE_OF_GENOTYPE_TEST |  | Not a list |
| FILE_TYPE | FILE_TYPE |  | Pedigree, Calving, Production, Events, Genotype, Milk data |
| GENOTYPE | GENOTYPE | USING THE CDCB FORMAT ; THE GENOTYPE IS A VARIABLE LENGTH STRING OF 0,1,2,5 INDICATING SNP GENOTYPES OF BB, AB, AA, -- (1 BYTE PER SNP, NO COMMAS BETWEEN SNPS). FOR EXAMPLE '01252010250211110025.......'. | Not a list |
| IMPUTATION_USED_TO_GENERATE_DATA | IMPUTATION_USED_TO_GENERATE_DATA | YES or NO | Not a list |
| PANEL_TYPE_BEFORE_IMPUTATION | PANEL_TYPE_BEFORE_IMPUTATION |  | Not a list |
| PROJECT | PROJECT |  | EDGP, EDGP & NAEX, NDGP, EDGP & RDGP, EDGP & RDGP & NAEX, NAEX, RDGP, RDGP & NAEX |
| SAMPLE_ID | SAMPLE_ID | UNIQUELY IDENTIFIES GENOTYPE (ie. SENTRIX CODE); DO NOT USE THE ANIMAL_ID (REGISTRATION NUM) TO ALLOW FOR MULTIPLE GENOTYPES PER ANIMAL IF REQUIRED | Not a list |
| SNP_CHIP_PANEL_TYPE | SNP_CHIP_PANEL_TYPE |  | Not a list |
| SOURCE_OF_DATA | SOURCE_OF_DATA | See contacts list under 'Source of Data' column | Not a list |
| TRANSACTION_TYPE | TRANSACTION_TYPE |  | Delete, Update |

## Schema SAIDs

**Capture base**: EOL30trcT6Ce7zyxj2QfV5JOVKH5sfXVXOJdsBhoh6vI

| Layer | SAID |
| --- | --- |
| character_encoding | ERpREYa0K5_cCUKhpTdjqnFRcrT7YW3VvQ1OjZyOgSpE |
| conformance | EiEoX0KsQqLEuqu0RXb3dJMYdkE8eYXmOw6NDY9X9J7U |
| entry (en) | EezMLqk4brFrEQ2GSXm6YxzAqoF11aNwrxTt5j2zqy00 |
| entry_code | EN7JzZkAFgfPCPL4XMISP_a4Yro2XXZCLzGiivnRw1BY |
| information (en) | Ersu-KzbK_Bi8yCxhjTB_4UXXpdFRsCFf-OtLs7HokLw |
| label (en) | EVRBJKKLTrgOgoLDN0iKz24klj6Ao_SHZsF9M4pvUbgY |
| meta (en) | EbXS1-PaSbc4whUAdnBr3Ct442ELMrxtSyhiZQuyabA0 |

**Date created**: 2025-04-29 13:50:02

