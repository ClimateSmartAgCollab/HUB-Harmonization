---
layout: default  
title: TEAM BENEFIT Act 1 Individual Soil Samples  
parent: BENEFIT  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: TEAM BENEFIT: Act 1 Individual Soil Samples  
**Description**: This is a dataset of soils that have been collected for use in the ICT project. Ideally we would add more information here regarding the file/project  
**Classification**: RDF105  
**Author**: Michelle Edwards  
**Author Email**: edwardsm@uoguelph.ca  
**ICT Group**: BENEFIT  

## Schema quick view

[Download Schema](TEAM_OCA_bundle.zip)

| Attribute | Label | Description |
| --- | --- | --- |
| Act_1.1 | Act_1.1 |  |
| Act_1.3 | Act_1.3 |  |
| Act_1.4 | Act_1.4 |  |
| Act_2.1 | Act_2.1 |  |
| City | City | Name of the city where the soil sample was taken |
| Collected | Collected | Date soil sample was collected |
| Host_Plant | Host_Plant | Host plant name |
| Isolations_Made? | Isolations_Made? | Were Isolations made? |
| Label | Label |  |
| Label_original | Label_original | Original label of soil sample |
| Lat | Lat | Latitude of location where soil sample was taken |
| Long | Long | Longitude of location where soil sample was taken |
| Notes | Notes | Notes |
| Province | Province | Statistics Canada codes and provinces |
| Received | Received | Date soil sample was received |
| Storage | Storage | Storage unit and temperature samples were stored at |
| Subsample_to_Corradi_Lab | Subsample_to_Corradi_Lab | Was a subsample sent to Corradi Lab? If so, what date was it sent? |
| Subsample_to_Scott_lab | Subsample_to_Scott_lab | Was a subsample sent to Scott Lab? If so, what date was it sent? |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | TEAM BENEFIT: Act 1 Individual Soil Samples | This is a dataset of soils that have been collected for use in the ICT project. Ideally we would add more information here regarding the file/project |

## Selection lists

### English

#### Act_1.1 entry codes

| Entry code | Label |
| --- | --- |
| No | No |
| Yes | Yes |

#### Act_1.3 entry codes

| Entry code | Label |
| --- | --- |
| No | No |
| Yes | Yes |

#### Act_1.4 entry codes

| Entry code | Label |
| --- | --- |
| No | No |
| Yes | Yes |

#### Act_2.1 entry codes

| Entry code | Label |
| --- | --- |
| No | No |
| Yes | Yes |

#### City entry codes

| Entry code | Label |
| --- | --- |
| Addison | Addison |
| Arnaud | Arnaud |
| Bagot | Bagot |
| Balmoral | Balmoral |
| Bath | Bath |
| Bornholm | Bornholm |
| Brampton | Brampton |
| Brandon | Brandon |
| Caledon | Caledon |
| Carman | Carman |
| Cartwright | Cartwright |
| Central Elgin | Central Elgin |
| Dublin | Dublin |
| Exeter | Exeter |
| Francis | Francis |
| Glenlea | Glenlea |
| Granton | Granton |
| Kingston | Kingston |
| Lacombe | Lacombe |
| Lanigan | Lanigan |
| MacGregor | MacGregor |
| Melita | Melita |
| Minto | Minto |
| NA | NA |
| Oak Lake | Oak Lake |
| Paris (Brant County) | Paris (Brant County) |
| Parkbeg | Parkbeg |
| Phillips Farm | Phillips Farm |
| Portage la Prairie | Portage la Prairie |
| St. George (Brant County) | St. George (Brant County) |
| St. Pierre Jolys | St. Pierre Jolys |
| Wawanesa | Wawanesa |
| Wawota | Wawota |
| Winchester | Winchester |

#### Province entry codes

