
BEGIN_REFERENCE_MATERIAL
******************************************************************
OCA_READ_ME/1.0
This is a human-readable schema, based on the OCA schema standard.

Reference for Overlays Capture Architecture (OCA):
https://doi.org/10.5281/zenodo.7707467

Reference for OCA_READ_ME/1.0:
https://github.com/agrifooddatacanada/OCA_README

A schema describes details about a dataset.
In OCA, a schema consists of a capture_base which documents the attributes and their most basic features.
A schema may also contain overlays which add details to the capture_base.
For each overlay and capture_base, a hash of their original contents has been calculated and is reported here as the SAID value.

This README format documents the capture_base and overlays that were associated together in a single OCA Bundle.
OCA_MANIFEST lists all components of the OCA Bundle.
For the OCA_BUNDLE, each section between rows of ****'s contains the details of one "layer type/version" of the OCA Bundle.
******************************************************************
END_REFERENCE_MATERIAL

BEGIN_OCA_MANIFEST
******************************************************************
Package SAID/digest: EGRRH-4qD2zNCWynyCefq0sEmZBBsamMRwBeeJsbDjAm
Bundle SAID/digest: EPehSCxbQ4qcVhEsLlGPYwzpKBsM3FLA9FT9WzRpyO4U

spec/capture_base/1.1 SAID/digest: "ELyfXt8wfuLYql3IABdjsuwtgnRaobepNGsbWbPTmqMl"
spec/overlays/meta/1.1 (eng) SAID/digest: "EA7YWtUuOKVoGBgPprk9dKWG0zCMhnwZEplV5QKePqM7"
spec/overlays/label/1.1 (eng) SAID/digest: "EJCbsTATovspHJvzf15HeCaIDbtsfj_F_BK4EFnF-Vnh"
spec/overlays/information/1.1 (eng) SAID/digest: "ELZyAXM349E1ETt9JYCuyOE3dqcxbXjiyANyNTNmyxcp"
spec/overlays/unit/1.1 SAID/digest: "ELyhPOjMVLihqIO7K4t7xtzvrIlmUV5d8Fyhm1siHaex"

community/overlays/adc/ordering/1.1 SAID/digest: "EPjBJG8SYWTbp8LVYYOnt2QgsnnP6KRhuUcbX0-IK_an"
community/overlays/adc/sensitive/1.1 SAID/digest: "EBz1mYKnUH4sgyoyvsj60VGDsHo2VegPBoFh9Cbomlw4"
******************************************************************
END_OCA_MANIFEST

BEGIN_OCA_BUNDLE
******************************************************************
Layer name: spec/capture_base/1.1
SAID/digest: ELyfXt8wfuLYql3IABdjsuwtgnRaobepNGsbWbPTmqMl
Classification: RDF401

Schema attributes: data type
    accession_id: Text
    species: Text
    subspecies: Text
    origin: Text
    morphological_trait: Text
    agronomic_trait: Text
    sequencing_platform: Text
    variant_calls: Text
    geographic_location: Text
    climate_conditions: Text
    pathogen_strain: Text
    inoculum_concentration: Numeric
    disease_severity_score: Numeric
    n2o_flux: Numeric
    ch4_flux: Numeric
    co2_flux: Numeric
    soil_temperature: Numeric
    soil_moisture: Numeric
    soil_nutrient_content: Numeric
    crop_yield: Numeric
    fertilizer_application_rate: Numeric
    parental_line: Text
    generation: Text
    yield: Numeric
    protein_content: Numeric
    maturity: Numeric
    marker_data: Text
    qtl_mapping: Text
    field_trial_location: Text
    weather_conditions: Text
    gene_id: Text
    functional_description: Text
    rna_seq_data: Text
    qpcr_data: Text
    proteomics_data: Text
    protein_interaction_data: Text
    metabolite_profile: Text
    pathway_analysis: Text
    participant_id: Text
    demographic_data: Text
    survey_response: Text
    interview_transcript: Text
    interview_coding: Text
    cost_benefit_analysis: Text
    market_analysis: Text
    regulations: Text
    stakeholder_analysis: Text

******************************************************************
Layer name: spec/overlays/meta/1.1
SAID/digest: EA7YWtUuOKVoGBgPprk9dKWG0zCMhnwZEplV5QKePqM7
Language: eng
Description: CLIMATE SMART AGRICULTURE AND FOOD SYSTEMS – INTERDISCIPLINARY CHALLENGE TEAMS (CSAFS-ICT) APPLICATION FORM

******************************************************************
Layer name: spec/overlays/label/1.1
SAID/digest: EJCbsTATovspHJvzf15HeCaIDbtsfj_F_BK4EFnF-Vnh
Language: eng
Schema attributes: spec/overlays/label/1.1
    accession_id: Accession ID
    species: Species
    subspecies: Subspecies
    origin: Origin
    morphological_trait: Morphological Trait
    agronomic_trait: Agronomic Trait
    sequencing_platform: Sequencing Platform
    variant_calls: Variant Calls
    geographic_location: Geographic Location
    climate_conditions: Climate Conditions
    pathogen_strain: Pathogen Strain
    inoculum_concentration: Inoculum Concentration
    disease_severity_score: Disease Severity Score
    n2o_flux: N2O Flux
    ch4_flux: CH4 Flux
    co2_flux: CO2 Flux
    soil_temperature: Soil Temperature
    soil_moisture: Soil Moisture
    soil_nutrient_content: Soil Nutrient Content
    crop_yield: Crop Yield
    fertilizer_application_rate: Fertilizer Application Rate
    parental_line: Parental Line
    generation: Generation
    yield: Yield
    protein_content: Protein Content
    maturity: Maturity
    marker_data: Marker Data
    qtl_mapping: QTL Mapping
    field_trial_location: Field Trial Location
    weather_conditions: Weather Conditions
    gene_id: Gene ID
    functional_description: Functional Description
    rna_seq_data: RNA-Seq Data
    qpcr_data: qPCR Data
    proteomics_data: Proteomics Data
    protein_interaction_data: Protein Interaction Data
    metabolite_profile: Metabolite Profile
    pathway_analysis: Pathway Analysis
    participant_id: Participant ID
    demographic_data: Demographic Data
    survey_response: Survey Response
    interview_transcript: Interview Transcript
    interview_coding: Interview Coding
    cost_benefit_analysis: Cost-Benefit Analysis
    market_analysis: Market Analysis
    regulations: Regulations
    stakeholder_analysis: Stakeholder Analysis

