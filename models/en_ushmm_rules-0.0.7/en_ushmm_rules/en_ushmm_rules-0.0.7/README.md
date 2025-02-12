This is a pipeline of heuristics to help identify essential entities for research into the Holocaust.

| Feature | Description |
| --- | --- |
| **Name** | `en_ushmm_rules` |
| **Version** | `0.0.7` |
| **spaCy** | `>=3.1.1,<3.2.0` |
| **Default Pipeline** | `find_ships`, `find_ghettos`, `find_people`, `find_spousal`, `find_camps_strict`, `find_groups`, `find_places`, `find_geography`, `ner` |
| **Components** | `find_ships`, `find_ghettos`, `find_people`, `find_spousal`, `find_camps_strict`, `find_groups`, `find_places`, `find_geography`, `ner` |
| **Vectors** | 0 keys, 0 unique vectors (0 dimensions) |
| **Sources** | n/a |
| **License** | n/a |
| **Author** | [W.J.B. Mattingly](www.wjbmattingly.com) |

### Label Scheme

<details>

<summary>View label scheme (18 labels for 1 components)</summary>

| Component | Labels |
| --- | --- |
| **`ner`** | `CARDINAL`, `DATE`, `EVENT`, `FAC`, `GPE`, `LANGUAGE`, `LAW`, `LOC`, `MONEY`, `NORP`, `ORDINAL`, `ORG`, `PERCENT`, `PERSON`, `PRODUCT`, `QUANTITY`, `TIME`, `WORK_OF_ART` |

</details>