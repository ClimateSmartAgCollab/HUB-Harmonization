---
layout: default  
title: soil  
parent: Loop  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: soil  
**Description**: A schema describing soil samples together with water content measurements.  
**Classification**: RDF401  
**Author**: Carly Huitema  
**Author Email**: huitemac@uoguelph.ca  
**ICT Group**: Loop  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| collect_date | Collection Date | The date of sample collection |
| collect_time | Collection Time | The time of sample collection |
| date_in | Date In | The date the sample entered the lab |
| date_out | Date Out | The date the sample left the lab |
| duration | Duration | The duration of the sample collection |
| farm | Farm | The farm where the sample was collected |
| final_mass | Final Mass | The final mass of the sample |
| initial_mass | Initial Mass | The initial mass of the sample |
| latitude | Latitude | The latitude where the sample was taken |
| longitude | Longitude | The longitude where the sample was taken |
| moisture | Moisture | The moisture content of the sample |
| paddock_id | Paddock ID | The paddock ID where the sample was collected |
| sample_id | Sample ID | The unique identifier for the sample |
| sample_type | Sample Type | The type of sample |
| samplers | Samplers | The people who collected the sample |
| temperature | Temperature | The temperature at the time of sample collection |
| time_in | Time In | The time the sample entered the lab |
| time_out | Time Out | The time the sample left the lab |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | soil | A schema describing soil samples together with water content measurements. |
| French | sol | Un schéma décrivant des échantillons de sol avec des mesures de contenu en eau. |

## Selection lists

### English

#### farm entry codes

| Entry code | Label |
| --- | --- |
| A | Hensall farm |
| B | Guelph farm north |
| C | Guelph farm south |
| D | Lakeridge farm |

#### samplers entry codes

| Entry code | Label |
| --- | --- |
| Aedan | Aedan |
| Isabella | Isabella |
| Lila | Lila |
| Makhi | Makhi |
| Nathan | Nathan |
| Zara | Zara |

### French

#### farm entry codes

| Entry code | Label |
| --- | --- |
| A | Ferme Hensall |
| B | Ferme Guelph nord |
| C | Ferme Guelph sud |
| D | Ferme Lakeridge |

#### samplers entry codes

| Entry code | Label |
| --- | --- |
| Aedan | Aedan |
| Isabella | Isabella |
| Lila | Lila |
| Makhi | Makhi |
| Nathan | Nathan |
| Zara | Zara |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry | Format rule | Cardinality |
| --- | --- | --- | --- | --- | --- | --- | --- |
| collect_date | false |  | DateTime | utf-8 | true | ^\(?:\(?:19\|20\)\\d\{2\}\)\-\(?:0\[1\-9\]\|1\[0\-2\]\)\-\(?:0\[1\-9\]\|\[1\-2\]\\d\|3\[0\-1\]\)$ |  |
| collect_time | false |  | DateTime | utf-8 | false | ^\(\[01\]\[0\-9\]\|2\[0\-3\]\):\[0\-5\]\[0\-9\]:\[0\-5\]\[0\-9\]$/gm |  |
| date_in | false |  | DateTime | utf-8 | false | ^\(?:\(?:19\|20\)\\d\{2\}\)\-\(?:0\[1\-9\]\|1\[0\-2\]\)\-\(?:0\[1\-9\]\|\[1\-2\]\\d\|3\[0\-1\]\)$ |  |
| date_out | false |  | DateTime | utf-8 | false | ^\(?:\(?:19\|20\)\\d\{2\}\)\-\(?:0\[1\-9\]\|1\[0\-2\]\)\-\(?:0\[1\-9\]\|\[1\-2\]\\d\|3\[0\-1\]\)$ |  |
| duration | false |  | DateTime | utf-8 | false | ^P\(?\!$\)\(\(\\d\+Y\)\|\(\\d\+\.\\d\+Y$\)\)?\(\(\\d\+M\)\|\(\\d\+\.\\d\+M$\)\)?\(\(\\d\+W\)\|\(\\d\+\.\\d\+W$\)\)?\(\(\\d\+D\)\|\(\\d\+\.\\d\+D$\)\)?\(T\(?=\\d\)\(\(\\d\+H\)\|\(\\d\+\.\\d\+H$\)\)?\(\(\\d\+M\)\|\(\\d\+\.\\d\+M$\)\)?\(\\d\+\(\.\\d\+\)?S\)?\)??$/gm |  |
| farm | false |  | Text | utf-8 | true | ^\[A\-Z\]\*$ |  |
| final_mass | false |  | Numeric | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |  |
| initial_mass | false |  | Numeric | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |  |
| latitude | false |  | Text | utf-8 | false |  |  |
| longitude | false |  | Text | utf-8 | false |  |  |
| moisture | false |  | Numeric | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |  |
| paddock_id | false |  | Numeric | utf-8 | false | ^\-?\[0\-9\]\+$ |  |
| sample_id | false |  | Text | utf-8 | false | ^\.\{0,250\}$ |  |
| sample_type | false |  | Text | utf-8 | false | ^\.\{0,50\}$ |  |
| samplers | false |  | Array[Text] | utf-8 | false |  | -6 |
| temperature | false |  | Numeric | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |  |
| time_in | false |  | DateTime | utf-8 | false | ^\(\[01\]\[0\-9\]\|2\[0\-3\]\):\[0\-5\]\[0\-9\]:\[0\-5\]\[0\-9\]$/gm |  |
| time_out | false |  | DateTime | utf-8 | false | ^\(\[01\]\[0\-9\]\|2\[0\-3\]\):\[0\-5\]\[0\-9\]:\[0\-5\]\[0\-9\]$/gm |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| collect_date | Collection Date | The date of sample collection | Not a list |
| collect_time | Collection Time | The time of sample collection | Not a list |
| date_in | Date In | The date the sample entered the lab | Not a list |
| date_out | Date Out | The date the sample left the lab | Not a list |
| duration | Duration | The duration of the sample collection | Not a list |
| farm | Farm | The farm where the sample was collected | Hensall farm, Guelph farm north, Guelph farm south, Lakeridge farm |
| final_mass | Final Mass | The final mass of the sample | Not a list |
| initial_mass | Initial Mass | The initial mass of the sample | Not a list |
| latitude | Latitude | The latitude where the sample was taken | Not a list |
| longitude | Longitude | The longitude where the sample was taken | Not a list |
| moisture | Moisture | The moisture content of the sample | Not a list |
| paddock_id | Paddock ID | The paddock ID where the sample was collected | Not a list |
| sample_id | Sample ID | The unique identifier for the sample | Not a list |
| sample_type | Sample Type | The type of sample | Not a list |
| samplers | Samplers | The people who collected the sample | Aedan, Isabella, Lila, Makhi, Nathan, Zara |
| temperature | Temperature | The temperature at the time of sample collection | Not a list |
| time_in | Time In | The time the sample entered the lab | Not a list |
| time_out | Time Out | The time the sample left the lab | Not a list |

