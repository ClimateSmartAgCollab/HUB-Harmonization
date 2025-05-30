---
layout: default  
title: PeaCE  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: PeaCE  
**Description**: CLIMATE SMART AGRICULTURE AND FOOD SYSTEMS – INTERDISCIPLINARY CHALLENGE TEAMS (CSAFS-ICT) APPLICATION FORM  
**Classification**: RDF401  
**Schema package SAID**: PLACEHOLDER_PACKAGE_DIGEST_ProjectPeaCE  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| accession_id | Accession ID | Unique identifier for each germplasm accession |
| species | Species | Species of the germplasm accession |
| subspecies | Subspecies | Subspecies of the germplasm accession |
| origin | Origin | Geographical origin of the germplasm accession |
| morphological_trait | Morphological Trait | Morphological trait measured for the germplasm accession |
| agronomic_trait | Agronomic Trait | Agronomic trait measured for the germplasm accession |
| sequencing_platform | Sequencing Platform | Sequencing platform used for genotyping |
| variant_calls | Variant Calls | Variant calls generated from sequencing data |
| geographic_location | Geographic Location | Geographic location of the germplasm accession |
| climate_conditions | Climate Conditions | Climate conditions at the origin of the germplasm accession |
| pathogen_strain | Pathogen Strain | Pathogen strain used for disease resistance screening |
| inoculum_concentration | Inoculum Concentration | Concentration of the pathogen inoculum |
| disease_severity_score | Disease Severity Score | Disease severity score on a scale of 1-5 |
| n2o_flux | N2O Flux | Nitrous oxide flux measurement |
| ch4_flux | CH4 Flux | Methane flux measurement |
| co2_flux | CO2 Flux | Carbon dioxide flux measurement |
| soil_temperature | Soil Temperature | Soil temperature measurement |
| soil_moisture | Soil Moisture | Soil moisture measurement |
| soil_nutrient_content | Soil Nutrient Content | Soil nutrient content measurement |
| crop_yield | Crop Yield | Crop yield measurement |
| fertilizer_application_rate | Fertilizer Application Rate | Fertilizer application rate |
| parental_line | Parental Line | Parental line used in the breeding program |
| generation | Generation | Generation of the breeding population |
| yield | Yield | Yield measurement for the breeding population |
| protein_content | Protein Content | Protein content measurement for the breeding population |
| maturity | Maturity | Maturity measurement for the breeding population |
| marker_data | Marker Data | Marker data generated for the breeding population |
| qtl_mapping | QTL Mapping | QTL mapping data for the breeding population |
| field_trial_location | Field Trial Location | Location of the field trial for the breeding population |
| weather_conditions | Weather Conditions | Weather conditions during the field trial |
| gene_id | Gene ID | Unique identifier for each gene |
| functional_description | Functional Description | Functional description of the gene |
| rna_seq_data | RNA-Seq Data | RNA-seq data for gene expression analysis |
| qpcr_data | qPCR Data | qPCR data for gene expression analysis |
| proteomics_data | Proteomics Data | Proteomics data for protein analysis |
| protein_interaction_data | Protein Interaction Data | Protein-protein interaction data |
| metabolite_profile | Metabolite Profile | Metabolite profile data |
| pathway_analysis | Pathway Analysis | Pathway analysis data |
| participant_id | Participant ID | Unique identifier for each participant |
| demographic_data | Demographic Data | Demographic data of the participant |
| survey_response | Survey Response | Survey response data |
| interview_transcript | Interview Transcript | Interview transcript data |
| interview_coding | Interview Coding | Interview coding data |
| cost_benefit_analysis | Cost-Benefit Analysis | Cost-benefit analysis data |
| market_analysis | Market Analysis | Market analysis data |
| regulations | Regulations | Regulations data |
| stakeholder_analysis | Stakeholder Analysis | Stakeholder analysis data |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | PeaCE | CLIMATE SMART AGRICULTURE AND FOOD SYSTEMS – INTERDISCIPLINARY CHALLENGE TEAMS (CSAFS-ICT) APPLICATION FORM |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| accession_id | false |  | Text |  |
| species | false |  | Text |  |
| subspecies | false |  | Text |  |
| origin | false |  | Text |  |
| morphological_trait | false |  | Text |  |
| agronomic_trait | false |  | Text |  |
| sequencing_platform | false |  | Text |  |
| variant_calls | false |  | File |  |
| geographic_location | false |  | Text |  |
| climate_conditions | false |  | Text |  |
| pathogen_strain | false |  | Text |  |
| inoculum_concentration | false | cfu/ml | Numeric |  |
| disease_severity_score | false | - | Numeric |  |
| n2o_flux | false | g N/ha/day | Numeric |  |
| ch4_flux | false | g C/ha/day | Numeric |  |
| co2_flux | false | g C/ha/day | Numeric |  |
| soil_temperature | false | °C | Numeric |  |
| soil_moisture | false | % | Numeric |  |
| soil_nutrient_content | false | varies | Numeric |  |
| crop_yield | false | kg/ha | Numeric |  |
| fertilizer_application_rate | false | kg/ha | Numeric |  |
| parental_line | false |  | Text |  |
| generation | false |  | Text |  |
| yield | false | kg/ha | Numeric |  |
| protein_content | false | % | Numeric |  |
| maturity | false | days | Numeric |  |
| marker_data | false |  | File |  |
| qtl_mapping | false |  | File |  |
| field_trial_location | false |  | Text |  |
| weather_conditions | false |  | Text |  |
| gene_id | false |  | Text |  |
| functional_description | false |  | Text |  |
| rna_seq_data | false |  | File |  |
| qpcr_data | false |  | File |  |
| proteomics_data | false |  | File |  |
| protein_interaction_data | false |  | File |  |
| metabolite_profile | false |  | File |  |
| pathway_analysis | false |  | File |  |
| participant_id | true |  | Text |  |
| demographic_data | true |  | Text |  |
| survey_response | true |  | Text |  |
| interview_transcript | true |  | Text |  |
| interview_coding | true |  | Text |  |
| cost_benefit_analysis | false |  | File |  |
| market_analysis | false |  | File |  |
| regulations | false |  | File |  |
| stakeholder_analysis | false |  | File |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| accession_id | Accession ID | Unique identifier for each germplasm accession | Not a list |
| species | Species | Species of the germplasm accession | Not a list |
| subspecies | Subspecies | Subspecies of the germplasm accession | Not a list |
| origin | Origin | Geographical origin of the germplasm accession | Not a list |
| morphological_trait | Morphological Trait | Morphological trait measured for the germplasm accession | Not a list |
| agronomic_trait | Agronomic Trait | Agronomic trait measured for the germplasm accession | Not a list |
| sequencing_platform | Sequencing Platform | Sequencing platform used for genotyping | Not a list |
| variant_calls | Variant Calls | Variant calls generated from sequencing data | Not a list |
| geographic_location | Geographic Location | Geographic location of the germplasm accession | Not a list |
| climate_conditions | Climate Conditions | Climate conditions at the origin of the germplasm accession | Not a list |
| pathogen_strain | Pathogen Strain | Pathogen strain used for disease resistance screening | Not a list |
| inoculum_concentration | Inoculum Concentration | Concentration of the pathogen inoculum | Not a list |
| disease_severity_score | Disease Severity Score | Disease severity score on a scale of 1-5 | Not a list |
| n2o_flux | N2O Flux | Nitrous oxide flux measurement | Not a list |
| ch4_flux | CH4 Flux | Methane flux measurement | Not a list |
| co2_flux | CO2 Flux | Carbon dioxide flux measurement | Not a list |
| soil_temperature | Soil Temperature | Soil temperature measurement | Not a list |
| soil_moisture | Soil Moisture | Soil moisture measurement | Not a list |
| soil_nutrient_content | Soil Nutrient Content | Soil nutrient content measurement | Not a list |
| crop_yield | Crop Yield | Crop yield measurement | Not a list |
| fertilizer_application_rate | Fertilizer Application Rate | Fertilizer application rate | Not a list |
| parental_line | Parental Line | Parental line used in the breeding program | Not a list |
| generation | Generation | Generation of the breeding population | Not a list |
| yield | Yield | Yield measurement for the breeding population | Not a list |
| protein_content | Protein Content | Protein content measurement for the breeding population | Not a list |
| maturity | Maturity | Maturity measurement for the breeding population | Not a list |
| marker_data | Marker Data | Marker data generated for the breeding population | Not a list |
| qtl_mapping | QTL Mapping | QTL mapping data for the breeding population | Not a list |
| field_trial_location | Field Trial Location | Location of the field trial for the breeding population | Not a list |
| weather_conditions | Weather Conditions | Weather conditions during the field trial | Not a list |
| gene_id | Gene ID | Unique identifier for each gene | Not a list |
| functional_description | Functional Description | Functional description of the gene | Not a list |
| rna_seq_data | RNA-Seq Data | RNA-seq data for gene expression analysis | Not a list |
| qpcr_data | qPCR Data | qPCR data for gene expression analysis | Not a list |
| proteomics_data | Proteomics Data | Proteomics data for protein analysis | Not a list |
| protein_interaction_data | Protein Interaction Data | Protein-protein interaction data | Not a list |
| metabolite_profile | Metabolite Profile | Metabolite profile data | Not a list |
| pathway_analysis | Pathway Analysis | Pathway analysis data | Not a list |
| participant_id | Participant ID | Unique identifier for each participant | Not a list |
| demographic_data | Demographic Data | Demographic data of the participant | Not a list |
| survey_response | Survey Response | Survey response data | Not a list |
| interview_transcript | Interview Transcript | Interview transcript data | Not a list |
| interview_coding | Interview Coding | Interview coding data | Not a list |
| cost_benefit_analysis | Cost-Benefit Analysis | Cost-benefit analysis data | Not a list |
| market_analysis | Market Analysis | Market analysis data | Not a list |
| regulations | Regulations | Regulations data | Not a list |
| stakeholder_analysis | Stakeholder Analysis | Stakeholder analysis data | Not a list |

## Schema SAIDs

**Capture base**: CB_DIGEST_ProjectPeaCE_Main

**Bundle**: PLACEHOLDER_BUNDLE_DIGEST_ProjectPeaCE

**Package**: PLACEHOLDER_PACKAGE_DIGEST_ProjectPeaCE

| Layer | SAID | Type |
| --- | --- | --- |
| information (eng) | INFO_OVERLAY_DIGEST_ProjectPeaCE_ENG_1 | spec/overlays/information/1.1 |
| label (eng) | LABEL_OVERLAY_DIGEST_ProjectPeaCE_ENG_1 | spec/overlays/label/1.1 |
| meta (eng) | META_OVERLAY_DIGEST_ProjectPeaCE_PeaDiversity | spec/overlays/meta/1.1 |
| unit | UNIT_OVERLAY_DIGEST_ProjectPeaCE_1 | spec/overlays/unit/1.1 |

**Date created**: 2025-05-30 14:56:43

