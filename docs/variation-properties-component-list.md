# Component list Schema

```txt
https://variate.ca/definitions/variation.json#/properties/components
```




| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                 |
| :------------------ | ---------- | -------------- | ----------------------- | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [variation.schema.json\*](../out/definitions/variation.schema.json "open original schema") |

## components Type

`object` ([Component list](variation-properties-component-list.md))

# Component list Properties

| Property              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                  |
| :-------------------- | -------- | -------- | -------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `[a-zA-Z0-9]+`        | `object` | Optional | cannot be null | [Variation](variation-properties-component-list-patternproperties-component.md "https&#x3A;//variate.ca/definitions/component.json#/properties/components/patternProperties/\[a-zA-Z0-9]+") |
| Additional Properties | Any      | Optional | can be null    |                                                                                                                                                                                             |

## Pattern: `[a-zA-Z0-9]+`

Component ID along with its list of attributes.


`[a-zA-Z0-9]+`

-   is optional
-   Type: `object` ([Component](variation-properties-component-list-patternproperties-component.md))
-   cannot be null
-   defined in: [Variation](variation-properties-component-list-patternproperties-component.md "https&#x3A;//variate.ca/definitions/component.json#/properties/components/patternProperties/\[a-zA-Z0-9]+")

### \[a-zA-Z0-9]+ Type

`object` ([Component](variation-properties-component-list-patternproperties-component.md))

## Additional Properties

Additional properties are allowed and do not have to follow a specific schema
