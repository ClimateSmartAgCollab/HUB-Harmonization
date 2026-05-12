---
layout: default  
title: PeaMAGIC  
parent: peaCE  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: PeaMAGIC  
**Description**: This schema describes a multi\-environment phenotypic and genotypic dataset for a pea (Pisum sativum) MAGIC population comprising 848 inbred lines derived from an 8\-founder crossing scheme. The population was genotyped using skim sequencing (Skim\-seq) to capture genome\-wide variation. Field phenotyping was conducted across multiple environments, including one location with three replicates in 2024 and three locations with two replicates each in 2025. Traits measured include days to flowering, days to maturity, lodging, plant height, seed protein concentration, seed starch concentration, and grain yield (kg/ha). The schema captures structured observations across genotypes, environments, and replicates, along with standardized trait definitions and measurement units.  
**Classification**: RDF401  
**Author**: Kishore Gali  
**Author Email**: kishore.gali@usask.ca  
**ICT Group**: peaCE  
**Schema package SAID**: ENnuVJHyEvhpVyYaUIMqUR31ngXD8iQ1AYuMUo7yWUOS  

[Download Semantic Engine Schema](PeaMAGIC_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| Study_ID | Study Identifier | Unique identifier for the study dataset |
| Environment_ID | Environment Identifier | Identifier for a unique year\-location combination |
| Year | Year | Calendar year in which the field experiment was conducted |
| Location | Location | Name of the field trial location |
| Rep | Replication | Replication number within the experimental design |
| Line_ID | Line identifier | Unique identifier for each inbred MAGIC line |
| Trait_ID | Trait identifier | Identifier for the measured trait (e.g., DTF, DTM) |
| Value | Trait value | Observed or measured value for the specified trait |
| Unit | Measurement unit | Unit of measurement corresponding to the trait value (e.g., days, cm, kg/ha) |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | PeaMAGIC | This schema describes a multi\-environment phenotypic and genotypic dataset for a pea (Pisum sativum) MAGIC population comprising 848 inbred lines derived from an 8\-founder crossing scheme. The population was genotyped using skim sequencing (Skim\-seq) to capture genome\-wide variation. Field phenotyping was conducted across multiple environments, including one location with three replicates in 2024 and three locations with two replicates each in 2025. Traits measured include days to flowering, days to maturity, lodging, plant height, seed protein concentration, seed starch concentration, and grain yield (kg/ha). The schema captures structured observations across genotypes, environments, and replicates, along with standardized trait definitions and measurement units. |

## Selection lists

### English

#### Trait_ID entry codes

| Entry code | Label |
| --- | --- |
| DTF | Days to flowering |
| DTM | Days to maturity |
| LDG | Lodging |
| PH | Plant height |
| PROT | Seed protein concentration |
| STARCH | Seed starch concentration |
| YLD | Grain yield |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| Study_ID | false |  | Text |  |
| Environment_ID | false |  | Text |  |
| Year | false |  | Numeric |  |
| Location | false |  | Text |  |
| Rep | false |  | Numeric |  |
| Line_ID | false |  | Text |  |
| Trait_ID | false |  | Text |  |
| Value | false |  | Numeric |  |
| Unit | false |  | Text |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| Study_ID | Study Identifier | Unique identifier for the study dataset | Not a list |
| Environment_ID | Environment Identifier | Identifier for a unique year\-location combination | Not a list |
| Year | Year | Calendar year in which the field experiment was conducted | Not a list |
| Location | Location | Name of the field trial location | Not a list |
| Rep | Replication | Replication number within the experimental design | Not a list |
| Line_ID | Line identifier | Unique identifier for each inbred MAGIC line | Not a list |
| Trait_ID | Trait identifier | Identifier for the measured trait (e.g., DTF, DTM) | Days to flowering, Days to maturity, Lodging, Plant height, Seed protein concentration, Seed starch concentration, Grain yield |
| Value | Trait value | Observed or measured value for the specified trait | Not a list |
| Unit | Measurement unit | Unit of measurement corresponding to the trait value (e.g., days, cm, kg/ha) | Not a list |

## Schema SAIDs

**Capture base**: EA94LwDFvFKEz4SVc_v1SFEGTR_RGphYmzV5PNEDsWCF

**Bundle**: ELcKSga0p36I9EdxxgkFdozLHQTZ7NWeF-dpciIHSjtg

**Package**: ENnuVJHyEvhpVyYaUIMqUR31ngXD8iQ1AYuMUo7yWUOS

| Layer | SAID | Type |
| --- | --- | --- |
| entry (eng) | ELYFtTt88fUo4bcmVU_45G03f3AsDVlHN57pwmzxEGoO | spec/overlays/entry/1.1 |
| entry_code | EGAG97qirjcir_pxFcm1onooJvkwVrsq4bLwYQrUb-A9 | spec/overlays/entry_code/1.1 |
| information (eng) | EFWouXicU_k06YJtk_67WeCd6wG9ik9mI3Q4xIbveZlv | spec/overlays/information/1.1 |
| label (eng) | EKRVgVwfOOYrE3kUps6miq1ltAnYRqfosaXyCgcsDNz4 | spec/overlays/label/1.1 |
| meta (eng) | EFSgL_EajBH_MkAhkxrDqss0H3lsxIXVQ47ezP60bob- | spec/overlays/meta/1.1 |
| ordering | EGok2ykWR99BmkNlF9-r-SikiigvVRK5LtQF1RVIDnmD | community/overlays/adc/ordering/1.0 |

**Date created**: 2026-05-12 13:08:32

