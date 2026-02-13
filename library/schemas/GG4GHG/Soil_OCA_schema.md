---
layout: default  
title: Soil chemistry data  
parent: GG4GHG  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Soil chemistry data  
**Description**: A schema to describe soil chemistry measurements for GG4GHG data.  
**Classification**: RDF106  
**Author**: Shreemi Prabhakaran  
**Author Email**: qhm106@mail.usask.ca  
**ICT Group**: GG4GHG  
**Schema package SAID**: ELBjaeykQYw2y95klurjVNwD6_tgLuXU5XvvBY8xneFt  

[Download Semantic Engine Schema](Soil_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| name | name | The full name of the sample (Combination of plant, site, aspect and plot number). |
| plant | plant | The focal species target. |
| site | site | The site the sample was taken from. |
| aspect | aspect | Whether it is a focal or community sample. |
| Plot | Plot | The plot number associated with the sample |
| TOC400_perc | TOC400_perc | TOC400 as a percent. |
| ROC_perc | ROC_perc | ROC as a percent. |
| TIC900_perc | TIC900_perc | TIC900 as a percent. |
| TC | TC | Total Carbon |
| TN | TN | Total Nitrogen |
| SOC_perc | SOC_perc | Soil Organic Carbon percent |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Soil chemistry data | A schema to describe soil chemistry measurements for GG4GHG data. |

## Selection lists

### English

#### aspect entry codes

| Entry code | Label |
| --- | --- |
| Focal | Focal Plot |
| Community | Community Plot |

#### plant entry codes

| Entry code | Label |
| --- | --- |
| CL | Calamovilfa longifolia |
| DP | Dalea purpurea |
| LL | Linum lewisii |
| NV | Nasella viridula |

#### site entry codes

| Entry code | Label |
| --- | --- |
| ASQ | NCC Asquith |
| BFP | Buffalo Pound |
| BID | Biddulph |
| CDE | Condie |
| CFL | Cranberry Flats |
| CPH | Camp Hughes |
| DOG | Douglas |
| DUN | Dundurn |
| ECV | Echo valley |
| ESL | East Shoal Lake |
| FEL | Fort Ellice – St. Lazare |
| GLE | Grasslands E (west block) |
| GLW | Grasslands W (west block) |
| GWR | Goodwater |
| HDM | Horod Moraine – Onanole |
| HZN | Hazen |
| LAM | Lake Alma |
| MAN | Manitou |
| MAT | Matador |
| MAY | Maymonyt |
| MCK | McKinney |
| RBL | Redberry lake |
| SLO | CFB Shilo |
| STD | St. Denis |
| YQP | Yellow Quill Prairie |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| name | false |  | Text |  |
| plant | false |  | Text |  |
| site | false |  | Text |  |
| aspect | false |  | Text |  |
| Plot | false |  | Numeric |  |
| TOC400_perc | false |  | Numeric |  |
| ROC_perc | false |  | Numeric |  |
| TIC900_perc | false |  | Numeric |  |
| TC | false |  | Numeric |  |
| TN | false |  | Numeric |  |
| SOC_perc | false |  | Numeric |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| name | name | The full name of the sample (Combination of plant, site, aspect and plot number). | Not a list |
| plant | plant | The focal species target. | Calamovilfa longifolia, Dalea purpurea, Linum lewisii, Nasella viridula |
| site | site | The site the sample was taken from. | NCC Asquith, Buffalo Pound, Biddulph, Condie, Cranberry Flats, Camp Hughes, Douglas, Dundurn, Echo valley, East Shoal Lake, Fort Ellice – St. Lazare, Grasslands E (west block), Grasslands W (west block), Goodwater, Horod Moraine – Onanole, Hazen, Lake Alma, Manitou, Matador, Maymonyt, McKinney, Redberry lake, CFB Shilo, St. Denis, Yellow Quill Prairie |
| aspect | aspect | Whether it is a focal or community sample. | Focal Plot, Community Plot |
| Plot | Plot | The plot number associated with the sample | Not a list |
| TOC400_perc | TOC400_perc | TOC400 as a percent. | Not a list |
| ROC_perc | ROC_perc | ROC as a percent. | Not a list |
| TIC900_perc | TIC900_perc | TIC900 as a percent. | Not a list |
| TC | TC | Total Carbon | Not a list |
| TN | TN | Total Nitrogen | Not a list |
| SOC_perc | SOC_perc | Soil Organic Carbon percent | Not a list |

## Schema SAIDs

**Capture base**: ENZ4u4Ds9z_u8q5DD7IPXPK9wSnE6aTh-LCQ_d5hxpnW

**Bundle**: EAgGuoPIYHVzIGCiMJehE6dRzmQCG53iYV2eRHT9oant

**Package**: ELBjaeykQYw2y95klurjVNwD6_tgLuXU5XvvBY8xneFt

| Layer | SAID | Type |
| --- | --- | --- |
| entry (eng) | EO8SBTKyf3EVkeizGs9ecKMbllvE-NiwFQ6de-MpFcnE | spec/overlays/entry/1.1 |
| entry_code | ENZ0RIU2G3PlQlu-fN9YnSvr7QKTDWxKimrLdUJ-1qQh | spec/overlays/entry_code/1.1 |
| information (eng) | EHptHJqhHv3g3Szui4GOUQldgJTE8oTKhSWbPQ9tIaLp | spec/overlays/information/1.1 |
| label (eng) | ENPTMuGGMR0ea3vd8l59YyCrEGxV52DPY7Gwces3jrzV | spec/overlays/label/1.1 |
| meta (eng) | EFCTEOB_lE7s5Tz9ubacWvTZ_rGfhoFMgjvUavY1mnXT | spec/overlays/meta/1.1 |
| ordering | ECsdfDDSn5d_sIeo6RQxvoiWIH-OOqAAKmSeeCYIiDcd | community/overlays/adc/ordering/1.0 |

**Date created**: 2026-02-13 10:59:13

