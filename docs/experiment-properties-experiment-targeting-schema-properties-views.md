# Views Schema

```txt
https://variate.ca/definitions/views.json#/properties/targeting/properties/views
```

The views object contains two arrays: include and exclude. Each array contains a list of urls or regular expressions to include or exclude from targeting.


| Abstract            | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                   |
| :------------------ | ---------- | ------ | ------------ | :---------------- | --------------------- | ------------------- | -------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Stable | No           | Forbidden         | Forbidden             | none                | [experiment.schema.json\*](../out/definitions/experiment.schema.json "open original schema") |

## views Type

`object` ([Views](experiment-properties-experiment-targeting-schema-properties-views.md))

# Views Properties

| Property            | Type    | Required | Nullable       | Defined by                                                                                                |
| :------------------ | ------- | -------- | -------------- | :-------------------------------------------------------------------------------------------------------- |
| [include](#include) | `array` | Required | cannot be null | [Views](views-properties-include.md "https&#x3A;//variate.ca/definitions/views.json#/properties/include") |
| [exclude](#exclude) | `array` | Required | cannot be null | [Views](views-properties-exclude.md "https&#x3A;//variate.ca/definitions/views.json#/properties/exclude") |

## include




`include`

-   is required
-   Type: `string[]`
-   cannot be null
-   defined in: [Views](views-properties-include.md "https&#x3A;//variate.ca/definitions/views.json#/properties/include")

### include Type

`string[]`

## exclude




`exclude`

-   is required
-   Type: `string[]`
-   cannot be null
-   defined in: [Views](views-properties-exclude.md "https&#x3A;//variate.ca/definitions/views.json#/properties/exclude")

### exclude Type

`string[]`
