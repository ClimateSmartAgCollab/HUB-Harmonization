---
layout: default  
title: Nucleic_acid_submission_checklist  
parent: BENEFIT  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Nucleic_acid_submission_checklist  
**Description**: Unknown  
**Classification**: RDF106  
**Author**: George diCenzo  
**Author Email**: george.dicenzo@queensu.ca  
**ICT Group**: BENEFIT  
**Schema package SAID**: EElVpvB2X7KDbSNYf8HLm-2masATvPWKrd9AerXuNB2l  

[Download Semantic Engine Schema](Nucleic_acid_submission_checklist_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| Well_or_tube_ID | Well_or_tube_ID | The tube ID or well position (e.g., A1, B2, etc.). |
| Sample_ID | Sample_ID | The ID of the sample. |
| Volume | Volume | Sample volume. |
| Total_DNA-RNA_amount | Total_DNA-RNA_amount | Total amount (Qubit concentration multiplied by volume) of DNA/RNA. |
| Qubit_concentration | Qubit_concentration | DNA/RNA concentration as determined by Qubit. |
| Take3_concentration | Take3_concentration | DNA/RNA concentration as determined by Take3 or Nanodrop. |
| 260-280_ratio | 260-280_ratio | The 260/280 ratio as determined by Take3 or Nanodrop. |
| 260-230_ratio | 260-280_ratio | The 260/230 ratio as determined by Take3 or Nanodrop. |
| RNase_A | RNase_A | Was a RNase A step performed? |
| Cleanup | Cleanup | Was an extra clean\-up step performed? |
| Elution_buffer | Elution_buffer | Which buffer is the DNA/RNA in? |
| Gel_check | Gel_check | Was the sample run on a gel? |
| Target_amount | Target_amoung | What is the desired mass of DNA/RNA for the submission? |
| Target_volume | Target_volume | What is the desired volume for the submission? |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Nucleic_acid_submission_checklist | Unknown |

## Selection lists

### English

#### Cleanup entry codes

| Entry code | Label |
| --- | --- |
| Yes | Yes |
| No | No |

#### Elution_buffer entry codes

| Entry code | Label |
| --- | --- |
| Water | Water |
| T10E0.1 | 10 mM Tris-HCl (pH 8.0) with 0.1 mM EDTA |
| T10E1 | 10 mM Tris-HCl (pH 8.0) with 0.1 mM EDTA |
| EB | Elution buffer from kit |

#### Gel_check entry codes

| Entry code | Label |
| --- | --- |
| Yes | Yes |
| No | No |

#### RNase_A entry codes

| Entry code | Label |
| --- | --- |
| Yes | Yes |
| No | No |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry | Format rule | Lower Bound | Inclusive | Upper Bound | Inclusive |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Well_or_tube_ID | false |  | Text |  | true | ^\.\{0,50\}$ |
| Sample_ID | false |  | Text |  | true | ^\.\{0,50\}$ |
| Volume | false | µL | Numeric |  | true | ^\[\-\+\]?\\d\*\\\.?\\d\+$ | 0 | true |  | false |
| Total_DNA-RNA_amount | false | ng | Numeric |  | true | ^\[\-\+\]?\\d\*\\\.?\\d\+$ | 0 | true |  | false |
| Qubit_concentration | false | ng/µL | Numeric |  | true | ^\[\-\+\]?\\d\*\\\.?\\d\+$ | 0 | true |  | false |
| Take3_concentration | false | ng/µL | Numeric |  | true | ^\[\-\+\]?\\d\*\\\.?\\d\+$ | 0 | true |  | false |
| 260-280_ratio | false |  | Numeric |  | true | ^\[\-\+\]?\\d\*\\\.?\\d\+$ | 0 | true |  | false |
| 260-230_ratio | false |  | Numeric |  | true | ^\[\-\+\]?\\d\*\\\.?\\d\+$ | 0 | true |  | false |
| RNase_A | false |  | Boolean |  | true |  |
| Cleanup | false |  | Boolean |  | true |  |
| Elution_buffer | false |  | Text |  | true | ^\.\{0,50\}$ |
| Gel_check | false |  | Boolean |  | true |  |
| Target_amount | false | ng | Numeric |  | true | ^\-?\[0\-9\]\+$ | 0 | true |  | false |
| Target_volume | false | µL | Numeric |  | true | ^\-?\[0\-9\]\+$ | 0 | true |  | false |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| Well_or_tube_ID | Well_or_tube_ID | The tube ID or well position (e.g., A1, B2, etc.). | Not a list |
| Sample_ID | Sample_ID | The ID of the sample. | Not a list |
| Volume | Volume | Sample volume. | Not a list |
| Total_DNA-RNA_amount | Total_DNA-RNA_amount | Total amount (Qubit concentration multiplied by volume) of DNA/RNA. | Not a list |
| Qubit_concentration | Qubit_concentration | DNA/RNA concentration as determined by Qubit. | Not a list |
| Take3_concentration | Take3_concentration | DNA/RNA concentration as determined by Take3 or Nanodrop. | Not a list |
| 260-280_ratio | 260-280_ratio | The 260/280 ratio as determined by Take3 or Nanodrop. | Not a list |
| 260-230_ratio | 260-280_ratio | The 260/230 ratio as determined by Take3 or Nanodrop. | Not a list |
| RNase_A | RNase_A | Was a RNase A step performed? | Yes, No |
| Cleanup | Cleanup | Was an extra clean\-up step performed? | Yes, No |
| Elution_buffer | Elution_buffer | Which buffer is the DNA/RNA in? | Water, 10 mM Tris-HCl (pH 8.0) with 0.1 mM EDTA, 10 mM Tris-HCl (pH 8.0) with 0.1 mM EDTA, Elution buffer from kit |
| Gel_check | Gel_check | Was the sample run on a gel? | Yes, No |
| Target_amount | Target_amoung | What is the desired mass of DNA/RNA for the submission? | Not a list |
| Target_volume | Target_volume | What is the desired volume for the submission? | Not a list |

## Schema SAIDs

**Capture base**: EEZggdoZC4ROHUDK7Zs5o4koy9e6qGmhsOba6s5z2-Ug

**Bundle**: EB4RCsc8N59MLVHAppjO-ia9ukmaW7IH1hmZOYr4Xhre

**Package**: EElVpvB2X7KDbSNYf8HLm-2masATvPWKrd9AerXuNB2l

| Layer | SAID | Type |
| --- | --- | --- |
| conformance | EADPWvKAm0CNAYprdzCgtTaVW7oFLkfDvMtVw-PNgLCJ | spec/overlays/conformance/1.1 |
| entry (eng) | EP-ZMtrfdTD798BQpZYRwtTTjD7khpos1DWQyxujFhc_ | spec/overlays/entry/1.1 |
| entry_code | ED52o20Y2tJlC3Sb2YJPUO7Vk4ZKPoa8AONyMkRXh17s | spec/overlays/entry_code/1.1 |
| format | EOv5Dzx2EES0BTTq0M_PWqRcY0jHb3NLWVAbRnW2gti4 | spec/overlays/format/1.1 |
| information (eng) | EAWYwcBNu2z8PqrlMMdc5wSsO-avZTSxstS4oFFysNCZ | spec/overlays/information/1.1 |
| label (eng) | EDcMntjBhCXJFkt40R8Xa_dj0nov_p5UFv5osoi2eKFE | spec/overlays/label/1.1 |
| meta (eng) | EAmMm8hmF-_eASiR126M6kwsEdP4c7Gk8PmOKJoO3KVe | spec/overlays/meta/1.1 |
| unit | EKflv04qHikoBc1czBW8VKM81eEnmIYFTMGSknjVV9Hc | spec/overlays/unit/1.1 |
| ordering | EBA3XHwISrfDKCElwNuEDhEgAD1Rie72uQc1oJpLEMAP | community/overlays/adc/ordering/1.0 |
| range | EOvlPlW-o5d7Ia4jLgePhWcs-pkliSuno8okn3IZvKSJ | community/overlays/adc/range/1.0 |

**Date created**: 2026-03-26 16:05:14

