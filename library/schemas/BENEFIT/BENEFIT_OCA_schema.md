---
layout: default  
title: BENEFIT Soil Sample Metadata  
parent: BENEFIT  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: BENEFIT Soil Sample Metadata  
**Description**: Metadata associated with the soil samples collected as part of the BENEFIT project.  
**Classification**: RDF106  
**Author**: George Colin diCenzo  
**Author Email**: george.dicenzo@queensu.ca  
**ICT Group**: BENEFIT  
**Schema package SAID**: ELw_5caFHMEkuFSb7eMWB0Om9nWLHUIpIfaUMPM01PT6  

[Download Semantic Engine Schema](BENEFIT_OCA_package.json)
[Download LinkML Schema](BENEFIT_LinkML/schema.yaml) ([yaml](BENEFIT_LinkML/schema.yaml); table view: [fields](https://github.com/ClimateSmartAgCollab/HUB-Harmonization/blob/main/library/schemas/BENEFIT/BENEFIT_LinkML/schema_slots.tsv), [picklists](https://github.com/ClimateSmartAgCollab/HUB-Harmonization/blob/main/library/schemas/BENEFIT/BENEFIT_LinkML/schema_enums.tsv))

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| GCS_ID | Genome Canada Soil ID | Unique numerical identifier of each soil sample |
| Original_soil_label | Original soil label | Original name/label given to each soil during collection |
| Host_Plant | Associated plant species | The plant species that was planted in the soil at the time of soil collection |
| Soil_type | Soil type (bulk soil or rhizosphere) | If specified, whether the soil sample represents bulk soil or rhizosphere soil |
| Province | Province | The province that the soil was collected from |
| City | City | The city that the soil was collected from |
| Latitude | Latitude | The latitude of the soil collection site |
| Longitude | Longitude | The longitude of the soil collection site |
| Collected | Date of collection | The date that the soil sample was collected |
| Received | Date of receipt | The date that the soil sample was received at the lab |
| Storage | Storage | How the soil sample was stored |
| Activity_1.1 | Activity 1.1 soils | An indication of whether the soil was used as part of Activity 1.1 research |
| Activity_1.3 | Activity 1.3 soils | An indication of whether the soil was used as part of Activity 1.3 research |
| Activity_1.4 | Activity 1.4 soils | An indication of whether the soil was used as part of Activity 1.4 research |
| Activity_2.1 | Activity 2.1 soils | An indication of whether the soil was used as part of Activity 2.1 research |
| Notes | Notes | Additional notes relevant to the soil sample |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | BENEFIT Soil Sample Metadata | Metadata associated with the soil samples collected as part of the BENEFIT project. |

## Selection lists

### English

#### Province entry codes

| Entry code | Label |
| --- | --- |
| AB | Alberta |
| BC | British Columbia |
| MB | Manitoba |
| NB | New Brunswick |
| NL | Newfoundland and Labrador |
| NS | Nova Scotia |
| ON | Ontario |
| PE | Prince Edward Island |
| QC | Quebec City |
| SK | Saskatchewan |
| NT | Northwest Territories |
| NU | Nunavut |
| YT | Yukon |

#### Soil_type entry codes

| Entry code | Label |
| --- | --- |
| Bulk | Bulk soil |
| Rhizosphere | Rhizosphere soil |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry | Format rule |
| --- | --- | --- | --- | --- | --- | --- |
| GCS_ID | false |  | Text |  | true | ^\.\{0,50\}$ |
| Original_soil_label | false |  | Text |  | false | ^\.\{0,250\}$ |
| Host_Plant | false |  | Text |  | true | ^\.\{0,250\}$ |
| Soil_type | false |  | Text |  | false | ^\.\{0,50\}$ |
| Province | false |  | Text |  | true | ^\.\{0,50\}$ |
| City | true |  | Text |  | true | ^\.\{0,250\}$ |
| Latitude | true |  | Numeric |  | true | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| Longitude | true |  | Numeric |  | true | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| Collected | false |  | DateTime |  | false | ^\(\\d\{4\}\)\-\(0\[1\-9\]\|1\[0\-2\]\)\-\(0\[1\-9\]\|\[12\]\\d\|3\[01\]\)$ |
| Received | false |  | DateTime |  | false | ^\(\\d\{4\}\)\-\(0\[1\-9\]\|1\[0\-2\]\)\-\(0\[1\-9\]\|\[12\]\\d\|3\[01\]\)$ |
| Storage | false |  | Text |  | false | ^\.\{0,800\}$ |
| Activity_1.1 | false |  | Boolean |  | false |  |
| Activity_1.3 | false |  | Boolean |  | false |  |
| Activity_1.4 | false |  | Boolean |  | false |  |
| Activity_2.1 | false |  | Boolean |  | false |  |
| Notes | true |  | Text |  | false | ^\.\{0,4000\}$ |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| GCS_ID | Genome Canada Soil ID | Unique numerical identifier of each soil sample | Not a list |
| Original_soil_label | Original soil label | Original name/label given to each soil during collection | Not a list |
| Host_Plant | Associated plant species | The plant species that was planted in the soil at the time of soil collection | Not a list |
| Soil_type | Soil type (bulk soil or rhizosphere) | If specified, whether the soil sample represents bulk soil or rhizosphere soil | Bulk soil, Rhizosphere soil |
| Province | Province | The province that the soil was collected from | Alberta, British Columbia, Manitoba, New Brunswick, Newfoundland and Labrador, Nova Scotia, Ontario, Prince Edward Island, Quebec City, Saskatchewan, Northwest Territories, Nunavut, Yukon |
| City | City | The city that the soil was collected from | Not a list |
| Latitude | Latitude | The latitude of the soil collection site | Not a list |
| Longitude | Longitude | The longitude of the soil collection site | Not a list |
| Collected | Date of collection | The date that the soil sample was collected | Not a list |
| Received | Date of receipt | The date that the soil sample was received at the lab | Not a list |
| Storage | Storage | How the soil sample was stored | Not a list |
| Activity_1.1 | Activity 1.1 soils | An indication of whether the soil was used as part of Activity 1.1 research | Not a list |
| Activity_1.3 | Activity 1.3 soils | An indication of whether the soil was used as part of Activity 1.3 research | Not a list |
| Activity_1.4 | Activity 1.4 soils | An indication of whether the soil was used as part of Activity 1.4 research | Not a list |
| Activity_2.1 | Activity 2.1 soils | An indication of whether the soil was used as part of Activity 2.1 research | Not a list |
| Notes | Notes | Additional notes relevant to the soil sample | Not a list |

## Schema SAIDs

**Capture base**: EBRDsvSEYUb3V0Ozgzq7wcnrDMqYxcmzbttH6dtZBoQg

**Bundle**: EIMkfr-jO52ISmQ1_fnLaYSt7leZA-ZeNKf56a-SOZKt

**Package**: ELw_5caFHMEkuFSb7eMWB0Om9nWLHUIpIfaUMPM01PT6

| Layer | SAID | Type |
| --- | --- | --- |
| conformance | EAbnGagAQ2gYdWMOa6HPkoeucHyWArAwrP_ub-U4syhI | spec/overlays/conformance/1.1 |
| entry (eng) | EJjdR8q8CXzEN9jzZN09yN0VNKkmgHTs_Pj_u9LZXB0a | spec/overlays/entry/1.1 |
| entry_code | EDdNMITUzJjz6YTWz3ZG6HINqABfMV29M5dkq-yCWD5w | spec/overlays/entry_code/1.1 |
| format | EFeaSDQlwJEGtspD6wE7elptlzeQ2mbGsPfENN9KeR7_ | spec/overlays/format/1.1 |
| information (eng) | EHnWcE809eMJAKV9LX-3Diiy-8a_5FP4pzOX95Q4Em6c | spec/overlays/information/1.1 |
| label (eng) | ELB9pm5lwxC1aqi6Qkyw-HHDdT77WwiQ6tP-raP2T-jK | spec/overlays/label/1.1 |
| meta (eng) | EC8-fNbhJ5u4HZrZR_Q6XMRtbWVniR8hVUZxtnpdXu8z | spec/overlays/meta/1.1 |
| ordering | EPyHj6kZMK4Oi2ZXecatVu2qTLDsq-kkDbX6J4kG0GUs | community/overlays/adc/ordering/1.1 |
| unit_framing | EN4kmBlvAvhJZ97I_8znC-siH9BMxei7luOtYnhQ-JRU | community/overlays/adc/unit_framing/1.1 |
| sensitive | EJFnix32NBqFxSLYVhcBH2nCcn4fHoNO69Fqh9qPv2WY | community/overlays/adc/sensitive/1.1 |

**Date created**: 2025-05-20 11:42:42

