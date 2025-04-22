---
layout: default  
title: Team ACTIVATE Large Field Trial  
parent: Activate
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Team ACTIVATE: Large Field Trial  
**Description**: This data schema refers to the Act2.3 dataset which is a subset from our large field trial  
**Classification**: RDF401  
**Author**: Michelle Edwards  
**Author Email**: edwardsm@uoguelph.ca  
**ICT Group**: Activate  
**Schema package SAID**: ELPQjoJHYFOxwUiz4sx75q-0CRSsPa0kKToxbjxXKGQ_  

[Download Schema](Team_OCA_bundle.json)


## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| plot | plot | Plot number |
| U_ID | Unique ID | unique identifier (year_plot_lentilnumber) |
| Lentil | Lentil | Lentil number |
| Wheat | Wheat | Wheat number |
| Combo | Combo | Lentil-Wheat combination |
| Rep | Rep | Replication number |
| Type | Type | Treatment or check |
| Col | Col | Column number |
| Row | Row | Row number |
| Block | Block | Block number |
| BlockRow | BlockRow | Row nomber within block |
| BlockCol | BlockCol | Column number within block |
| Name | Name | Lentil name |
| Expt | Expt | Experiment name |
| Planting_Date | Planting Date (date) | Sowing date |
| Emergence_Date | Emergence Date (date) | Emergence date |
| Flowering_Date_R1 | Flowering Date (R1; date) | Flowering date |
| Maturity_Date_R7 | Maturity Date (R7; date) | maturity date |
| Days_to_Emergence | Days to Emergence (date) | Days from sowing to emergence |
| One_Open_Flower_R1 | Days till 10% of Plants have One Open Flower (R1; days) | Days from sowing to flowering |
| Half_Pods_Mature_R7 | Days till 10% of Plants have 1/2 Pods Mature (R7; days) | Days from sowing to maturity |
| Lodging | Lodging (scale; 1=upright; 5=prostrate) | Lodging |
| yield_plot | yield plot (g) | yield plot from combine |
| yield_subsample | yield subsample (g) | yield subsample (prior to combine) |
| yield_total | yield total (g) | total yield = subsample + combine |
| NIR_LenPro_preTweak | NIR_LenPro_preTweak | Protein percentage estimated by NIR (old calibration) |
| Comment | Comment | Comment |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Team ACTIVATE: Large Field Trial | This data schema refers to the Act2.3 dataset which is a subset from our large field trial |

## Selection lists

### English

#### Lodging entry codes

| Entry code | Label |
| --- | --- |
| 1 | Upright |
| 5 | Prostate |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| plot | false |  | Text |  |
| U_ID | false |  | Text |  |
| Lentil | false |  | Text |  |
| Wheat | false |  | Text |  |
| Combo | false |  | Text |  |
| Rep | false |  | Text |  |
| Type | false |  | Text |  |
| Col | false |  | Numeric |  |
| Row | false |  | Numeric |  |
| Block | false |  | Numeric |  |
| BlockRow | false |  | Numeric |  |
| BlockCol | false |  | Numeric |  |
| Name | false |  | Text |  |
| Expt | false |  | Text |  |
| Planting_Date | false |  | DateTime |  |
| Emergence_Date | false |  | DateTime |  |
| Flowering_Date_R1 | false |  | DateTime |  |
| Maturity_Date_R7 | false |  | DateTime |  |
| Days_to_Emergence | false | days | Numeric |  |
| One_Open_Flower_R1 | false | days | Numeric |  |
| Half_Pods_Mature_R7 | false | days | Numeric |  |
| Lodging | false | scale | Numeric |  |
| yield_plot | false | g | Numeric |  |
| yield_subsample | false | g | Numeric |  |
| yield_total | false | g | Numeric |  |
| NIR_LenPro_preTweak | false |  | Numeric |  |
| Comment | false |  | Text |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| plot | plot | Plot number | Not a list |
| U_ID | Unique ID | unique identifier (year_plot_lentilnumber) | Not a list |
| Lentil | Lentil | Lentil number | Not a list |
| Wheat | Wheat | Wheat number | Not a list |
| Combo | Combo | Lentil-Wheat combination | Not a list |
| Rep | Rep | Replication number | Not a list |
| Type | Type | Treatment or check | Not a list |
| Col | Col | Column number | Not a list |
| Row | Row | Row number | Not a list |
| Block | Block | Block number | Not a list |
| BlockRow | BlockRow | Row nomber within block | Not a list |
| BlockCol | BlockCol | Column number within block | Not a list |
| Name | Name | Lentil name | Not a list |
| Expt | Expt | Experiment name | Not a list |
| Planting_Date | Planting Date (date) | Sowing date | Not a list |
| Emergence_Date | Emergence Date (date) | Emergence date | Not a list |
| Flowering_Date_R1 | Flowering Date (R1; date) | Flowering date | Not a list |
| Maturity_Date_R7 | Maturity Date (R7; date) | maturity date | Not a list |
| Days_to_Emergence | Days to Emergence (date) | Days from sowing to emergence | Not a list |
| One_Open_Flower_R1 | Days till 10% of Plants have One Open Flower (R1; days) | Days from sowing to flowering | Not a list |
| Half_Pods_Mature_R7 | Days till 10% of Plants have 1/2 Pods Mature (R7; days) | Days from sowing to maturity | Not a list |
| Lodging | Lodging (scale; 1=upright; 5=prostrate) | Lodging | Upright, Prostate |
| yield_plot | yield plot (g) | yield plot from combine | Not a list |
| yield_subsample | yield subsample (g) | yield subsample (prior to combine) | Not a list |
| yield_total | yield total (g) | total yield = subsample + combine | Not a list |
| NIR_LenPro_preTweak | NIR_LenPro_preTweak | Protein percentage estimated by NIR (old calibration) | Not a list |
| Comment | Comment | Comment | Not a list |

## Schema SAIDs

**Capture base**: EEdoSkxincxxXw86wULNxyserIxal3Zn10AsgJjCU-RX

**Bundle**: EMdvbpvqUFLuRxPKM7Hj_z5ltT01ZNYpgwckz6Puy93E

**Package**: ELPQjoJHYFOxwUiz4sx75q-0CRSsPa0kKToxbjxXKGQ_

| Layer | SAID | Type |
| --- | --- | --- |
| entry (eng) | EMU7J42QfMZ7FC5ZFpT-giK-NGPgSgJC7lnzmkSMYbSJ | spec/overlays/entry/1.1 |
| entry_code | ECQQb1aU71HzxBkU7MJd6AIj1H_z-mpN06LbSp1z23xI | spec/overlays/entry_code/1.1 |
| information (eng) | EOKXEkcSJ-UqZTuBlw3894w8DvX-m16_AvCUFpsgLShD | spec/overlays/information/1.1 |
| label (eng) | EOtkjO5XcoY14-ducLlDR-NkN1GK0L1ivWWvWievG6vH | spec/overlays/label/1.1 |
| meta (eng) | EA059bf2q8p8d2TqJV-H8X0jhk0hWG7vMuUluuyJsD_6 | spec/overlays/meta/1.1 |
| unit | EOose8Sr8hEG5SDFUNTa1RjxTD1fQ_cWB9xDoJLQ_2TT | spec/overlays/unit/1.1 |
| ordering | EI8MB1ZCjsCNBjQERtaIhpa9HUDz1S0Y-EgzUQ4jXeV1 | community/overlays/adc/ordering/1.1 |

**Date created**: 2025-04-22 12:25:17

