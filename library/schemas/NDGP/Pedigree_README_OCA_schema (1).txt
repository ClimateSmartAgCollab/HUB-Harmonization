
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
Package SAID/digest: EOv3TSb3EDIZYdOtPIPTgtg2bNfgKwG_HNrqdGILz_WM
Bundle SAID/digest: EHFHRC3XvgklWxlyXILLenKrdk9PN9bZSgNp_7l5t8nZ

spec/capture_base/1.1 SAID/digest: "EKBa-ldXtgfZMXdjIwTeoccKLyJ9KlsDSIiPr737hh2R"
spec/overlays/meta/1.1 (eng) SAID/digest: "ENXWXXPkDubfnMP1WwuBhdtFWcRPgJGeQ3ghgMYy2ZxD"
spec/overlays/label/1.1 (eng) SAID/digest: "EBdKjDEVlcjirq6DfYxWpsxuWK56dtPvhQOKJTGV_XIn"
spec/overlays/information/1.1 (eng) SAID/digest: "EL9Id-flLeDFBILdbRpUU75lYeTY8bOHYNMPvtBbe4w1"
spec/overlays/conformance/1.1 SAID/digest: "ENKUvpp6xxWoeRjWxHWyoEsiapP_qQjqtF9wEEgz3dCe"
spec/overlays/character_encoding/1.1 SAID/digest: "EIj4bv1fC5EW4jwyw_ovMhJsDItL85ZixNelORZSyLDW"
spec/overlays/entry_code/1.1 SAID/digest: "EEov_xnPMh2v2qUgTYZZ6tdJTOOdO4FBaW0hURSMGxcC"
spec/overlays/entry/1.1 (eng) SAID/digest: "EFDF3wqCrP2Ec1XtBjjWiCv4jcG7dRHo3cJxPfezxh3M"

community/overlays/adc/ordering/1.1 SAID/digest: "EHJtLg0zRs-6OgAM_bXWINPNGm-3z2nV6LH03FOGVtzO"
******************************************************************
END_OCA_MANIFEST

BEGIN_OCA_BUNDLE
******************************************************************
Layer name: spec/capture_base/1.1
SAID/digest: EKBa-ldXtgfZMXdjIwTeoccKLyJ9KlsDSIiPr737hh2R
Classification: RDF402

Schema attributes: data type
    FILE_TYPE: Text
    ANIMAL_ID: Text
    TRANSACTION_TYPE: Text
    SIRE_ID: Text
    DAM_ID: Text
    BIRTH_DATE: DateTime
    REGISTERED_NAME: Text
    SOURCE_OF_DATA: Text
    PROJECT: Text

******************************************************************
Layer name: spec/overlays/meta/1.1
SAID/digest: ENXWXXPkDubfnMP1WwuBhdtFWcRPgJGeQ3ghgMYy2ZxD
Language: eng
Description: Data schema for the pedigree file layout for the Resilient Dairy Genome Project

******************************************************************
Layer name: spec/overlays/label/1.1
SAID/digest: EBdKjDEVlcjirq6DfYxWpsxuWK56dtPvhQOKJTGV_XIn
Language: eng
Schema attributes: spec/overlays/label/1.1
    FILE_TYPE: FILE_TYPE
    ANIMAL_ID: ANIMAL_ID
    TRANSACTION_TYPE: TRANSACTION_TYPE
    SIRE_ID: SIRE_ID
    DAM_ID: DAM_ID
    BIRTH_DATE: BIRTH_DATE
    REGISTERED_NAME: REGISTERED_NAME
    SOURCE_OF_DATA: SOURCE_OF_DATA
    PROJECT: PROJECT

