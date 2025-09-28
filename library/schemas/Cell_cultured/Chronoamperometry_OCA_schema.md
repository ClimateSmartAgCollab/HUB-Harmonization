---
layout: default  
title: Chronoamperometry for Lactate Conversion  
parent: Cell Cultured Meat  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Chronoamperometry for Lactate Conversion  
**Description**: This schema will have a table of current and time. On plotting this, we can identify any reduction in analyte concentration from the gradual decline(here, Lactate). Required Time periods for conversion can be input and current would be read correspondingly by the instrument.  
**Classification**: RDF203  
**Author**: Sruthi Sasidharan  
**Author Email**: sasidhas@mcmaster.ca  
**ICT Group**: Cell Cultured Meat  
**Schema package SAID**: ELGQaK8J6SjxqLDaLWq76J6csBjxqjDp_LHLDV4PRMWK 

[Download schema](Chronoamperometry_OCA_package.json)

[Download LinkML Schema](Chronoamperometry_LinkML/schema.json) ([yaml](Chronoamperometry_LinkML/schema.yaml); table view: [fields](https://github.com/ClimateSmartAgCollab/HUB-Harmonization/blob/main/library/schemas/Cell_cultured/Chronoamperometry_LinkML/schema_slots.tsv), [picklists](https://github.com/ClimateSmartAgCollab/HUB-Harmonization/blob/main/library/schemas/Cell_cultured/Chronoamperometry_LinkML/schema_enums.tsv))

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| Current |  | Corresponding current read by the instrument |
| Time |  | Time needed for Lactate conversion which can be varied by the user |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Chronoamperometry for Lactate Conversion | This schema will have a table of current and time. On plotting this, we can identify any reduction in analyte concentration from the gradual decline(here, Lactate). Required Time periods for conversion can be input and current would be read correspondingly by the instrument. |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| Current | false | microamperes | Numeric |  |
| Time | false | seconds | DateTime |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| Current |  | Corresponding current read by the instrument | Not a list |
| Time |  | Time needed for Lactate conversion which can be varied by the user | Not a list |

## Schema SAIDs

**Capture base**: EPHCANwzvKDad7_ktHSy40jVdm_21yO6ON3KKJJJZqYd

**Bundle**: EL29DPEGAKZmFcxjGc5KlnXmql610SEhfBQhz7tiWZ37

**Package**: ELGQaK8J6SjxqLDaLWq76J6csBjxqjDp_LHLDV4PRMWK

| Layer | SAID | Type |
| --- | --- | --- |
| information (eng) | EDWrtFTh1e4saYYUYZ9Ip744PMjJGjK8-NUt6CTan1Sb | spec/overlays/information/1.1 |
| meta (eng) | EKImBxX3wm7XGqkVHnzEXmTasCZO2nbFPYYFZQLZ001J | spec/overlays/meta/1.1 |
| unit | EKpSHROTYL-3ihhLBoQtjDit4atPpeSbg9nUf-qYokJK | spec/overlays/unit/1.1 |
| ordering | EMoI4h5V1JxWCeSvW7IDzGSBAJk4GJu8ErcFOxQ5Se3u | community/overlays/adc/ordering/1.1 |

**Date created**: 2025-05-02 15:27:03

