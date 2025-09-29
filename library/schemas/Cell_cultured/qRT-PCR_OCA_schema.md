---
layout: default  
title: qRT-PCR  
parent: Cell Cultured Meat  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: qRT-PCR  
**Description**:   
**Classification**: RDF207  
**Author**: Chang Ge  
**Author Email**: gec@mcmaster.ca  
**ICT Group**: Cell Cultured Meat  
**Schema package SAID**: EC0_5f6_6dg4JYkB8r-qPl10daGoN0pOEiIbz5xbUvpx  

[Download Schema](qRT-PCR_OCA_package.json)

[Download LinkML Schema](qRT-PCR_LinkML/schema.json) ([yaml](qRT-PCR_LinkML/schema.yaml); table view: [fields](https://github.com/ClimateSmartAgCollab/HUB-Harmonization/blob/main/library/schemas/Cell_cultured/qRT-PCR_LinkML/schema_slots.tsv), [picklists](https://github.com/ClimateSmartAgCollab/HUB-Harmonization/blob/main/library/schemas/Cell_cultured/qRT-PCR_LinkML/schema_enums.tsv))

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| Well |  | Identifies the specific well on the qPCR plate |
| Well_Position |  | Coordinates of the well |
| Sample_Name |  | Name or ID of the biological or experimental sample |
| Target_Name |  | Target Gene |
| Reporter |  | Fluorescent dye used to detect amplification |
| CT |  | Threshold cycle where fluorescence exceeds background |
| Ct_Mean |  | Average CT value from technical replicates |
| Ct_SD |  | Standard deviation of CT values among replicates |
| Ct_Threshold |  | Fluorescence threshold used to calculate CT |
| Baseline_Start |  | Start cycle for baseline signal calculation |
| Baseline_End |  | End cycle for baseline signal calculation |
| Amp_Status |  | Indicates whether amplification was detected |
| Cq_Conf |  | Confidence in quantification cycle (Cq) value |
| HIGHSD |  | High standard deviation among technical replicates for a given sample, suggesting inconsistent amplification |
| Tm1 |  | Melting temperature of the first PCR product peak |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | qRT-PCR |  |

## Selection lists

### English

#### Amp_Status entry codes

| Entry code | Label |
| --- | --- |
| Amp | Amplified |
| No Amp | Not amplified |

#### HIGHSD entry codes

| Entry code | Label |
| --- | --- |
| Y | Yes |
| N | No |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Format rule |
| --- | --- | --- | --- | --- | --- |
| Well | false |  | Numeric |  |  |
| Well_Position | false |  | Text |  | ^\[A\-Z\]\*$ |
| Sample_Name | false |  | Text |  |  |
| Target_Name | false |  | Text |  |  |
| Reporter | false |  | Text |  |  |
| CT | false |  | Numeric |  |  |
| Ct_Mean | false |  | Numeric |  |  |
| Ct_SD | false |  | Numeric |  |  |
| Ct_Threshold | false |  | Numeric |  |  |
| Baseline_Start | false |  | Numeric |  |  |
| Baseline_End | false |  | Numeric |  |  |
| Amp_Status | false |  | Text |  |  |
| Cq_Conf | false |  | Numeric |  |  |
| HIGHSD | false |  | Text |  |  |
| Tm1 | false | Celsius | Numeric |  |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| Well |  | Identifies the specific well on the qPCR plate | Not a list |
| Well_Position |  | Coordinates of the well | Not a list |
| Sample_Name |  | Name or ID of the biological or experimental sample | Not a list |
| Target_Name |  | Target Gene | Not a list |
| Reporter |  | Fluorescent dye used to detect amplification | Not a list |
| CT |  | Threshold cycle where fluorescence exceeds background | Not a list |
| Ct_Mean |  | Average CT value from technical replicates | Not a list |
| Ct_SD |  | Standard deviation of CT values among replicates | Not a list |
| Ct_Threshold |  | Fluorescence threshold used to calculate CT | Not a list |
| Baseline_Start |  | Start cycle for baseline signal calculation | Not a list |
| Baseline_End |  | End cycle for baseline signal calculation | Not a list |
| Amp_Status |  | Indicates whether amplification was detected | Amplified, Not amplified |
| Cq_Conf |  | Confidence in quantification cycle (Cq) value | Not a list |
| HIGHSD |  | High standard deviation among technical replicates for a given sample, suggesting inconsistent amplification | Yes, No |
| Tm1 |  | Melting temperature of the first PCR product peak | Not a list |

## Schema SAIDs

**Capture base**: EBroLoNV7McCLVmkJg_rxH2EbZS84Paapit_j_lm3UrS

**Bundle**: EJi38MgR5eN0HalQuMGKg0s7U1j5DrPexRRXApZlUUK1

**Package**: EC0_5f6_6dg4JYkB8r-qPl10daGoN0pOEiIbz5xbUvpx

| Layer | SAID | Type |
| --- | --- | --- |
| entry (eng) | EFot7BDdwZwOVg0ef6LC_eG0i5gH-7gO4pQANjHnu7DF | spec/overlays/entry/1.1 |
| entry_code | EOh9P24N5Meuq22qYOFG2XOSORKt3wYdFCcdVMaPS4Hw | spec/overlays/entry_code/1.1 |
| format | EADAJRHFd4k8kzzjqEE0ie4hCGovN1HVT71JhnWzwEeV | spec/overlays/format/1.1 |
| information (eng) | EP87foRjGB26wfqqJv9LsWCVQVamrKNzu8SAKYUKaiWR | spec/overlays/information/1.1 |
| meta (eng) | EEImLq8eMQ5Tb9rs4UGqzEARut78vxNXYhRekQGroe_v | spec/overlays/meta/1.1 |
| unit | EPJdogWMuzK4Ipfsmyo6KGfwHc08lIY0u8Shn4lepTxq | spec/overlays/unit/1.1 |
| ordering | EEvNJw-g-ryaWI6Mv_hPztTh1a-EkEyNeXclwx9gBK6C | community/overlays/adc/ordering/1.1 |

**Date created**: 2025-05-02 10:56:32

