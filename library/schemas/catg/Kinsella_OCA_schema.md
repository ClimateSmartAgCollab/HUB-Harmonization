---
layout: default  
title: Kinsella Cow Production Data  
parent: CAT-G  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Kinsella Cow Production Data  
**Description**: Version 3 of cow production data for Kinsella ranch.  
**Classification**: RDF402  
**Author**: Hailey Bolen  
**Author Email**: hbolen@ualberta.ca  
**ICT Group**: CAT-G  
**Schema package SAID**: EJhCz_ffRgNzEL2HfdgoyPo3t7ZvJmmmLSnKN8pRQB6h

[download Semantic Engine schema](Kinsella_Cow_Production_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| CW_TAG | Visual Cow Tag | Corresponds to the visual cow ID tag |
| CW_GENO_ID | Cow Genotype ID | The genotype identification number of the cows |
| CW_BRDT | Cow Birth date | The date cow was born (YYYY-MM-DD) |
| CW_YR_LETTER | Year Letter of Cow | Letter that reflects the year animal was born in |
| CW_AGE_JUL2025_YR | Age of Cow | Age (in years) of cow at the start of the trial, calculated from start date of trial period minus cow birthdate |
| CW_PGWT_KG | Cow PregTest Weight | Cow weight at preg check in kg, collected from raw weight files |
| CW_Pred_PGWT_KG | Cow predicted Pregnancy Weight | Cow predicted Pregnancy Weight in kg |
| CW_PGPREG | Pregnancy Status | Pregnancy diagnosis of cow at preg-check (P=Pregnant;O=Open;.=missing data) |
| CW_PGDT | Cow PregTest Date | Date cow is Preg-Checked, and often the same date as the calf is weaned (YYYY-MM-DD) |
| CF_BRDT_2024 | Calf Birth Date | Date calf was born (YYYY-MM-DD) |
| RFI_gEPD | Cow genomic estimated Expected Progeny Difference | Cow genomic estimated Expected Progeny Difference |
| CW_REMARKS | General remarks about cow | Will include general remarks about the cow before and after prebreed, ie. Treatments, notes regarding fostering, etc. |
| RANCH | Ranch name | The ranch where the animal belong (Kinsella or Mattheis) |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Kinsella Cow Production Data | Version 3 of cow production data for Kinsella ranch. |

## Selection lists

### English

#### RANCH entry codes

| Entry code | Label |
| --- | --- |
| Kinsella | Kinsella |
| Mattheis | Mattheis |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| CW_TAG | false |  | Text |  |
| CW_GENO_ID | false |  | Text |  |
| CW_BRDT | false |  | DateTime |  |
| CW_YR_LETTER | false |  | Text |  |
| CW_AGE_JUL2025_YR | false |  | Numeric |  |
| CW_PGWT_KG | false | kg | Numeric |  |
| CW_Pred_PGWT_KG | false | kg | Numeric |  |
| CW_PGPREG | false |  | Text |  |
| CW_PGDT | false |  | DateTime |  |
| CF_BRDT_2024 | false |  | DateTime |  |
| RFI_gEPD | false |  | Numeric |  |
| CW_REMARKS | false |  | Text |  |
| RANCH | false |  | Text |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| CW_TAG | Visual Cow Tag | Corresponds to the visual cow ID tag | Not a list |
| CW_GENO_ID | Cow Genotype ID | The genotype identification number of the cows | Not a list |
| CW_BRDT | Cow Birth date | The date cow was born (YYYY-MM-DD) | Not a list |
| CW_YR_LETTER | Year Letter of Cow | Letter that reflects the year animal was born in | Not a list |
| CW_AGE_JUL2025_YR | Age of Cow | Age (in years) of cow at the start of the trial, calculated from start date of trial period minus cow birthdate | Not a list |
| CW_PGWT_KG | Cow PregTest Weight | Cow weight at preg check in kg, collected from raw weight files | Not a list |
| CW_Pred_PGWT_KG | Cow predicted Pregnancy Weight | Cow predicted Pregnancy Weight in kg | Not a list |
| CW_PGPREG | Pregnancy Status | Pregnancy diagnosis of cow at preg-check (P=Pregnant;O=Open;.=missing data) | Not a list |
| CW_PGDT | Cow PregTest Date | Date cow is Preg-Checked, and often the same date as the calf is weaned (YYYY-MM-DD) | Not a list |
| CF_BRDT_2024 | Calf Birth Date | Date calf was born (YYYY-MM-DD) | Not a list |
| RFI_gEPD | Cow genomic estimated Expected Progeny Difference | Cow genomic estimated Expected Progeny Difference | Not a list |
| CW_REMARKS | General remarks about cow | Will include general remarks about the cow before and after prebreed, ie. Treatments, notes regarding fostering, etc. | Not a list |
| RANCH | Ranch name | The ranch where the animal belong (Kinsella or Mattheis) | Kinsella, Mattheis |

## Schema SAIDs

**Capture base**: EEpsjVAJWfmU2Pg4uPvTwA7FnXAfFRRPtq9xLB928zXv

**Bundle**: EIdDPkh7oprDU8J-PrHfjF9qXcsIjbyB7X5B7h7RQ-nP

**Package**: EJhCz_ffRgNzEL2HfdgoyPo3t7ZvJmmmLSnKN8pRQB6h

| Layer | SAID | Type |
| --- | --- | --- |
| entry (eng) | EBNs8B5dQdK9UZtNIdEzqd-5A3Nvm22GH7_gu72Ex5IJ | spec/overlays/entry/1.1 |
| entry_code | EFJhcJBgkUm8Q8rBxR-xk18PIyA3_hkF6Q-f4xncHnrZ | spec/overlays/entry_code/1.1 |
| information (eng) | EFRx5JxRVGU6_InC0g1hLXwAwkjnzuAkW33BGx_Gtgaz | spec/overlays/information/1.1 |
| label (eng) | ELtMmm0cCcUiTvChEY4fwIFm4C85XUIC72ZftBVe3jyT | spec/overlays/label/1.1 |
| meta (eng) | EAWZhYMgHuR1TlODq6D1EnG9X21gmmSE93FBEhpaNEZb | spec/overlays/meta/1.1 |
| unit | ELoRh2PzfcWvAmx2y_5Gg6cKgoOonWQxW6F_JKkJzZq6 | spec/overlays/unit/1.1 |
| ordering | EBXCRedRtg0DrCMEC24kGErnPLwj1rL9v3UeNTdYBs01 | community/overlays/adc/ordering/1.1 |

**Date created**: 2025-09-11 09:16:20