******************************************************************
Layer name: spec/overlays/information/1.1
SAID/digest: ELZyAXM349E1ETt9JYCuyOE3dqcxbXjiyANyNTNmyxcp
Language: eng
Schema attributes: spec/overlays/information/1.1
    accession_id: Unique identifier for each germplasm accession
    species: Species of the germplasm accession
    subspecies: Subspecies of the germplasm accession
    origin: Geographical origin of the germplasm accession
    morphological_trait: Morphological trait measured for the germplasm accession
    agronomic_trait: Agronomic trait measured for the germplasm accession
    sequencing_platform: Sequencing platform used for genotyping
    variant_calls: Variant calls generated from sequencing data
    geographic_location: Geographic location of the germplasm accession
    climate_conditions: Climate conditions at the origin of the germplasm accession
    pathogen_strain: Pathogen strain used for disease resistance screening
    inoculum_concentration: Concentration of the pathogen inoculum
    disease_severity_score: Disease severity score on a scale of 1-5
    n2o_flux: Nitrous oxide flux measurement
    ch4_flux: Methane flux measurement
    co2_flux: Carbon dioxide flux measurement
    soil_temperature: Soil temperature measurement
    soil_moisture: Soil moisture measurement
    soil_nutrient_content: Soil nutrient content measurement
    crop_yield: Crop yield measurement
    fertilizer_application_rate: Fertilizer application rate
    parental_line: Parental line used in the breeding program
    generation: Generation of the breeding population
    yield: Yield measurement for the breeding population
    protein_content: Protein content measurement for the breeding population
    maturity: Maturity measurement for the breeding population
    marker_data: Marker data generated for the breeding population
    qtl_mapping: QTL mapping data for the breeding population
    field_trial_location: Location of the field trial for the breeding population
    weather_conditions: Weather conditions during the field trial
    gene_id: Unique identifier for each gene
    functional_description: Functional description of the gene
    rna_seq_data: RNA-seq data for gene expression analysis
    qpcr_data: qPCR data for gene expression analysis
    proteomics_data: Proteomics data for protein analysis
    protein_interaction_data: Protein-protein interaction data
    metabolite_profile: Metabolite profile data
    pathway_analysis: Pathway analysis data
    participant_id: Unique identifier for each participant
    demographic_data: Demographic data of the participant
    survey_response: Survey response data
    interview_transcript: Interview transcript data
    interview_coding: Interview coding data
    cost_benefit_analysis: Cost-benefit analysis data
    market_analysis: Market analysis data
    regulations: Regulations data
    stakeholder_analysis: Stakeholder analysis data

******************************************************************
Layer name: spec/overlays/unit/1.1
SAID/digest: ELyhPOjMVLihqIO7K4t7xtzvrIlmUV5d8Fyhm1siHaex
Measurement system: undefined

Schema attributes: spec/overlays/unit/1.1
    inoculum_concentration: cfu/ml
    disease_severity_score: -
    n2o_flux: g N/ha/day
    ch4_flux: g C/ha/day
    co2_flux: g C/ha/day
    soil_temperature: °C
    soil_moisture: %
    soil_nutrient_content: varies
    crop_yield: kg/ha
    fertilizer_application_rate: kg/ha
    yield: kg/ha
    protein_content: %
    maturity: days

******************************************************************
END_OCA_BUNDLE

BEGIN_OCA_PACKAGE_EXTENSIONS
******************************************************************
Layer name: community/overlays/adc/ordering/1.1
SAID/digest: EPjBJG8SYWTbp8LVYYOnt2QgsnnP6KRhuUcbX0-IK_an
Attribute ordering: accession_id, species, subspecies, origin, morphological_trait, agronomic_trait, sequencing_platform, variant_calls, geographic_location, climate_conditions, pathogen_strain, inoculum_concentration, disease_severity_score, n2o_flux, ch4_flux, co2_flux, soil_temperature, soil_moisture, soil_nutrient_content, crop_yield, fertilizer_application_rate, parental_line, generation, yield, protein_content, maturity, marker_data, qtl_mapping, field_trial_location, weather_conditions, gene_id, functional_description, rna_seq_data, qpcr_data, proteomics_data, protein_interaction_data, metabolite_profile, pathway_analysis, participant_id, demographic_data, survey_response, interview_transcript, interview_coding, cost_benefit_analysis, market_analysis, regulations, stakeholder_analysis

******************************************************************
Layer name: community/overlays/adc/sensitive/1.1
SAID/digest: EBz1mYKnUH4sgyoyvsj60VGDsHo2VegPBoFh9Cbomlw4
Sensitive attributes: demographic_data, interview_coding, interview_transcript, participant_id, survey_response

******************************************************************
END_OCA_PACKAGE_EXTENSIONS
