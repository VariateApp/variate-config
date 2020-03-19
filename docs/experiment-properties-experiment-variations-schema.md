# Experiment Variations Schema Schema

```txt
https://variate.ca/definitions/experiment.json#/properties/variations
```




| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                   |
| :------------------ | ---------- | -------------- | ----------------------- | :---------------- | --------------------- | ------------------- | -------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [experiment.schema.json\*](../out/definitions/experiment.schema.json "open original schema") |

## variations Type

`object` ([Experiment Variations Schema](experiment-properties-experiment-variations-schema.md))

# Experiment Variations Schema Properties

| Property       | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                  |
| :------------- | -------- | -------- | -------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `[a-zA-Z0-9]+` | `object` | Optional | cannot be null | [Experiment](experiment-properties-experiment-variations-schema-patternproperties-variation.md "https&#x3A;//variate.ca/definitions/variation.json#/properties/variations/patternProperties/\[a-zA-Z0-9]+") |

## Pattern: `[a-zA-Z0-9]+`

The variation object contains the variation ID, traffic allocation information and the list of components for this variation.


`[a-zA-Z0-9]+`

-   is optional
-   Type: `object` ([Variation](experiment-properties-experiment-variations-schema-patternproperties-variation.md))
-   cannot be null
-   defined in: [Experiment](experiment-properties-experiment-variations-schema-patternproperties-variation.md "https&#x3A;//variate.ca/definitions/variation.json#/properties/variations/patternProperties/\[a-zA-Z0-9]+")

### \[a-zA-Z0-9]+ Type

`object` ([Variation](experiment-properties-experiment-variations-schema-patternproperties-variation.md))