| Entry code | Label |
| --- | --- |
| 10 | Newfoundland and Labrador |
| 11 | Prince Edward Island |
| 12 | Nova Scotia |
| 13 | New Brunswick |
| 24 | Quebec |
| 35 | Ontario |
| 46 | Manitoba |
| 47 | Saskatchewan |
| 48 | Alberta |
| 59 | British Columbia |
| 60 | Yukon |
| 61 | Northwest Territories |
| 62 | Nunavut |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry | Format rule |
| --- | --- | --- | --- | --- | --- | --- |
| Act_1.1 | false |  | Boolean | utf-8 | false |  |
| Act_1.3 | false |  | Boolean | utf-8 | false |  |
| Act_1.4 | false |  | Boolean | utf-8 | false |  |
| Act_2.1 | false |  | Boolean | utf-8 | false |  |
| City | false |  | Text | utf-8 | false | ^\.\{0,50\}$ |
| Collected | false |  | DateTime | utf-8 | false |  |
| Host_Plant | false |  | Text | utf-8 | false |  |
| Isolations_Made? | false |  | Text | utf-8 | false |  |
| Label | false |  | Text | utf-8 | true |  |
| Label_original | false |  | Text | utf-8 | false |  |
| Lat | true |  | Numeric | utf-8 | false |  |
| Long | true |  | Numeric | utf-8 | false |  |
| Notes | false |  | Text | utf-8 | false |  |
| Province | false |  | Text | utf-8 | false |  |
| Received | false |  | DateTime | utf-8 | false |  |
| Storage | false |  | Text | utf-8 | false |  |
| Subsample_to_Corradi_Lab | false |  | Text | utf-8 | false |  |
| Subsample_to_Scott_lab | false |  | Text | utf-8 | false |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| Act_1.1 | Act_1.1 |  | No, Yes |
| Act_1.3 | Act_1.3 |  | No, Yes |
| Act_1.4 | Act_1.4 |  | No, Yes |
| Act_2.1 | Act_2.1 |  | No, Yes |
| City | City | Name of the city where the soil sample was taken | Addison, Arnaud, Bagot, Balmoral, Bath, Bornholm, Brampton, Brandon, Caledon, Carman, Cartwright, Central Elgin, Dublin, Exeter, Francis, Glenlea, Granton, Kingston, Lacombe, Lanigan, MacGregor, Melita, Minto, NA, Oak Lake, Paris (Brant County), Parkbeg, Phillips Farm, Portage la Prairie, St. George (Brant County), St. Pierre Jolys, Wawanesa, Wawota, Winchester |
| Collected | Collected | Date soil sample was collected | Not a list |
| Host_Plant | Host_Plant | Host plant name | Not a list |
| Isolations_Made? | Isolations_Made? | Were Isolations made? | Not a list |
| Label | Label |  | Not a list |
| Label_original | Label_original | Original label of soil sample | Not a list |
| Lat | Lat | Latitude of location where soil sample was taken | Not a list |
| Long | Long | Longitude of location where soil sample was taken | Not a list |
| Notes | Notes | Notes | Not a list |
| Province | Province | Statistics Canada codes and provinces | Newfoundland and Labrador, Prince Edward Island, Nova Scotia, New Brunswick, Quebec, Ontario, Manitoba, Saskatchewan, Alberta, British Columbia, Yukon, Northwest Territories, Nunavut |
| Received | Received | Date soil sample was received | Not a list |
| Storage | Storage | Storage unit and temperature samples were stored at | Not a list |
| Subsample_to_Corradi_Lab | Subsample_to_Corradi_Lab | Was a subsample sent to Corradi Lab? If so, what date was it sent? | Not a list |
| Subsample_to_Scott_lab | Subsample_to_Scott_lab | Was a subsample sent to Scott Lab? If so, what date was it sent? | Not a list |

## Schema SAIDs

**Capture base**: Ert6ARBNBNZKjjSrpustkRJSTUXc-zizq6i4qzGhkPLI

| Layer | SAID |
| --- | --- |
| character_encoding | EySSNlivnOpgiFFbFjmm2PT9RlF0rgTPFzRVr_jGHnsQ |
| conformance | EH6M94ys4hG2FZafJkE0ilzK06eeN4krJ38MjVEFeu5c |
| entry (en) | Eb_UXqj8giITpeGJxOGib-vRKAem0cWTcnYlbzDF6Nzs |
| entry_code | EOdSBxXgYO4OpL2f2B9_wM7FGdWoyrBCp2d9HyKUuKLw |
| format | Esul5Q-_GT_Lm0IdKyPQxsG9m2EW8dcji37uOmj61WMk |
| information (en) | EDpIfLr9MizKM6jsk076ySV9AW9T_aw15piapFJtjfdU |
| label (en) | ETs_15A1Mqs_pBJHVj6eCbrzvMJ67yYo_ZY9haEetva0 |
| meta (en) | EiXcYHSOkklA4Wb1v9N3l7aSdPEq6ELLBfooJqcUlR4Y |

**Date created**: 2025-01-31 08:59:25
