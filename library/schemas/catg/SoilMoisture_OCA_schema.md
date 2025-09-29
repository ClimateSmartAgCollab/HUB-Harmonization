---
layout: default  
title: Soil Moisture Monthly  
parent: CAT-G  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Soil Moisture Monthly  
**Description**: Soil moisture monthly from CAT-G Activity 3.  
**Author**: Heather Anderson  
**Author Email**: htanders@ualberta.ca  
**ICT Group**: CAT-G  
**Schema package SAID**: EJuDwAjP7nQyCdByQUpeymL91IQ1BbhTKaSkZZe-twim

[download Semantic Engine schema](Soil_Moisture_OCA_package.json)  

[Download LinkML Schema](Soil_Moisture_LinkML/schema.json) ([yaml](Soil_Moisture_LinkML/schema.yaml); table view: [fields](https://github.com/ClimateSmartAgCollab/HUB-Harmonization/blob/main/library/schemas/catg/Soil_Moisture_LinkML/schema_slots.tsv), [picklists](https://github.com/ClimateSmartAgCollab/HUB-Harmonization/blob/main/library/schemas/catg/Soil_Moisture_LinkML/schema_enums.tsv))

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| PLOT | Plot number |  |
| MONTH | Month in which data was taken |  |
| SAMPLEDATE | Date soil moisture was sampled |  |
| OBSERVERS | Initials of individuals who took data sample |  |
| RANCH | Ranch name |  |
| ENV_PROBEMOIS | Probe Moisture Reading |  |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Soil Moisture Monthly | Soil moisture monthly from CAT-G Activity 3. |

## Selection lists

### English

#### MONTH entry codes

| Entry code | Label |
| --- | --- |
| January | January |
| February | February |
| March | March |
| April | April |
| May | May |
| June | June |
| July | July |
| August | August |
| September | September |
| October | October |
| November | November |
| December | December |

#### RANCH entry codes

| Entry code | Label |
| --- | --- |
| Kinsella | Kinsella |
| Mattheis | Mattheis |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| PLOT | false |  | Numeric |  |
| MONTH | false |  | Text |  |
| SAMPLEDATE | false |  | DateTime |  |
| OBSERVERS | false |  | Text |  |
| RANCH | false |  | Text |  |
| ENV_PROBEMOIS | false |  | Numeric |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| PLOT | Plot number |  | Not a list |
| MONTH | Month in which data was taken |  | January, February, March, April, May, June, July, August, September, October, November, December |
| SAMPLEDATE | Date soil moisture was sampled |  | Not a list |
| OBSERVERS | Initials of individuals who took data sample |  | Not a list |
| RANCH | Ranch name |  | Kinsella, Mattheis |
| ENV_PROBEMOIS | Probe Moisture Reading |  | Not a list |

## Schema SAIDs

**Capture base**: EOnV0PsMltLfk7n68iMHHfyr_tUnUIdTJ7GSCxPGOHLv

**Bundle**: EEFIBI5OgXihPEy1bln039k49-QJ72D9AHg7BtnLPjz6

**Package**: EJuDwAjP7nQyCdByQUpeymL91IQ1BbhTKaSkZZe-twim

| Layer | SAID | Type |
| --- | --- | --- |
| entry (eng) | EGyasN181LTN5banYs--0Um-BkxZ0arxQ0G-RbZ5v-KK | spec/overlays/entry/1.1 |
| entry_code | EOU36xFDU-pibwWI8nvQpCiqg7DuLzAPCSusPkEatfl5 | spec/overlays/entry_code/1.1 |
| label (eng) | EBlzF3KYma5fP1rFCCeHWEwl8MypMNm08-9c89girwwY | spec/overlays/label/1.1 |
| meta (eng) | EL246rjRvh3ZU_lnE0wIEpfk99AAC506Ql98_Kh9vB72 | spec/overlays/meta/1.1 |
| ordering | EBkd-7dQmYPbcXLsEht1rW2CtHnuT_bPvFwIODSKSxWY | community/overlays/adc/ordering/1.1 |

**Date created**: 2025-09-11 09:15:18

