---
layout: default  
title: Environmental DNA  
parent: Loop  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Environmental DNA  
**Description**: This schema is designed for environmental or agricultural monitoring datasets. It includes several key attributes such as sample identifiers, sample types, geographic coordinates (latitude and longitude), and site descriptions. The schema also defines metadata fields for data validation, such as required entry values, accepted formats, and character encoding. It aims to support structured data collection and ensure interoperability across platforms through consistent attribute naming and semantic annotations.  
**Classification**: RDF209  
**Author**: Paul Célicourt  
**Author Email**: Paul.Celicourt@inrs.ca  
**ICT Group**: Loop  
**Schema package SAID**: EDaePjQtbEwquMTpqkS20fWSEb1T-f5UBM3ytQz2_xCm  

[Download Semantic Engine schema](environmental_DNA.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| sample_name | Sample name | Unique identifier for each sample. Example: \"Soil_2023_SiteA_Rep1\" |
| metadata_version | Metadata version | Version of the metadata schema used. Example: \"1.2\" |
| license | License | Data distribution license. Example: \"CC-BY-4.0\" |
| dataset_doi | Dataset DOI | Persistent identifier for the dataset (Digital Object Identifier). Example: \"10.5281/zenodo.123456\" |
| sampler | Sampler | Person who performed the sampling. Format: \"Firstname Lastname\". Example: \"Marie Dupon\" |
| sampler_affiliation | Sampler affiliation | Sampler\'s institution. Example: \"INRAE UMR EcoSys\" |
| analyst | Analyst | Person who performed the analyses. Example: \"Jean Martin\" |
| analyst_affiliation | Analyst affiliation | Analyst\'s institution. Example: \"CNRS LEM\" |
| data_curator | Data curator | Data quality manager. Example: \"Pierre Lambert\" |
| location_name | Location name | Sampling site description. Example: \"Experimental Field A, Versailles\" |
| latitude | Decimal latitude | WGS84 coordinate (decimal degrees). Example: 48.8053 |
| longitude | Decimal longitude | WGS84 coordinate (decimal degrees). Example: 2.1211 |
| sampling_date | Sampling date | Collection date and time (ISO 8601). Example: \"2023-06-15T14:30:00+02:00\" |
| temporal_resolution | Temporal resolution | Measurement frequency. Example: \"daily\", \"weekly\" |
| experimental_design | Experimental design | Experimental scheme. Example: \"Randomized blocks\" |
| treatment_details | Treatment details | Applied experimental conditions. Example: \"Irrigation at 50% field capacity\" |
| replicates_count | Replicates count | Number of technical replicates. Example: 3 |
| reactor_type | Reactor type | Type of bioreactor. Example: \"Compost\" |
| sample_source_reactor | Sample source | Position relative to reactor. Example: \"inside\" |
| sample_type | Sample type | Material nature. Example: \"soil\", \"water\" |
| sampling_device | Sampling device | Equipment used. Example: \"Sterile corer\" |
| device_serial_number | Device serial number | Equipment unique ID. Example: \"SN-2023-456\" |
| sampled_quantity | Sampled quantity | Weight collected (grams). Example: 50 |
| sampling_depth | Sampling depth | Depth below surface (meters). Example: 0.2 |
| filter_size | Filter size | Filter size for water samples (micrometers). Example: 0.22 |
| filter_type | Filter type | Filter material. Example: \"Polycarbonate\" |
| temperature | Temperature | Average temperature during experiment (°C). Example: 25.5 |
| pH_level | pH | Acidity level. Example: 6.8 |
| electric_conductivity | Conductivity | Substrate conductivity (µS/cm). Example: 1200 |
| soil_water_content | Water content | Soil moisture (%). Example: 22.5 |
| tea_bag_index | Tea Bag Index | Decomposition rate indicator. Example: 0.05 |
| dna_quantity | DNA quantity | Extracted DNA amount (ng). Example: 50 |
| extraction_protocol | Extraction protocol | DNA extraction method. Example: \"DNeasy PowerSoil Kit\" |
| prep_type | Preparation type | Molecular preparation type. Example: \"amplicon\" |
| library | Amplicon/library | Targeted gene region. Example: \"16S rRNA V4-V5\" |
| fwd_probe_name | FWD probe name | Forward primer name. Example: \"515F\" |
| fwd_probe_seq | FWD probe sequence | Forward primer sequence. Example: \"GTGCCAGCMGCCGCGGTAA\" |
| rev_probe_name | REV probe name | Reverse primer name. Example: \"806R\" |
| rev_probe_seq | REV probe sequence | Reverse primer sequence. Example: \"GGACTACHVGGGTWTCTAAT\" |
| number_of_cycles | Number of cycles | PCR cycles. Example: 30 |
| lib_prep_protocol | Library protocol | Library preparation protocol. Example: \"Illumina 16S Metagenomic\" |
| sequencing_instrument | Sequencing instrument | Sequencer model. Example: \"Illumina NovaSeq 6000\" |
| sequencing_mode | Sequencing mode | Read configuration. Example: \"pe\" (paired-end) |
| read_count | Read count | Number of sequences (millions). Example: 10.5 |
| average_seq_quality | Average quality | Mean sequencing quality score (Q-score). Example: 30 |
| trimming_tool | Trimming tool | Read trimming software. Example: \"Trimmomatic v0.39\" |
| merging_tool | Merging tool | Read merging tool for paired-end data. Example: \"FLASH v1.2.11\" |
| unique_seq_creation_tool | Dereplication tool | Dereplication tool. Example: \"VSEARCH v2.18.0\" |
| unique_seq_similarity_threshold | Similarity threshold | Clustering cutoff (%). Example: 97 |
| analysis_method | Analysis method | Sequence variant method. Example: \"asv\" |
| ref_database | Reference database | Taxonomic reference database name and version. Example: \"SILVA 138.1\" |
| taxonomic_assign_tool | Taxonomy tool | Taxonomy classification software. Example: \"QIIME2 q2-feature-classifier\" |
| crop | Crop type | Plant species. Example: \"Zea mays\" |
| larval_dry_diet | Dry diet | Insect dry feed. Example: \"wheat\" |
| larval_wet_diet | Wet diet | Insect wet feed. Example: \"carrot\" |
| fermented_diet | Fermentation | Fermentation conditions. Example: \"Lactic fermentation 48h\" |
| mushroom_species | Mushroom species | Fungal species. Example: \"Pleurotus ostreatus\" |
| larval_protein_content | Larval protein | Insect protein content (mg/g). Example: 200 |
| larval_biomass_yield | Larval biomass | Insect biomass yield (g). Example: 150 |
| mushroom_biomass_yield | Mushroom biomass | Fungal yield (kg/kg substrate). Example: 0.3 |
| mushroom_substrate_conditioning | Substrate prep | Substrate preparation method. Example: \"Pasteurization 70°C\" |
| mushroom_substrate_upcycling | Substrate reuse | Reused substrate fraction (%). Example: 30 |
| crop_yield | Crop yield | Agricultural production (kg/ha). Example: 5000 |
| above_ground_biomass | Aerial biomass | Shoot biomass (g). Example: 25.3 |
| below_ground_biomass | Root biomass | Root biomass (g). Example: 10.2 |
| production | Production | General yield indicator. Example: 85 |
| colonisation_index | Colonization | Mycorrhizal colonization rate in %. Example: 75 |
| contamination_index | Contamination | Contamination level in %. Example: 5 |
| disease_scale | Disease index | Pathogen impact scale (0-5). Example: 2 |
| survival_rate | Survival rate | Plant survival rate (%). Example: 90 |
| root_length | Root length | Total root length (cm). Example: 120 |
| root_forks | Root forks | Root branching points (count). Example: 45 |
| root_tips | Root tips | Root apical points (count). Example: 200 |
| root_class | Root class | Root classification. Example: 3 (1=taproot, 2=fibrous) |
| stomatal_conductance | Stomatal conductance | Gas exchange rate (mmol/m²/s). Example: 0.5 |
| transpiration | Transpiration | Water loss rate (mmol/m²/s). Example: 4.5 |
| leaf_water_potential | Leaf water potential | Plant water status (-MPa). Example: 1.2 |
| photosynthesis | Photosynthesis | CO₂ assimilation rate (µmol/m²/s). Example: 20 |
| plant_height | Plant height | Plant height (cm). Example: 150 |
| carotenoids_content | Carotenoids | Pigment content (mg/g DW). Example: 0.15 |
| chlorophyll_content | Chlorophyll | Pigment content (mg/g DW). Example: 2.5 |
| fruit_quality | Fruit quality | Fruit quality index (1-10 scale). Example: 8 |
| tissue_composition | Tissue comp | Biochemical composition (%). Example: 20 (dry matter) |
| isolated_strains | Isolated strains | Microbial isolates. Example: \"Bacillus subtilis XYZ\" |
| biocontrol_ability | Biocontrol | Pathogen control capacity. Example: \"Fusarium oxysporum inhibition\" |
| crop_growth_promoting_ability | Growth promotion | Plant growth enhancement. Example: \"Siderophore production\" |
| substrate_health_promoting_ability | Substrate health | Substrate improvement. Example: \"PAH degradation\" |
| gas | Gas type | Measured gas type. Example: \"CH₄\" |
| trace_gas_flux | Gas flux | Emission rate (nmol/g/h). Example: 15.2 |
| flux_measurement_method | Flux method | Measurement technique. Example: \"GC\" (Gas Chromatography) |
| method_citation | Method citation | Protocol reference (DOI/standard). Example: \"doi:10.1038/nmeth.1234\" |
| qc_protocol | QC protocol | Quality control procedure. Example: \"16S sequence verification by PCR\" |
| qc_flag | QC flag | Measurement quality indicator. Example: \"pass\", \"suspect\", \"fail\" |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Environmental DNA | This schema is designed for environmental or agricultural monitoring datasets. It includes several key attributes such as sample identifiers, sample types, geographic coordinates (latitude and longitude), and site descriptions. The schema also defines metadata fields for data validation, such as required entry values, accepted formats, and character encoding. It aims to support structured data collection and ensure interoperability across platforms through consistent attribute naming and semantic annotations. |

## Selection lists

### English

#### analysis_method entry codes

| Entry code | Label |
| --- | --- |
| asv | Amplicon Sequence Variant |
| otu | Operational Taxonomic Unit |

#### flux_measurement_method entry codes

| Entry code | Label |
| --- | --- |
| GC | Gas Chromatography |
| FC | Flux Chamber |

#### gas entry codes

| Entry code | Label |
| --- | --- |
| CO2 | CO2 |
| CH4 | CH4 |
| N2O | N2O |

#### larval_dry_diet entry codes

| Entry code | Label |
| --- | --- |
| wheat | wheat |
| prorec | prorec |

#### larval_wet_diet entry codes

| Entry code | Label |
| --- | --- |
| carrot | carrot |
| puree | puree |
| fermented mix | fermented mix |

#### mushroom_species entry codes

| Entry code | Label |
| --- | --- |
| Pleurotus | Pleurotus |
| Ganoderma | Ganoderma |

#### prep_type entry codes

| Entry code | Label |
| --- | --- |
| amplicon | amplicon |
| gdna | gdna |
| rna | rna |

#### qc_flag entry codes

| Entry code | Label |
| --- | --- |
| pass | pass |
| suspect | suspect |
| fail | fail |

#### reactor_type entry codes

| Entry code | Label |
| --- | --- |
| Compost | Compost |
| Mealworm | Mealworm |
| Mushroom | Mushroom |

#### sample_source_reactor entry codes

| Entry code | Label |
| --- | --- |
| Upstream | Upstream |
| inside | inside |
| downstream | downstream |

#### sample_type entry codes

| Entry code | Label |
| --- | --- |
| soil | soil |
| water | water |
| plant | plant |
| reactor | reactor |

#### sequencing_mode entry codes

| Entry code | Label |
| --- | --- |
| pe | Paired-end |
| se | Single-end |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| sample_name | false |  | Text |  |
| metadata_version | false |  | Text |  |
| license | false |  | Text |  |
| dataset_doi | false |  | Text |  |
| sampler | false |  | Text |  |
| sampler_affiliation | false |  | Text |  |
| analyst | false |  | Text |  |
| analyst_affiliation | false |  | Text |  |
| data_curator | false |  | Text |  |
| location_name | false |  | Text |  |
| latitude | false | degree | Numeric |  |
| longitude | false | degree | Numeric |  |
| sampling_date | false |  | DateTime |  |
| temporal_resolution | false | day | Numeric |  |
| experimental_design | false |  | Text |  |
| treatment_details | false |  | Text |  |
| replicates_count | false | count | Numeric |  |
| reactor_type | false |  | Text |  |
| sample_source_reactor | false |  | Text |  |
| sample_type | false |  | Text |  |
| sampling_device | false |  | Text |  |
| device_serial_number | false |  | Text |  |
| sampled_quantity | false | g | Numeric |  |
| sampling_depth | false | m | Numeric |  |
| filter_size | false | µm | Numeric |  |
| filter_type | false |  | Text |  |
| temperature | false | °C | Numeric |  |
| pH_level | false |  | Numeric |  |
| electric_conductivity | false | µS/cm | Numeric |  |
| soil_water_content | false | % | Numeric |  |
| tea_bag_index | false | g/g | Numeric |  |
| dna_quantity | false | ng | Numeric |  |
| extraction_protocol | false |  | Text |  |
| prep_type | false |  | Text |  |
| library | false |  | Text |  |
| fwd_probe_name | false |  | Text |  |
| fwd_probe_seq | false |  | Text |  |
| rev_probe_name | false |  | Text |  |
| rev_probe_seq | false |  | Text |  |
| number_of_cycles | false | count | Numeric |  |
| lib_prep_protocol | false |  | Text |  |
| sequencing_instrument | false |  | Text |  |
| sequencing_mode | false |  | Text |  |
| read_count | false | count | Numeric |  |
| average_seq_quality | false |  | Numeric |  |
| trimming_tool | false |  | Text |  |
| merging_tool | false |  | Text |  |
| unique_seq_creation_tool | false |  | Text |  |
| unique_seq_similarity_threshold | false | % | Numeric |  |
| analysis_method | false |  | Text |  |
| ref_database | false |  | Text |  |
| taxonomic_assign_tool | false |  | Text |  |
| crop | false |  | Text |  |
| larval_dry_diet | false |  | Text |  |
| larval_wet_diet | false |  | Text |  |
| fermented_diet | false |  | Text |  |
| mushroom_species | false |  | Text |  |
| larval_protein_content | false | mg/g | Numeric |  |
| larval_biomass_yield | false | g | Numeric |  |
| mushroom_biomass_yield | false | kg/kg | Numeric |  |
| mushroom_substrate_conditioning | false |  | Text |  |
| mushroom_substrate_upcycling | false | % | Numeric |  |
| crop_yield | false | kg/ha | Numeric |  |
| above_ground_biomass | false | g | Numeric |  |
| below_ground_biomass | false | g | Numeric |  |
| production | false |  | Numeric |  |
| colonisation_index | false | % | Numeric |  |
| contamination_index | false | % | Numeric |  |
| disease_scale | false |  | Numeric |  |
| survival_rate | false | % | Numeric |  |
| root_length | false | cm | Numeric |  |
| root_forks | false | count | Numeric |  |
| root_tips | false | count | Numeric |  |
| root_class | false | count | Numeric |  |
| stomatal_conductance | false | mmol/m²/s | Numeric |  |
| transpiration | false | mmol/m²/s | Numeric |  |
| leaf_water_potential | false | mmol/m²/s | Numeric |  |
| photosynthesis | false | µmol/m²/s | Numeric |  |
| plant_height | false | cm | Numeric |  |
| carotenoids_content | false | mg/g | Numeric |  |
| chlorophyll_content | false | mg/g | Numeric |  |
| fruit_quality | false |  | Numeric |  |
| tissue_composition | false | % | Numeric |  |
| isolated_strains | false |  | Text |  |
| biocontrol_ability | false |  | Text |  |
| crop_growth_promoting_ability | false |  | Text |  |
| substrate_health_promoting_ability | false |  | Text |  |
| gas | false |  | Text |  |
| trace_gas_flux | false | nmol/g/h | Numeric |  |
| flux_measurement_method | false |  | Text |  |
| method_citation | false |  | Text |  |
| qc_protocol | false |  | Text |  |
| qc_flag | false |  | Text |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| sample_name | Sample name | Unique identifier for each sample. Example: \"Soil_2023_SiteA_Rep1\" | Not a list |
| metadata_version | Metadata version | Version of the metadata schema used. Example: \"1.2\" | Not a list |
| license | License | Data distribution license. Example: \"CC-BY-4.0\" | Not a list |
| dataset_doi | Dataset DOI | Persistent identifier for the dataset (Digital Object Identifier). Example: \"10.5281/zenodo.123456\" | Not a list |
| sampler | Sampler | Person who performed the sampling. Format: \"Firstname Lastname\". Example: \"Marie Dupon\" | Not a list |
| sampler_affiliation | Sampler affiliation | Sampler\'s institution. Example: \"INRAE UMR EcoSys\" | Not a list |
| analyst | Analyst | Person who performed the analyses. Example: \"Jean Martin\" | Not a list |
| analyst_affiliation | Analyst affiliation | Analyst\'s institution. Example: \"CNRS LEM\" | Not a list |
| data_curator | Data curator | Data quality manager. Example: \"Pierre Lambert\" | Not a list |
| location_name | Location name | Sampling site description. Example: \"Experimental Field A, Versailles\" | Not a list |
| latitude | Decimal latitude | WGS84 coordinate (decimal degrees). Example: 48.8053 | Not a list |
| longitude | Decimal longitude | WGS84 coordinate (decimal degrees). Example: 2.1211 | Not a list |
| sampling_date | Sampling date | Collection date and time (ISO 8601). Example: \"2023-06-15T14:30:00+02:00\" | Not a list |
| temporal_resolution | Temporal resolution | Measurement frequency. Example: \"daily\", \"weekly\" | Not a list |
| experimental_design | Experimental design | Experimental scheme. Example: \"Randomized blocks\" | Not a list |
| treatment_details | Treatment details | Applied experimental conditions. Example: \"Irrigation at 50% field capacity\" | Not a list |
| replicates_count | Replicates count | Number of technical replicates. Example: 3 | Not a list |
| reactor_type | Reactor type | Type of bioreactor. Example: \"Compost\" | Compost, Mealworm, Mushroom |
| sample_source_reactor | Sample source | Position relative to reactor. Example: \"inside\" | Upstream, inside, downstream |
| sample_type | Sample type | Material nature. Example: \"soil\", \"water\" | soil, water, plant, reactor |
| sampling_device | Sampling device | Equipment used. Example: \"Sterile corer\" | Not a list |
| device_serial_number | Device serial number | Equipment unique ID. Example: \"SN-2023-456\" | Not a list |
| sampled_quantity | Sampled quantity | Weight collected (grams). Example: 50 | Not a list |
| sampling_depth | Sampling depth | Depth below surface (meters). Example: 0.2 | Not a list |
| filter_size | Filter size | Filter size for water samples (micrometers). Example: 0.22 | Not a list |
| filter_type | Filter type | Filter material. Example: \"Polycarbonate\" | Not a list |
| temperature | Temperature | Average temperature during experiment (°C). Example: 25.5 | Not a list |
| pH_level | pH | Acidity level. Example: 6.8 | Not a list |
| electric_conductivity | Conductivity | Substrate conductivity (µS/cm). Example: 1200 | Not a list |
| soil_water_content | Water content | Soil moisture (%). Example: 22.5 | Not a list |
| tea_bag_index | Tea Bag Index | Decomposition rate indicator. Example: 0.05 | Not a list |
| dna_quantity | DNA quantity | Extracted DNA amount (ng). Example: 50 | Not a list |
| extraction_protocol | Extraction protocol | DNA extraction method. Example: \"DNeasy PowerSoil Kit\" | Not a list |
| prep_type | Preparation type | Molecular preparation type. Example: \"amplicon\" | amplicon, gdna, rna |
| library | Amplicon/library | Targeted gene region. Example: \"16S rRNA V4-V5\" | Not a list |
| fwd_probe_name | FWD probe name | Forward primer name. Example: \"515F\" | Not a list |
| fwd_probe_seq | FWD probe sequence | Forward primer sequence. Example: \"GTGCCAGCMGCCGCGGTAA\" | Not a list |
| rev_probe_name | REV probe name | Reverse primer name. Example: \"806R\" | Not a list |
| rev_probe_seq | REV probe sequence | Reverse primer sequence. Example: \"GGACTACHVGGGTWTCTAAT\" | Not a list |
| number_of_cycles | Number of cycles | PCR cycles. Example: 30 | Not a list |
| lib_prep_protocol | Library protocol | Library preparation protocol. Example: \"Illumina 16S Metagenomic\" | Not a list |
| sequencing_instrument | Sequencing instrument | Sequencer model. Example: \"Illumina NovaSeq 6000\" | Not a list |
| sequencing_mode | Sequencing mode | Read configuration. Example: \"pe\" (paired-end) | Paired-end, Single-end |
| read_count | Read count | Number of sequences (millions). Example: 10.5 | Not a list |
| average_seq_quality | Average quality | Mean sequencing quality score (Q-score). Example: 30 | Not a list |
| trimming_tool | Trimming tool | Read trimming software. Example: \"Trimmomatic v0.39\" | Not a list |
| merging_tool | Merging tool | Read merging tool for paired-end data. Example: \"FLASH v1.2.11\" | Not a list |
| unique_seq_creation_tool | Dereplication tool | Dereplication tool. Example: \"VSEARCH v2.18.0\" | Not a list |
| unique_seq_similarity_threshold | Similarity threshold | Clustering cutoff (%). Example: 97 | Not a list |
| analysis_method | Analysis method | Sequence variant method. Example: \"asv\" | Amplicon Sequence Variant, Operational Taxonomic Unit |
| ref_database | Reference database | Taxonomic reference database name and version. Example: \"SILVA 138.1\" | Not a list |
| taxonomic_assign_tool | Taxonomy tool | Taxonomy classification software. Example: \"QIIME2 q2-feature-classifier\" | Not a list |
| crop | Crop type | Plant species. Example: \"Zea mays\" | Not a list |
| larval_dry_diet | Dry diet | Insect dry feed. Example: \"wheat\" | wheat, prorec |
| larval_wet_diet | Wet diet | Insect wet feed. Example: \"carrot\" | carrot, puree, fermented mix |
| fermented_diet | Fermentation | Fermentation conditions. Example: \"Lactic fermentation 48h\" | Not a list |
| mushroom_species | Mushroom species | Fungal species. Example: \"Pleurotus ostreatus\" | Pleurotus, Ganoderma |
| larval_protein_content | Larval protein | Insect protein content (mg/g). Example: 200 | Not a list |
| larval_biomass_yield | Larval biomass | Insect biomass yield (g). Example: 150 | Not a list |
| mushroom_biomass_yield | Mushroom biomass | Fungal yield (kg/kg substrate). Example: 0.3 | Not a list |
| mushroom_substrate_conditioning | Substrate prep | Substrate preparation method. Example: \"Pasteurization 70°C\" | Not a list |
| mushroom_substrate_upcycling | Substrate reuse | Reused substrate fraction (%). Example: 30 | Not a list |
| crop_yield | Crop yield | Agricultural production (kg/ha). Example: 5000 | Not a list |
| above_ground_biomass | Aerial biomass | Shoot biomass (g). Example: 25.3 | Not a list |
| below_ground_biomass | Root biomass | Root biomass (g). Example: 10.2 | Not a list |
| production | Production | General yield indicator. Example: 85 | Not a list |
| colonisation_index | Colonization | Mycorrhizal colonization rate in %. Example: 75 | Not a list |
| contamination_index | Contamination | Contamination level in %. Example: 5 | Not a list |
| disease_scale | Disease index | Pathogen impact scale (0-5). Example: 2 | Not a list |
| survival_rate | Survival rate | Plant survival rate (%). Example: 90 | Not a list |
| root_length | Root length | Total root length (cm). Example: 120 | Not a list |
| root_forks | Root forks | Root branching points (count). Example: 45 | Not a list |
| root_tips | Root tips | Root apical points (count). Example: 200 | Not a list |
| root_class | Root class | Root classification. Example: 3 (1=taproot, 2=fibrous) | Not a list |
| stomatal_conductance | Stomatal conductance | Gas exchange rate (mmol/m²/s). Example: 0.5 | Not a list |
| transpiration | Transpiration | Water loss rate (mmol/m²/s). Example: 4.5 | Not a list |
| leaf_water_potential | Leaf water potential | Plant water status (-MPa). Example: 1.2 | Not a list |
| photosynthesis | Photosynthesis | CO₂ assimilation rate (µmol/m²/s). Example: 20 | Not a list |
| plant_height | Plant height | Plant height (cm). Example: 150 | Not a list |
| carotenoids_content | Carotenoids | Pigment content (mg/g DW). Example: 0.15 | Not a list |
| chlorophyll_content | Chlorophyll | Pigment content (mg/g DW). Example: 2.5 | Not a list |
| fruit_quality | Fruit quality | Fruit quality index (1-10 scale). Example: 8 | Not a list |
| tissue_composition | Tissue comp | Biochemical composition (%). Example: 20 (dry matter) | Not a list |
| isolated_strains | Isolated strains | Microbial isolates. Example: \"Bacillus subtilis XYZ\" | Not a list |
| biocontrol_ability | Biocontrol | Pathogen control capacity. Example: \"Fusarium oxysporum inhibition\" | Not a list |
| crop_growth_promoting_ability | Growth promotion | Plant growth enhancement. Example: \"Siderophore production\" | Not a list |
| substrate_health_promoting_ability | Substrate health | Substrate improvement. Example: \"PAH degradation\" | Not a list |
| gas | Gas type | Measured gas type. Example: \"CH₄\" | CO2, CH4, N2O |
| trace_gas_flux | Gas flux | Emission rate (nmol/g/h). Example: 15.2 | Not a list |
| flux_measurement_method | Flux method | Measurement technique. Example: \"GC\" (Gas Chromatography) | Gas Chromatography, Flux Chamber |
| method_citation | Method citation | Protocol reference (DOI/standard). Example: \"doi:10.1038/nmeth.1234\" | Not a list |
| qc_protocol | QC protocol | Quality control procedure. Example: \"16S sequence verification by PCR\" | Not a list |
| qc_flag | QC flag | Measurement quality indicator. Example: \"pass\", \"suspect\", \"fail\" | pass, suspect, fail |

## Schema SAIDs

**Capture base**: EAqfPkogZ3xjFlm8dK3ekg8U8QdmPhS6LzYl2H0QRRex

**Bundle**: EJ-6Qrj6jM_yLvCOPAYKfaakVzlzw5MG2Cansxc6Kn8X

**Package**: EDaePjQtbEwquMTpqkS20fWSEb1T-f5UBM3ytQz2_xCm

| Layer | SAID | Type |
| --- | --- | --- |
| entry (eng) | EEe684KNilXt00HeAl8BTen2EKMwFiTX0QX8fPM_MdXu | spec/overlays/entry/1.1 |
| entry_code | EH977_mFs85DhHCks80zOiRLOV0tM1Qas-yVWUcB7YRf | spec/overlays/entry_code/1.1 |
| information (eng) | EL6U2hCn0CPFcXJzSEZAeg6fbNV4MLJt2t7VgQx4LAhq | spec/overlays/information/1.1 |
| label (eng) | EFICrNPiNtw7v82uq47eCzpYFv8-0hOepD1xFDUZu-s4 | spec/overlays/label/1.1 |
| meta (eng) | EP7zwRJNoMGegkfiZzmc1Vuw7CeZ-UglmrkkNviT5iOQ | spec/overlays/meta/1.1 |
| unit | EH1zVzZ9nLSF6kzw2YSrP7evDlU1VISSBje5bZCyvDXB | spec/overlays/unit/1.1 |
| ordering | EGy2_xJ8-olIruCrd8P293a4_gPOAKivikjMrq5SHWNp | community/overlays/adc/ordering/1.1 |

**Date created**: 2025-08-14 14:31:54

