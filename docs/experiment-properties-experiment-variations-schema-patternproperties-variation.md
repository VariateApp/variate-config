# Variation Schema

```txt
https://variate.ca/definitions/variation.json#/properties/variations/patternProperties/[a-zA-Z0-9]+
```

The variation object contains the variation ID, traffic allocation information and the list of components for this variation.


| Abstract            | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                   |
| :------------------ | ---------- | ------ | ------------ | :---------------- | --------------------- | ------------------- | -------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Stable | No           | Forbidden         | Allowed               | none                | [experiment.schema.json\*](../out/definitions/experiment.schema.json "open original schema") |

## \[a-zA-Z0-9]+ Type

`object` ([Variation](experiment-properties-experiment-variations-schema-patternproperties-variation.md))

# Variation Properties

| Property                                | Type     | Required | Nullable       | Defined by                                                                                                                      |
| :-------------------------------------- | -------- | -------- | -------------- | :------------------------------------------------------------------------------------------------------------------------------ |
| [id](#id)                               | `string` | Required | cannot be null | [Variation](experiment-properties-id-1.md "https&#x3A;//variate.ca/definitions/id.json#/properties/id")                         |
| [experimentId](#experimentId)           | `string` | Required | cannot be null | [Variation](experiment-properties-id-1.md "https&#x3A;//variate.ca/definitions/id.json#/properties/experimentId")               |
| [siteId](#siteId)                       | `string` | Required | cannot be null | [Variation](experiment-properties-id-1.md "https&#x3A;//variate.ca/definitions/id.json#/properties/siteId")                     |
| [trafficAllocation](#trafficAllocation) | `object` | Required | cannot be null | [Variation](variation-properties-traffic.md "https&#x3A;//variate.ca/definitions/traffic.json#/properties/trafficAllocation")   |
| [components](#components)               | `object` | Required | cannot be null | [Variation](variation-properties-component-list.md "https&#x3A;//variate.ca/definitions/variation.json#/properties/components") |
| Additional Properties                   | Any      | Optional | can be null    |                                                                                                                                 |

## id

Identifier type used within Variate.


`id`

-   is required
-   Type: `string` ([ID](experiment-properties-id-1.md))
-   cannot be null
-   defined in: [Variation](experiment-properties-id-1.md "https&#x3A;//variate.ca/definitions/id.json#/properties/id")

### id Type

`string` ([ID](experiment-properties-id-1.md))

### id Examples

```json
"C74lbTFFVUk6Zj76ysMK"
```

```json
"nM3ntXmMj2dX86xnrvVK"
```

## experimentId

Identifier type used within Variate.


`experimentId`

-   is required
-   Type: `string` ([ID](experiment-properties-id-1.md))
-   cannot be null
-   defined in: [Variation](experiment-properties-id-1.md "https&#x3A;//variate.ca/definitions/id.json#/properties/experimentId")

### experimentId Type

`string` ([ID](experiment-properties-id-1.md))

### experimentId Examples

```json
"C74lbTFFVUk6Zj76ysMK"
```

```json
"nM3ntXmMj2dX86xnrvVK"
```

## siteId

Identifier type used within Variate.


`siteId`

-   is required
-   Type: `string` ([ID](experiment-properties-id-1.md))
-   cannot be null
-   defined in: [Variation](experiment-properties-id-1.md "https&#x3A;//variate.ca/definitions/id.json#/properties/siteId")

### siteId Type

`string` ([ID](experiment-properties-id-1.md))

### siteId Examples

```json
"C74lbTFFVUk6Zj76ysMK"
```

```json
"nM3ntXmMj2dX86xnrvVK"
```

## trafficAllocation

The traffic object contains a minimum and maximum percentage of traffic.


`trafficAllocation`

-   is required
-   Type: `object` ([Traffic](variation-properties-traffic.md))
-   cannot be null
-   defined in: [Variation](variation-properties-traffic.md "https&#x3A;//variate.ca/definitions/traffic.json#/properties/trafficAllocation")

### trafficAllocation Type

`object` ([Traffic](variation-properties-traffic.md))

## components




`components`

-   is required
-   Type: `object` ([Component list](variation-properties-component-list.md))
-   cannot be null
-   defined in: [Variation](variation-properties-component-list.md "https&#x3A;//variate.ca/definitions/variation.json#/properties/components")

### components Type

`object` ([Component list](variation-properties-component-list.md))

## Additional Properties

Additional properties are allowed and do not have to follow a specific schema
