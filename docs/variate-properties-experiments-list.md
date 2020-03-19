# Experiments List Schema

```txt
#/properties/experiments#/properties/experiments
```




| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                 |
| :------------------ | ---------- | -------------- | ----------------------- | :---------------- | --------------------- | ------------------- | -------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [variate.schema.json\*](../out/variate.schema.json "open original schema") |

## experiments Type

`object` ([Experiments List](variate-properties-experiments-list.md))

# Experiments List Properties

| Property       | Type     | Required | Nullable       | Defined by                                                                                                                                                                                   |
| :------------- | -------- | -------- | -------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[a-zA-Z0-9]+` | `object` | Optional | cannot be null | [Variate](variate-properties-experiments-list-patternproperties-experiment.md "https&#x3A;//variate.ca/definitions/experiment.json#/properties/experiments/patternProperties/\[a-zA-Z0-9]+") |

## Pattern: `[a-zA-Z0-9]+`

The experiment object contains the experiment ID, name, status, targeting information and list of variations included in this experiment.


`[a-zA-Z0-9]+`

-   is optional
-   Type: `object` ([Experiment](variate-properties-experiments-list-patternproperties-experiment.md))
-   cannot be null
-   defined in: [Variate](variate-properties-experiments-list-patternproperties-experiment.md "https&#x3A;//variate.ca/definitions/experiment.json#/properties/experiments/patternProperties/\[a-zA-Z0-9]+")

### \[a-zA-Z0-9]+ Type

`object` ([Experiment](variate-properties-experiments-list-patternproperties-experiment.md))
