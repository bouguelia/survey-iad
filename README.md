# Interactive Anomaly Detection: Reviewed Works

This repository contains the list of the 356 works reviewed in the survey:

> M.-R. Bouguelia, E. Calikus, Y. Fan, and K. Santosh. *Interactive Anomaly Detection: Paradigms, Methods, and Open Challenges*. Under review.

Each work is classified along the dimensions used in the survey: interaction paradigm, evaluation metric family, oracle type, base detector, datasets and application domain.

## File

`iad-survey-reviewed-works.csv` has one row per reviewed work (356 rows).

| Column | Description |
|---|---|
| `Title` | Title of the work |
| `Year` | Publication year (2010 to 2026) |
| `Authors` | Authors, as listed in the bibliographic record |
| `DOI` | Digital Object Identifier, when available |
| `Venue` | Journal or conference |
| `Taxonomy` | Interaction paradigm, given as the section number of the paper (see below) |
| `Metrics_Family` | Evaluation metric families reported, given as section numbers of the paper (see below); a work can report several |
| `Datasets_and_Domains` | Datasets, data types, and application domains used in the work |
| `Oracle_Type` | Who provides feedback in the evaluation (e.g., simulated oracle, real human) |
| `Base_Detector` | Underlying anomaly detector(s) |

### Interaction paradigms (`Taxonomy`)

| Code | Paradigm | Works |
|---|---|---|
| 3.1.1 | On-the-job relevance re-ranking | 36 |
| 3.1.2.1 | Generalization-oriented active learning: label-based interaction | 129 |
| 3.1.2.2 | Generalization-oriented active learning: more complex interactions / richer feedback | 43 |
| 3.2.1 | User-solicited interaction | 32 |
| 3.2.2 | Visualization-based interaction (open loop) | 116 |

Codes 3.1.x are machine-driven paradigms, and codes 3.2.x are human-driven paradigms.

### Metric families (`Metrics_Family`)

| Code | Metric family |
|---|---|
| 4.1 | Detection-quality metrics (e.g., AUC-ROC, F1, AP) |
| 4.2 | Budget-indexed discovery metrics (e.g., anomaly discovery curve, precision@b) |
| 4.3 | Human-effort and cost metrics (e.g., context-switching cost, time, question count) |
| 4.4 | Qualitative and study-based evaluation (e.g., case studies, user studies) |

