---
layout: default  
title: SoilData  
parent: CAT-G  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: SoilData  
**Description**: Soil data from CAT-G  
**Author**: Zerong Dai  
**Author Email**: zerong@ualberta.ca  
**ICT Group**: CAT-G  
**Schema package SAID**: EHT1QqCTapEvtLqdVfDDRl3SJ6_77i0XinNxNVBaSmZ6  

[download Semantic Engine schema](SoilData_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| Ranch |  |  |
| Plot_ID |  |  |
| Nitrogen_Weight |  |  |
| pH_Weight |  |  |
| Before_Moisture_Weight |  |  |
| After_Moisture_Weight |  |  |
| Percent_Moisture |  |  |
| Phosphorous_Weight |  |  |
| Texture_Weight |  |  |
| Carbon_Weight |  |  |
| C_N_Weight |  |  |
| Necromass_Weight |  |  |
| Soil_pH |  |  |
| Comments |  |  |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | SoilData | Soil data from CAT-G |

## Selection lists

### English

#### Ranch entry codes

| Entry code | Label |
| --- | --- |
| K | Kinsella |
| M | Mattheis |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry |
| --- | --- | --- | --- | --- | --- |
| Ranch | false |  | Text |  | true |
| Plot_ID | false |  | Numeric |  | true |
| Nitrogen_Weight | false |  | Numeric |  | false |
| pH_Weight | false |  | Numeric |  | false |
| Before_Moisture_Weight | false |  | Numeric |  | false |
| After_Moisture_Weight | false |  | Numeric |  | false |
| Percent_Moisture | false |  | Numeric |  | false |
| Phosphorous_Weight | false |  | Numeric |  | false |
| Texture_Weight | false |  | Numeric |  | false |
| Carbon_Weight | false |  | Numeric |  | false |
| C_N_Weight | false |  | Numeric |  | false |
| Necromass_Weight | false |  | Numeric |  | false |
| Soil_pH | false |  | Numeric |  | false |
| Comments | false |  | Text |  | false |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| Ranch |  |  | Kinsella, Mattheis |
| Plot_ID |  |  | Not a list |
| Nitrogen_Weight |  |  | Not a list |
| pH_Weight |  |  | Not a list |
| Before_Moisture_Weight |  |  | Not a list |
| After_Moisture_Weight |  |  | Not a list |
| Percent_Moisture |  |  | Not a list |
| Phosphorous_Weight |  |  | Not a list |
| Texture_Weight |  |  | Not a list |
| Carbon_Weight |  |  | Not a list |
| C_N_Weight |  |  | Not a list |
| Necromass_Weight |  |  | Not a list |
| Soil_pH |  |  | Not a list |
| Comments |  |  | Not a list |

## Schema SAIDs

**Capture base**: EBl8qFZOvKgiMPTjwyB6lUK-YdLngxbpeoeEFpPON8Zm

**Bundle**: EOttOoM0Ls_Ednd-ggLzx1y8SnMvrRiWnZFigtAzg2Z0

**Package**: EHT1QqCTapEvtLqdVfDDRl3SJ6_77i0XinNxNVBaSmZ6

| Layer | SAID | Type |
| --- | --- | --- |
| conformance | EIdu8uSgP5hIMzw9zuc5S-J7ITdZjgRwJs6VtLesN22m | spec/overlays/conformance/1.1 |
| entry (eng) | EErGoQQc8FLHp4VyuStbiuYBfQtbp767MNXzhzYN45GT | spec/overlays/entry/1.1 |
| entry_code | EJsm3j933Cjpofk8Q_3wqvY7a2ZzAPBmF519afYNaPZs | spec/overlays/entry_code/1.1 |
| meta (eng) | ECo85zu-VQuWhDILaUE1OCl9pPfHdUxxlabEi75e_q5f | spec/overlays/meta/1.1 |
| ordering | EPBhTCpKpTVjzCDYpzefZIhGhlMSpGsd1i1yVtmC6VQO | community/overlays/adc/ordering/1.1 |

**Date created**: 2025-09-11 09:13:42

