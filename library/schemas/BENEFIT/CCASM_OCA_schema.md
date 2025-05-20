---
layout: default  
title: CCASM Strain Collection  
parent: BENEFIT  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: CCASM Strain Collection  
**Description**: Metadata associated with the bacterial strains deposited in the Canadian Collection of Agricultural Soil Microbes (CCASM)  
**Classification**: RDF106  
**Author**: George Colin diCenzo  
**Author Email**: george.dicenzo@queensu.ca  
**ICT Group**: BENEFIT  
**Schema package SAID**: EFgo32vmhNVHNwEPnmN-cm54cMWBz8Yx30iuBqEQC--J  

[Download schema](CCASM_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| CCASM_ID | CCASM identifier | The unique CCASM identifier of the strain |
| Queens_box_ID | Queen's freezer box ID | The barcode on the freezer box of the replicate stored at Queen\'s University |
| Queens_box_name | Queen's freezer box name | The common name of the freezer box of the replicate stored at Queen\'s University |
| Queens_well | Queen's freezer box well position | The position within the freezer box of the replicate stored at Queen\'s University |
| Queens_barcode | Queen's freezer vial barcode | The barcode on the freezer vial of the replicate stored at Queen\'s University |
| Manitoba_box_ID | Manitoba freezer box ID | The barcode on the freezer box of the replicate stored at the University of Manitoba |
| Manitoba_box_name | Manitoba freezer box name | The common name of the freezer box of the replicate stored at the University of Manitoba |
| Manitoba_well | Manitoba freezer box well position | The position within the freezer box of the replicate stored at the University of Manitoba |
| Manitoba_barcode | Manitoba freezer vial barcode | The barcode on the freezer vial of the replicate stored at the University of Manitoba |
| strain_name | Strain name(s) | Other strain name(s) of the isolate |
| binomial_classification | Binomial classification | The binomial classification (genus and species, if classified) of the isolate |
| taxonomic_lineage | Full taxonomic lineage | The full taxonomic lineage of the isolate |
| risk_group | Risk group | The risk group (1, 2, 3, 4) of the isolate, if known |
| is_plant_pathogen | Is the strain a plant pathogen | An indication of whether the strain is a known plant pathogen |
| colony_morphology | Colony morphology | Description of the colony morphology of the isolate |
| host_plant_species | Associated plant species | The plant species from which the microbe was isolated, or that was planted in the soil from which the microbe was isolated |
| isolation_source | Isolation source | The source (soil or plant tissue type) that the microbe was isolated from |
| isolation_year | Isolation year | The year that the microbe was isolated |
| isolation_protocol | Isolation protocol | The method used for isolating the microbe |
| isolation_growth_medium | Isolation growth medium | The name of the growth medium that was used to isolate the microbe |
| isolation_growth_temperature | Isolation growth temperature | The incubation temperature used when isolating the microbe |
| isolation_growth_medium_composition | Isolation growth medium composition | The full composition of the growth medium used to isolate the microbe |
| isolation_soil_ph | Isolation soil pH | The pH of the soil from which the microbe was isolated, if known and if relevant |
| isolation_soil_organic_matter | Isolation soil organic matter (%) | The organic matter content of the soil from which the microbe was isolated, if known and if relevant |
| isolation_soil_texture | Isolation soil texture | The texture of the soil from which the microbe was isolated, if known and if relevant |
| isolation_soil_province | Isolation soil province | The province from which the soil (or plant material) was isolated |
| longitude | Longitute | The longitude at which the soil or plant material was sampled |
| latitude | Latitude | The latitude at which the soil or plant material was sampled |
| genome_ncbi_association | Genome NCBI accession | NCBI accession code(s) for the genome assembly of the microbe, if available |
| genome_size | Genome size | The genome size of the microbe, if known |
| notes | Notes | Additional notes about the microbe |
| citation | Citation | Citation of the study reporting the microbe, if available |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | CCASM Strain Collection | Metadata associated with the bacterial strains deposited in the Canadian Collection of Agricultural Soil Microbes (CCASM) |

## Selection lists

### English

#### is_plant_pathogen entry codes

| Entry code | Label |
| --- | --- |
| Yes | Yes |
| No | No |
| Unknown | Unknown |

#### isolation_protocol entry codes

| Entry code | Label |
| --- | --- |
| Soil dilution | Soil dilution plating |
| Tissue dilution | Tissue crushing and dilution plating |
| Nodule trapping | Nodule trapping experiment |
| Other | Other method as indicated in notes |

#### isolation_soil_province entry codes

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
| QC | Quebec |
| SK | Saskatchewan |
| NT | Northwest Territories |
| NU | Nunavut |
| YT | Yukon |

#### isolation_source entry codes

| Entry code | Label |
| --- | --- |
| Soil | Soil sample |
| Nodule | Nodule tissue |
| Root | Root tissue |
| Leaf | Leaf tissue |
| Stem | Stem tissue |
| Seed | Seed tissue |
| Other | Other source as indicated in notes |

#### risk_group entry codes

| Entry code | Label |
| --- | --- |
| 1 | Risk Group 1 |
| 2 | Risk Group 2 |
| 3 | Risk Group 3 |
| 4 | Risk Group 4 |
| Unknown | Unknown |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry | Format rule |
| --- | --- | --- | --- | --- | --- | --- |
| CCASM_ID | false |  | Text |  | true | ^\.\{0,50\}$ |
| Queens_box_ID | false |  | Text |  | true | ^\.\{0,50\}$ |
| Queens_box_name | false |  | Text |  | true | ^\.\{0,50\}$ |
| Queens_well | false |  | Text |  | true | ^\.\{0,50\}$ |
| Queens_barcode | false |  | Text |  | true | ^\.\{0,50\}$ |
| Manitoba_box_ID | false |  | Text |  | true | ^\.\{0,50\}$ |
| Manitoba_box_name | false |  | Text |  | true | ^\.\{0,50\}$ |
| Manitoba_well | false |  | Text |  | true | ^\.\{0,50\}$ |
| Manitoba_barcode | false |  | Text |  | true | ^\.\{0,50\}$ |
| strain_name | false |  | Text |  | true | ^\.\{0,4000\}$ |
| binomial_classification | false |  | Text |  | true | ^\.\{0,250\}$ |
| taxonomic_lineage | false |  | Text |  | true | ^\.\{0,4000\}$ |
| risk_group | false |  | Numeric |  | true | ^\-?\[0\-9\]\+$ |
| is_plant_pathogen | false |  | Text |  | true | ^\.\{0,50\}$ |
| colony_morphology | false |  | Text |  | false | ^\.\{0,4000\}$ |
| host_plant_species | false |  | Text |  | true | ^\.\{0,250\}$ |
| isolation_source | false |  | Text |  | true | ^\.\{0,250\}$ |
| isolation_year | false |  | DateTime |  | true | ^\(\\d\{4\}\)$ |
| isolation_protocol | false |  | Text |  | true | ^\.\{0,250\}$ |
| isolation_growth_medium | false |  | Text |  | true | ^\.\{0,50\}$ |
| isolation_growth_temperature | false |  | Numeric |  | true | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| isolation_growth_medium_composition | false |  | Text |  | true | ^\.\{0,4000\}$ |
| isolation_soil_ph | false |  | Numeric |  | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| isolation_soil_organic_matter | false |  | Numeric |  | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| isolation_soil_texture | false |  | Text |  | false | ^\.\{0,250\}$ |
| isolation_soil_province | false |  | Text |  | false | ^\.\{0,50\}$ |
| longitude | true |  | Numeric |  | true | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| latitude | true |  | Numeric |  | true | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| genome_ncbi_association | false |  | Text |  | false | ^\.\{0,800\}$ |
| genome_size | false |  | Numeric |  | false | ^\-?\[0\-9\]\+$ |
| notes | true |  | Text |  | false | ^\.\{0,4000\}$ |
| citation | false |  | Text |  | false | ^\.\{0,4000\}$ |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| CCASM_ID | CCASM identifier | The unique CCASM identifier of the strain | Not a list |
| Queens_box_ID | Queen's freezer box ID | The barcode on the freezer box of the replicate stored at Queen\'s University | Not a list |
| Queens_box_name | Queen's freezer box name | The common name of the freezer box of the replicate stored at Queen\'s University | Not a list |
| Queens_well | Queen's freezer box well position | The position within the freezer box of the replicate stored at Queen\'s University | Not a list |
| Queens_barcode | Queen's freezer vial barcode | The barcode on the freezer vial of the replicate stored at Queen\'s University | Not a list |
| Manitoba_box_ID | Manitoba freezer box ID | The barcode on the freezer box of the replicate stored at the University of Manitoba | Not a list |
| Manitoba_box_name | Manitoba freezer box name | The common name of the freezer box of the replicate stored at the University of Manitoba | Not a list |
| Manitoba_well | Manitoba freezer box well position | The position within the freezer box of the replicate stored at the University of Manitoba | Not a list |
| Manitoba_barcode | Manitoba freezer vial barcode | The barcode on the freezer vial of the replicate stored at the University of Manitoba | Not a list |
| strain_name | Strain name(s) | Other strain name(s) of the isolate | Not a list |
| binomial_classification | Binomial classification | The binomial classification (genus and species, if classified) of the isolate | Not a list |
| taxonomic_lineage | Full taxonomic lineage | The full taxonomic lineage of the isolate | Not a list |
| risk_group | Risk group | The risk group (1, 2, 3, 4) of the isolate, if known | Risk Group 1, Risk Group 2, Risk Group 3, Risk Group 4, Unknown |
| is_plant_pathogen | Is the strain a plant pathogen | An indication of whether the strain is a known plant pathogen | Yes, No, Unknown |
| colony_morphology | Colony morphology | Description of the colony morphology of the isolate | Not a list |
| host_plant_species | Associated plant species | The plant species from which the microbe was isolated, or that was planted in the soil from which the microbe was isolated | Not a list |
| isolation_source | Isolation source | The source (soil or plant tissue type) that the microbe was isolated from | Soil sample, Nodule tissue, Root tissue, Leaf tissue, Stem tissue, Seed tissue, Other source as indicated in notes |
| isolation_year | Isolation year | The year that the microbe was isolated | Not a list |
| isolation_protocol | Isolation protocol | The method used for isolating the microbe | Soil dilution plating, Tissue crushing and dilution plating, Nodule trapping experiment, Other method as indicated in notes |
| isolation_growth_medium | Isolation growth medium | The name of the growth medium that was used to isolate the microbe | Not a list |
| isolation_growth_temperature | Isolation growth temperature | The incubation temperature used when isolating the microbe | Not a list |
| isolation_growth_medium_composition | Isolation growth medium composition | The full composition of the growth medium used to isolate the microbe | Not a list |
| isolation_soil_ph | Isolation soil pH | The pH of the soil from which the microbe was isolated, if known and if relevant | Not a list |
| isolation_soil_organic_matter | Isolation soil organic matter (%) | The organic matter content of the soil from which the microbe was isolated, if known and if relevant | Not a list |
| isolation_soil_texture | Isolation soil texture | The texture of the soil from which the microbe was isolated, if known and if relevant | Not a list |
| isolation_soil_province | Isolation soil province | The province from which the soil (or plant material) was isolated | Alberta, British Columbia, Manitoba, New Brunswick, Newfoundland and Labrador, Nova Scotia, Ontario, Prince Edward Island, Quebec, Saskatchewan, Northwest Territories, Nunavut, Yukon |
| longitude | Longitute | The longitude at which the soil or plant material was sampled | Not a list |
| latitude | Latitude | The latitude at which the soil or plant material was sampled | Not a list |
| genome_ncbi_association | Genome NCBI accession | NCBI accession code(s) for the genome assembly of the microbe, if available | Not a list |
| genome_size | Genome size | The genome size of the microbe, if known | Not a list |
| notes | Notes | Additional notes about the microbe | Not a list |
| citation | Citation | Citation of the study reporting the microbe, if available | Not a list |

## Schema SAIDs

**Capture base**: EMN_7K_d-L8N9I0TGBBCp0drL0UfGFacvmbDrKSs1QOP

**Bundle**: EOkhgGcMv_Y-mmnRZpHodr61YSa1Nd2IGsCNaWAglfor

**Package**: EFgo32vmhNVHNwEPnmN-cm54cMWBz8Yx30iuBqEQC--J

| Layer | SAID | Type |
| --- | --- | --- |
| conformance | EKFSGHTqTOWnrxEwAQLY40vm3DD6gVFipl_L7KjOwK_w | spec/overlays/conformance/1.1 |
| entry (eng) | EC2Gz8xhY9ZFW_Hg4iRTaOBj7SMDr8Q5SHly87E9ck6h | spec/overlays/entry/1.1 |
| entry_code | EJ7k44YNb9K2M0T7ozjZ7mjmJVJUPIjyT30Kq92W3Ak5 | spec/overlays/entry_code/1.1 |
| format | EEUmbMB3Wa5MTzpX2T8Xz2E-iAEBvcnJo0IIN2RfT5G9 | spec/overlays/format/1.1 |
| information (eng) | ED5_5AEIcxHaKN0hth_8VoZpv9jIcMN6pLt6M-WSvI57 | spec/overlays/information/1.1 |
| label (eng) | EJk9P5qrxQmz4vLFq0hheVPZbU_LQclG0xXtzIsfN6Zr | spec/overlays/label/1.1 |
| meta (eng) | EDzQs8AVmGfofTIb6x3Qhnhw8JJAvJFgzeiacdKy8JPH | spec/overlays/meta/1.1 |
| ordering | EDpJaB5M0XV8WLtXFmH205vEsV9pnVMuCWisZVasYZZ9 | community/overlays/adc/ordering/1.1 |
| unit_framing | EN4kmBlvAvhJZ97I_8znC-siH9BMxei7luOtYnhQ-JRU | community/overlays/adc/unit_framing/1.1 |
| sensitive | EPFYFAa0uEpniYkEdWMDcNEnTgat6dg-SGF-4qvCXXNL | community/overlays/adc/sensitive/1.1 |

**Date created**: 2025-05-20 11:43:22

