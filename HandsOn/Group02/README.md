# Group02 — Madrid Culture Finder

Hands-on 1: dataset selection and application specification.

## Group members

| Name | GitHub username |
| --- | --- |
| JUNQI WENG | [jweng71](https://github.com/jweng71) |
| XIAN CHEN | [xian0223](https://github.com/xian0223) |
| LEONARDO LIN | [LeonardoLin05](https://github.com/LeonardoLin05) |
| ALEJANDRO DE LORENZO ESCRIBANO | [Pescabichillo](https://github.com/Pescabichillo) |

Group number: Group02, selected as the next available number on 29 September 2026; not yet reserved by an online submission. Group leader: pending agreement.
Number check: the upstream HandsOn directory had no merged group directories; open [PR #27](https://github.com/FacultadInformatica-LinkedData/Curso2026-2027/pull/27) already contains Group01. No other open PR contained a HandsOn group directory at the time of checking. Accordingly, use Group02 and recheck before submission for concurrent claims.

## Proposal

Find libraries and museums by name, area, accessibility features and distance. Course domain: **Smart community facilities**, with **Smart education** for libraries and **Smart tourism** for museums. Evidence: the domain diagram in `07.MGLD.pdf`, PDF page 46 (slide 47), titled “Hands-on domain: smart cities as an example”. These are explicit diagram labels; the facility-to-domain mapping is our interpretation. The Moodle preference for green datasets appears in Individual Assignment 1, not the Group Hands-on Assignment 1 requirements.

## Deliverables

- [Libraries CSV](csv/libraries.csv): 52 records.
- [Museums CSV](csv/museums.csv): 68 records.
- [Dataset requirements and sources](requirements/datasetRequirements.html).
- [Application requirements and static UI mock-ups](requirements/applicationRequirements.html).
- [Self-assessment](selfAssessmentHandsOn1.md).
- [Download provenance and quality profile](csv/provenance.json).

CSV parsing: semicolon separator, Windows-1252 encoding, 32 columns. Original downloaded files are unchanged. HTML documents are UTF-8 and can be opened locally without dependencies.

## Data attribution

Source: Ayuntamiento de Madrid, [Bibliotecas de Madrid](https://datos.madrid.es/dataset/201747-0-bibliobuses-bibliotecas) and [Museos de la ciudad de Madrid](https://datos.madrid.es/dataset/201132-0-museos), retrieved 29 September 2026. Both declare [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Current CSV files: unmodified snapshots. Future RDF derivatives must indicate their transformations and preserve attribution.

## Submission status

Deadline provided for this assignment: **1 October 2026, 23:59, Europe/Madrid**.
Pending: group review of the application and self-assessment, recheck of group-number availability, and GitHub submission. School submission has not been made. These materials are maintained on the master branch of the personal fork jweng71/Curso2026-2027.