### French

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| collect_date | Date de collecte | La date de prélèvement de l'échantillon | Not a list |
| collect_time | Heure de collecte | L'heure de prélèvement de l'échantillon | Not a list |
| date_in | Date d'entrée | La date d'entrée de l'échantillon au laboratoire | Not a list |
| date_out | Date de sortie | La date de sortie de l'échantillon du laboratoire | Not a list |
| duration | Durée | La durée du prélèvement de l'échantillon | Not a list |
| farm | Ferme | La ferme où l'échantillon a été prélevé | Ferme Hensall, Ferme Guelph nord, Ferme Guelph sud, Ferme Lakeridge |
| final_mass | Masse finale | La masse finale de l'échantillon | Not a list |
| initial_mass | Masse initiale | La masse initiale de l'échantillon | Not a list |
| latitude | Latitude | La latitude où l'échantillon a été prélevé | Not a list |
| longitude | Longitude | La longitude où l'échantillon a été prélevé | Not a list |
| moisture | Humidité | Le contenu en eau de l'échantillon | Not a list |
| paddock_id | ID de paddock | L'ID du paddock où l'échantillon a été prélevé | Not a list |
| sample_id | ID de l'échantillon | L'identifiant unique de l'échantillon | Not a list |
| sample_type | Type d'échantillon | Le type d'échantillon | Not a list |
| samplers | Préleveurs | Les personnes ayant prélevé l'échantillon | Aedan, Isabella, Lila, Makhi, Nathan, Zara |
| temperature | Température | La température au moment du prélèvement de l'échantillon | Not a list |
| time_in | Heure d'entrée | L'heure d'entrée de l'échantillon au laboratoire | Not a list |
| time_out | Heure de sortie | L'heure de sortie de l'échantillon du laboratoire | Not a list |

## Schema SAIDs

**Capture base**: E6JUx2q_fhhRYd5eNgEMpf-i8E-J85cUwtESJy5hwsjw

| Layer | SAID |
| --- | --- |
| cardinality | E6DwehssZ_U7KULl1LoSb7PbBrjjgD0aoBGCbsS8b4Cs |
| character_encoding | E6pqc9ZauW6fgArWw8SQhwJIBlfBcNvm-t8vCZOTqJOw |
| conformance | EfsRccYvCeLKrAPHgx9uv-W1ouLX8NqbKZXQWIrLl-JA |
| entry (en) | EGde-cJBqgYM1pCgPcPsH7lhlxksgzHTV9M59vvH8aEQ |
| entry (fr) | EmjVEJE7AK--c2WbGQXziteHcSQ_q77x77ogn9m6kkss |
| entry_code | EoY3xD_i7Sh08O1C-ZOjshGOuU6_4-DvMlWDG4kXQUfs |
| format | EikrVOMd1_CWxt2eOmv0dcT7IDrW8H_O-7NAv-MKDl8o |
| information (en) | EQF9hA5P0_9yFL3qbfiyOOWgPP22t4YTQBLVqgkWxrsI |
| information (fr) | EXD8axZq-N0Ep7m0wzrAUVzCoUmY0LLkePWXZpFbTPLA |
| label (en) | Es7HPsJohdCOJ81TDvIF6Aq79aF2HOA3NRbwaOLaih6E |
| label (fr) | EtGn4Tek5z565WAil9Qk3amD56DETJHM1IzX9kUXNygI |
| meta (en) | E1zyoXMihO6dUg-ENiK1jm2W_Kh4MniRDaVLhtruqtfU |
| meta (fr) | EYqWdhDW_ixnicw-wR_uRqkLlrkfOzoDdEVIdWuhf8-s |

**Date created**: 2024-11-28 10:57:49