******************************************************************
Layer name: spec/overlays/information/1.1
SAID/digest: EL9Id-flLeDFBILdbRpUU75lYeTY8bOHYNMPvtBbe4w1
Language: eng
Schema attributes: spec/overlays/information/1.1
    ANIMAL_ID: INTERBULL REGISTRATION CODE WHICH HAS EXACTLY 19 CHARACTERS. MADE UP OF FOUR COMPONENTS: BREED (3), COUNTRY (3), SEX(1), REGISTRATION NUMBER(12)
    SIRE_ID: 12 DIGIT ALPHANUMERIC FIELD THAT CONTAIN THE UNIQUE IDENTIFICATION NUMBER ASSIGNED TO THE ANIMAL BY THE RESPECTIVE BREED ASSOCIATION. IT HAS TO BE RIGHT JUSTIFIED IN THE FIELD (WITH LEADING '0'S).
    DAM_ID: 12 DIGIT ALPHANUMERIC FIELD THAT CONTAIN THE UNIQUE IDENTIFICATION NUMBER ASSIGNED TO THE ANIMAL BY THE RESPECTIVE BREED ASSOCIATION. IT HAS TO BE RIGHT JUSTIFIED IN THE FIELD (WITH LEADING '0'S).
    SOURCE_OF_DATA: See contacts list under 'Source of Data' column

******************************************************************
Layer name: spec/overlays/conformance/1.1
SAID/digest: ENKUvpp6xxWoeRjWxHWyoEsiapP_qQjqtF9wEEgz3dCe

Schema attributes: spec/overlays/conformance/1.1
    FILE_TYPE: O
    ANIMAL_ID: O
    TRANSACTION_TYPE: O
    SIRE_ID: M
    DAM_ID: M
    BIRTH_DATE: O
    REGISTERED_NAME: M
    SOURCE_OF_DATA: O
    PROJECT: O

******************************************************************
Layer name: spec/overlays/character_encoding/1.1
SAID/digest: EIj4bv1fC5EW4jwyw_ovMhJsDItL85ZixNelORZSyLDW

Schema attributes: spec/overlays/character_encoding/1.1
    FILE_TYPE: utf-8
    ANIMAL_ID: utf-8
    TRANSACTION_TYPE: utf-8
    SIRE_ID: utf-8
    DAM_ID: utf-8
    BIRTH_DATE: utf-8
    REGISTERED_NAME: utf-8
    SOURCE_OF_DATA: utf-8
    PROJECT: utf-8

******************************************************************
Layer name: spec/overlays/entry_code/1.1
SAID/digest: EEov_xnPMh2v2qUgTYZZ6tdJTOOdO4FBaW0hURSMGxcC

Schema attributes: spec/overlays/entry_code/1.1
    FILE_TYPE: [01,02,03,04,05,06]
    TRANSACTION_TYPE: [U,D]
    PROJECT: [100,110,111,010,011,001,101]

******************************************************************
Layer name: spec/overlays/entry/1.1
SAID/digest: EFDF3wqCrP2Ec1XtBjjWiCv4jcG7dRHo3cJxPfezxh3M
Schema attributes: spec/overlays/entry/1.1
    FILE_TYPE: Pedigree, Calving, Production, Events, Genotype, Milk data
    TRANSACTION_TYPE: Update, Delete
    PROJECT: EDGP, EDGP & NAEX, EDGP & RDGP, EDGP & RDGP & NAEX, RDGP, RDGP & NAEX, NAEX

******************************************************************
END_OCA_BUNDLE

BEGIN_OCA_PACKAGE_EXTENSIONS
******************************************************************
Layer name: community/overlays/adc/ordering/1.1
SAID/digest: EHJtLg0zRs-6OgAM_bXWINPNGm-3z2nV6LH03FOGVtzO
Attribute ordering: FILE_TYPE, ANIMAL_ID, TRANSACTION_TYPE, SIRE_ID, DAM_ID, BIRTH_DATE, REGISTERED_NAME, SOURCE_OF_DATA, PROJECT
Entry code ordering:
    FILE_TYPE: 01, 02, 03, 04, 05, 06
    TRANSACTION_TYPE: U, D
    PROJECT: 100, 110, 111, 010, 011, 001, 101

******************************************************************
END_OCA_PACKAGE_EXTENSIONS
