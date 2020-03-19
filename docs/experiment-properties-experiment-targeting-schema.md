# Experiment Targeting Schema Schema

```txt
https://variate.ca/definitions/experiment.json#/properties/targeting
```




| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                   |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | -------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [experiment.schema.json\*](../out/definitions/experiment.schema.json "open original schema") |

## targeting Type

`object` ([Experiment Targeting Schema](experiment-properties-experiment-targeting-schema.md))

# Experiment Targeting Schema Properties

| Property              | Type     | Required | Nullable       | Defined by                                                                                                                                                                           |
| :-------------------- | -------- | -------- | -------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [views](#views)       | `object` | Required | cannot be null | [Experiment](experiment-properties-experiment-targeting-schema-properties-views.md "https&#x3A;//variate.ca/definitions/views.json#/properties/targeting/properties/views")          |
| [segments](#segments) | `object` | Required | cannot be null | [Experiment](experiment-properties-experiment-targeting-schema-properties-segments.md "https&#x3A;//variate.ca/definitions/segments.json#/properties/targeting/properties/segments") |

## views

The views object contains two arrays: include and exclude. Each array contains a list of urls or regular expressions to include or exclude from targeting.


`views`

-   is required
-   Type: `object` ([Views](experiment-properties-experiment-targeting-schema-properties-views.md))
-   cannot be null
-   defined in: [Experiment](experiment-properties-experiment-targeting-schema-properties-views.md "https&#x3A;//variate.ca/definitions/views.json#/properties/targeting/properties/views")

### views Type

`object` ([Views](experiment-properties-experiment-targeting-schema-properties-views.md))

## segments

Segments are defined using JSON logic (see <http://jsonlogic.com/> for reference).


`segments`

-   is required
-   Type: `object` ([Segments](experiment-properties-experiment-targeting-schema-properties-segments.md))
-   cannot be null
-   defined in: [Experiment](experiment-properties-experiment-targeting-schema-properties-segments.md "https&#x3A;//variate.ca/definitions/segments.json#/properties/targeting/properties/segments")

### segments Type

`object` ([Segments](experiment-properties-experiment-targeting-schema-properties-segments.md))
