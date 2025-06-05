---
layout: default  
title: Team ACTIVATE Multi-genus Rotational Field Trial  
parent: Activate  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Team ACTIVATE: Multi-genus Rotational Field Trial  
**Description**: This data schema refers to the Activity 2.3 phenotypic dataset which is taken on our large, multi-genus field trial.  
**Classification**: RDF401  
**Author**: Lacey Sanderson  
**Author Email**: las166@mail.usask.ca  
**ICT Group**: Activate  
**Schema package SAID**: EIem5ascBmJ8ud_RcMLBGj1JprhWZkIg0ajaz92Q5q5x  

[Download Schema](ACTIVATE-act2.3.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| plot | Plot | Identifies the plot uniquely within a given location/year (i.e. siteyear). |
| UniqueID | Unique ID | Uniquely identifies the particular plot within the larger trial. It consists of the year the plot was grown, the Plot ID and either the Lentil OR Wheat ID depending on which is grown when these data are taken. |
| Lentil | Lentil | Uniquely identifies the Lentil germplasm planted in this plot within the trial. |
| Wheat | Wheat | Uniquely identifies the Wheat germplasm planted in this plot within the trial. |
| Combo | Combo | Identifies the Lentil-Wheat combination evaluated in this plot. |
| Rep | Rep | Replication number |
| Type | Type | Treatment or check |
| Col | Col | Column number |
| Row | Row | Row number |
| Block | Block | Block number |
| BlockRow | BlockRow | Row number within block |
| BlockCol | BlockCol | Column number within block |
| Name | Name | The full name of the Lentil or Wheat germplasm evaluated in this particular row. |
| Expt | Expt | Captures the particular siteyear and Lentil/Wheat portion of the experiment evaluated in this row. This also indicates where and then these data were collected. |
| Planting_Date | Planting Date (date) | The date the seeds were sown. |
| Emergence_Date | Emergence Date (date) | The date on which at least 50% of the seeds within the plot are visible above the soil. |
| Flowering_Date_R1 | Flowering Date (R1; date) | The date at which there is one open flower at any node on 50% of the plants in the plot. This is R1 in the Lentil Reproductive & Maturity Staging Guide. |
| Maturity_Date_R7 | Maturity Date (R7; date) | This is R7 in the Lentil Reproductive & Maturity Staging Guide. |
| Days_to_Emergence | Days to Emergence (date) | The number of days from the date of planting to the \"Emergence Date\". |
| One_Open_Flower_R1 | Days till 10% of Plants have One Open Flower (R1; days) | The number of days from the date of planting to the \"Flowering Date\" where the Flowering date is the date the plants reach R1 according to the Lentil Reproductive & Maturity Staging Guide. |
| Half_Pods_Mature_R7 | Days till 10% of Plants have 1/2 Pods Mature (R7; days) | The number of days from the date of planting to the \"Maturity Date\" where the Maturity date is the date the plants reach R7 according to the Lentil Reproductive & Maturity Staging Guide. |
| Lodging | Lodging (scale; 1=upright; 5=prostrate) | Indicates the rate of lodging in the plot between R6-R7 where lodging is defined as an irreversible falling over of the primary plant stem greater than 45 degrees. |
| yield_plot | yield plot (g) | The weight of the seed harvested from the plot by the combine. |
| yield_subsample | yield subsample (g) | Some plots have yield subsampled at R7 by hand. This value is recorded here. |
| yield_total | yield total (g) | For subsampled plots this is the yield from both the combine and the subsample. For others this will be equal to the plot yield measurement. |
| NIR_LenPro_preTweak | NIR_LenPro_preTweak | Protein percentage estimated by Near Infrared Spectroscopy (old calibration) |
| NIR | NIR | Protein percentage estimated by Near Infrared Spectroscopy (updated calibration) |
| Comment | Comment | General comments from the field crew that may be pertinent to know during analysis. |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Team ACTIVATE: Multi-genus Rotational Field Trial | This data schema refers to the Activity 2.3 phenotypic dataset which is taken on our large, multi-genus field trial. |

## Selection lists

### English

#### Expt entry codes

| Entry code | Label |
| --- | --- |
| ACTIVATE 2024 Hunter Lentil | ACTIVATE 2024 Hunter Lentil |
| ACTIVATE 2024 Clavet Lentil | ACTIVATE 2024 Clavet Lentil |
| ACTIVATE 2025 Hunter Wheat | ACTIVATE 2025 Hunter Wheat |
| ACTIVATE 2025 Clavet Wheat | ACTIVATE 2025 Clavet Wheat |

#### Lodging entry codes

| Entry code | Label |
| --- | --- |
| 1 | Upright |
| 5 | Prostate |

#### Type entry codes

| Entry code | Label |
| --- | --- |
| Treatment | Treatment |
| Check | Check |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry |
| --- | --- | --- | --- | --- | --- |
| plot | false |  | Text |  | true |
| UniqueID | false |  | Text |  | true |
| Lentil | false |  | Text |  | true |
| Wheat | false |  | Text |  | true |
| Combo | false |  | Text |  | true |
| Rep | false |  | Text |  | true |
| Type | false |  | Text |  | true |
| Col | false |  | Numeric |  | true |
| Row | false |  | Numeric |  | true |
| Block | false |  | Numeric |  | true |
| BlockRow | false |  | Numeric |  | true |
| BlockCol | false |  | Numeric |  | true |
| Name | false |  | Text |  | true |
| Expt | false |  | Text |  | true |
| Planting_Date | false | year-month-day | DateTime |  | false |
| Emergence_Date | false | year-month-day | DateTime |  | false |
| Flowering_Date_R1 | false | year-month-day | DateTime |  | false |
| Maturity_Date_R7 | false | year-month-day | DateTime |  | false |
| Days_to_Emergence | false | days | Numeric |  | false |
| One_Open_Flower_R1 | false | days | Numeric |  | false |
| Half_Pods_Mature_R7 | false | days | Numeric |  | false |
| Lodging | false | scale | Numeric |  | false |
| yield_plot | false | grams | Numeric |  | false |
| yield_subsample | false | grams | Numeric |  | false |
| yield_total | false | grams | Numeric |  | false |
| NIR_LenPro_preTweak | false | percent protein | Numeric |  | false |
| NIR | false | percent protein | Numeric |  | false |
| Comment | false |  | Text |  | false |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| plot | Plot | Identifies the plot uniquely within a given location/year (i.e. siteyear). | Not a list |
| UniqueID | Unique ID | Uniquely identifies the particular plot within the larger trial. It consists of the year the plot was grown, the Plot ID and either the Lentil OR Wheat ID depending on which is grown when these data are taken. | Not a list |
| Lentil | Lentil | Uniquely identifies the Lentil germplasm planted in this plot within the trial. | Not a list |
| Wheat | Wheat | Uniquely identifies the Wheat germplasm planted in this plot within the trial. | Not a list |
| Combo | Combo | Identifies the Lentil-Wheat combination evaluated in this plot. | Not a list |
| Rep | Rep | Replication number | Not a list |
| Type | Type | Treatment or check | Treatment, Check |
| Col | Col | Column number | Not a list |
| Row | Row | Row number | Not a list |
| Block | Block | Block number | Not a list |
| BlockRow | BlockRow | Row number within block | Not a list |
| BlockCol | BlockCol | Column number within block | Not a list |
| Name | Name | The full name of the Lentil or Wheat germplasm evaluated in this particular row. | Not a list |
| Expt | Expt | Captures the particular siteyear and Lentil/Wheat portion of the experiment evaluated in this row. This also indicates where and then these data were collected. | ACTIVATE 2024 Hunter Lentil, ACTIVATE 2024 Clavet Lentil, ACTIVATE 2025 Hunter Wheat, ACTIVATE 2025 Clavet Wheat |
| Planting_Date | Planting Date (date) | The date the seeds were sown. | Not a list |
| Emergence_Date | Emergence Date (date) | The date on which at least 50% of the seeds within the plot are visible above the soil. | Not a list |
| Flowering_Date_R1 | Flowering Date (R1; date) | The date at which there is one open flower at any node on 50% of the plants in the plot. This is R1 in the Lentil Reproductive & Maturity Staging Guide. | Not a list |
| Maturity_Date_R7 | Maturity Date (R7; date) | This is R7 in the Lentil Reproductive & Maturity Staging Guide. | Not a list |
| Days_to_Emergence | Days to Emergence (date) | The number of days from the date of planting to the \"Emergence Date\". | Not a list |
| One_Open_Flower_R1 | Days till 10% of Plants have One Open Flower (R1; days) | The number of days from the date of planting to the \"Flowering Date\" where the Flowering date is the date the plants reach R1 according to the Lentil Reproductive & Maturity Staging Guide. | Not a list |
| Half_Pods_Mature_R7 | Days till 10% of Plants have 1/2 Pods Mature (R7; days) | The number of days from the date of planting to the \"Maturity Date\" where the Maturity date is the date the plants reach R7 according to the Lentil Reproductive & Maturity Staging Guide. | Not a list |
| Lodging | Lodging (scale; 1=upright; 5=prostrate) | Indicates the rate of lodging in the plot between R6-R7 where lodging is defined as an irreversible falling over of the primary plant stem greater than 45 degrees. | Upright, Prostate |
| yield_plot | yield plot (g) | The weight of the seed harvested from the plot by the combine. | Not a list |
| yield_subsample | yield subsample (g) | Some plots have yield subsampled at R7 by hand. This value is recorded here. | Not a list |
| yield_total | yield total (g) | For subsampled plots this is the yield from both the combine and the subsample. For others this will be equal to the plot yield measurement. | Not a list |
| NIR_LenPro_preTweak | NIR_LenPro_preTweak | Protein percentage estimated by Near Infrared Spectroscopy (old calibration) | Not a list |
| NIR | NIR | Protein percentage estimated by Near Infrared Spectroscopy (updated calibration) | Not a list |
| Comment | Comment | General comments from the field crew that may be pertinent to know during analysis. | Not a list |

## Schema SAIDs

**Capture base**: EEyEpnhlN7oKPxUAHvevuy9pKAGUxp78GikCqP19gLQC

**Bundle**: EEsBPAJOOmqyYyF-mLuOuY67V-h0qSyS_RA26-mH0axJ

**Package**: EIem5ascBmJ8ud_RcMLBGj1JprhWZkIg0ajaz92Q5q5x

| Layer | SAID | Type |
| --- | --- | --- |
| conformance | EOC6Uk1_jls26qvmEHO3ALSbXD2KuisF6Z_QI8NigAii | spec/overlays/conformance/1.1 |
| entry (eng) | EFIq1_ERFkejuxa94JZLMguJLesadV90nbLU-FxUvQwN | spec/overlays/entry/1.1 |
| entry_code | EB1lNVeHbpUWX_7ZxddBMVK1zTw1vi4FYQ-JGvoCAdNH | spec/overlays/entry_code/1.1 |
| information (eng) | EFvSJfygFy2zPLxJ13-msmYhNRStVm0GeWHEY5GrGrIG | spec/overlays/information/1.1 |
| label (eng) | EE460RPr8j5v9J0cYfPwhp7zAqMX1VjC__jTVrS1W5WW | spec/overlays/label/1.1 |
| meta (eng) | EAiNK207L5C5VzUuKtFPiCyaNIUGsrDF1E1n8SNBLlke | spec/overlays/meta/1.1 |
| unit | EDofPlXiMTMvdhBJsvNdkLMbQUG9ipP2XiRqIqVYo5e4 | spec/overlays/unit/1.1 |
| ordering | EA1QnkpytB6RMT2JrDOiY9dTV62cSJCydyCb6_XpBEv3 | community/overlays/adc/ordering/1.1 |
| sensitive | EH03eeS641_CQzycegyrynCne8eRoKyeJoAUD9QlSwnk | community/overlays/adc/sensitive/1.1 |

**Date created**: 2025-06-05 11:42:43

