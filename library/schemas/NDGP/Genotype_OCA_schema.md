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
**Description**: Data schema for the pedigree file layout for the Net\-Zero Dairy Genome Project  
**Classification**: RDF402  
**Author**: Ricarda E. Jahnel   
**Author Email**: rjahnel@uoguelph.ca  
**ICT Group**: NDGP  
**Schema package SAID**: EKL4rOaOkfa_SgrxZp66HgCPV1HgAM7Q0m10yb2Ll6uz  

[Download schema](Genotype_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| ANIMAL_ID | ANIMAL_ID | INTERBULL REGISTRATION CODE WHICH HAS EXACTLY 19 CHARACTERS. MADE UP OF FOUR COMPONENTS: BREED (3), COUNTRY (3), SEX(1), REGISTRATION NUMBER(12) |
| SAMPLE_ID | SAMPLE_ID | UNIQUELY IDENTIFIES GENOTYPE (ie. SENTRIX CODE); DO NOT USE THE ANIMAL_ID (REGISTRATION NUM) TO ALLOW FOR MULTIPLE GENOTYPES PER ANIMAL IF REQUIRED |
| TRANSACTION_TYPE | TRANSACTION_TYPE |  |
| SNP_CHIP_PANEL_TYPE | SNP_CHIP_PANEL_TYPE |  |
| IMPUTATION_USED_TO_GENERATE_DATA | IMPUTATION_USED_TO_GENERATE_DATA | YES or NO |
| PANEL_TYPE_BEFORE_IMPUTATION | PANEL_TYPE_BEFORE_IMPUTATION |  |
| DATE_OF_GENOTYPE_TEST | DATE_OF_GENOTYPE_TEST |  |
| FILE_TYPE | FILE_TYPE |  |
| GENOTYPE | GENOTYPE | USING THE CDCB FORMAT ; THE GENOTYPE IS A VARIABLE LENGTH STRING OF 0,1,2,5 INDICATING SNP GENOTYPES OF BB, AB, AA, \\-\\- (1 BYTE PER SNP, NO COMMAS BETWEEN SNPS). FOR EXAMPLE \'01252010250211110025.......\'. |
| SOURCE_OF_DATA | SOURCE_OF_DATA | See contacts list under \'Source of Data\' column |
| PROJECT | PROJECT |  |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Genotype File Layout | Data schema for the pedigree file layout for the Net\-Zero Dairy Genome Project |

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
| 0001 | NDGP |
| 0010 | NAEX |
| 0100 | RDGP |
| 0101 | RDGP & NDGP |
| 0110 | RDGP & NAEX |
| 1000 | EDGP |
| 1010 | EDGP & NAEX |
| 1100 | EDGP & RDGP |
| 1101 | EDGP & RDGP & NDGP |
| 1110 | EDGP & RDGP & NAEX |
| 1111 | EDGP & RDGP & NDGP & NAEX |

#### TRANSACTION_TYPE entry codes

| Entry code | Label |
| --- | --- |
| D | Delete |
| U | Update |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry |
| --- | --- | --- | --- | --- | --- |
| ANIMAL_ID | false |  | Text | utf-8 | true |
| SAMPLE_ID | false |  | Text | utf-8 | true |
| TRANSACTION_TYPE | false |  | Text | utf-8 | true |
| SNP_CHIP_PANEL_TYPE | false |  | Text | utf-8 | true |
| IMPUTATION_USED_TO_GENERATE_DATA | false |  | Text | utf-8 | true |
| PANEL_TYPE_BEFORE_IMPUTATION | false |  | Text | utf-8 | false |
| DATE_OF_GENOTYPE_TEST | false |  | DateTime | utf-8 | true |
| FILE_TYPE | false |  | Text | utf-8 | true |
| GENOTYPE | false |  | Text | utf-8 | true |
| SOURCE_OF_DATA | false |  | Text | utf-8 | true |
| PROJECT | false |  | Text | utf-8 | true |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| ANIMAL_ID | ANIMAL_ID | INTERBULL REGISTRATION CODE WHICH HAS EXACTLY 19 CHARACTERS. MADE UP OF FOUR COMPONENTS: BREED (3), COUNTRY (3), SEX(1), REGISTRATION NUMBER(12) | Not a list |
| SAMPLE_ID | SAMPLE_ID | UNIQUELY IDENTIFIES GENOTYPE (ie. SENTRIX CODE); DO NOT USE THE ANIMAL_ID (REGISTRATION NUM) TO ALLOW FOR MULTIPLE GENOTYPES PER ANIMAL IF REQUIRED | Not a list |
| TRANSACTION_TYPE | TRANSACTION_TYPE |  | Delete, Update |
| SNP_CHIP_PANEL_TYPE | SNP_CHIP_PANEL_TYPE |  | Not a list |
| IMPUTATION_USED_TO_GENERATE_DATA | IMPUTATION_USED_TO_GENERATE_DATA | YES or NO | Not a list |
| PANEL_TYPE_BEFORE_IMPUTATION | PANEL_TYPE_BEFORE_IMPUTATION |  | Not a list |
| DATE_OF_GENOTYPE_TEST | DATE_OF_GENOTYPE_TEST |  | Not a list |
| FILE_TYPE | FILE_TYPE |  | Pedigree, Calving, Production, Events, Genotype, Milk data |
| GENOTYPE | GENOTYPE | USING THE CDCB FORMAT ; THE GENOTYPE IS A VARIABLE LENGTH STRING OF 0,1,2,5 INDICATING SNP GENOTYPES OF BB, AB, AA, \\-\\- (1 BYTE PER SNP, NO COMMAS BETWEEN SNPS). FOR EXAMPLE \'01252010250211110025.......\'. | Not a list |
| SOURCE_OF_DATA | SOURCE_OF_DATA | See contacts list under \'Source of Data\' column | Not a list |
| PROJECT | PROJECT |  | NDGP, NAEX, RDGP, RDGP & NDGP, RDGP & NAEX, EDGP, EDGP & NAEX, EDGP & RDGP, EDGP & RDGP & NDGP, EDGP & RDGP & NAEX, EDGP & RDGP & NDGP & NAEX |

## Schema SAIDs

**Capture base**: EKoWv4EyelwW51NAY-97mA3uGJ9j68EOIiDm7ZFLdCTN

**Bundle**: EBizCp-6vWJL5i3A5pj9LNNmE2JwCSil76F_YioD68lc

**Package**: EKL4rOaOkfa_SgrxZp66HgCPV1HgAM7Q0m10yb2Ll6uz

| Layer | SAID | Type |
| --- | --- | --- |
| character_encoding | EM5AcpqVolN60kpulCidNwUO_UZUIYerjYx2DyaTFLxc | spec/overlays/character_encoding/1.1 |
| conformance | EHZmUS-CBG9n4VbczloQmEcrxtfe0HxaTi5lwA-nttH1 | spec/overlays/conformance/1.1 |
| entry (eng) | EHGicLE7kuDbmbhw2j33KNDmHh1uFpNSbovpCn_ZkR3K | spec/overlays/entry/1.1 |
| entry_code | EDlT_uzpLI1teNQywh4gh9DnebK3-jZIun8ue_YsKmbz | spec/overlays/entry_code/1.1 |
| information (eng) | EAddMx_MJPYVjlwVVd6ffMKTkkdWUnsd97XuIHDOoYrD | spec/overlays/information/1.1 |
| label (eng) | EIEvgpp6R_ly_Gbob77TkfIlFVUhZoO7XFGw9h_C32QZ | spec/overlays/label/1.1 |
| meta (eng) | EI0gad0fXKY37cfkaEQQexpnkLQVeolsE9juV6ezCxlu | spec/overlays/meta/1.1 |
| ordering | EKr3iA4HqV2SuIPAi2CcOQ9ttMINWNFx41mcHe2cmio0 | community/overlays/adc/ordering/1.0 |

**Date created**: 2026-02-02 15:18:08

