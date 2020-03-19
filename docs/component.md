# Component Schema

```txt
https://variate.ca/definitions/component.json
```

Component ID along with its list of attributes.


| Abstract            | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                               |
| :------------------ | ---------- | ------ | ------------ | :---------------- | --------------------- | ------------------- | ---------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Stable | No           | Forbidden         | Forbidden             | none                | [component.schema.json](../out/definitions/component.schema.json "open original schema") |

## Component Type

`object` ([Component](component.md))

# Component Properties

| Property                      | Type     | Required | Nullable       | Defined by                                                                                                              |
| :---------------------------- | -------- | -------- | -------------- | :---------------------------------------------------------------------------------------------------------------------- |
| [id](#id)                     | `string` | Required | cannot be null | [Component](experiment-properties-id-1.md "https&#x3A;//variate.ca/definitions/id.json#/properties/id")                 |
| [variationId](#variationId)   | `string` | Required | cannot be null | [Component](experiment-properties-id-1.md "https&#x3A;//variate.ca/definitions/id.json#/properties/variationId")        |
| [experimentId](#experimentId) | `string` | Required | cannot be null | [Component](experiment-properties-id-1.md "https&#x3A;//variate.ca/definitions/id.json#/properties/experimentId")       |
| [siteId](#siteId)             | `string` | Required | cannot be null | [Component](experiment-properties-id-1.md "https&#x3A;//variate.ca/definitions/id.json#/properties/siteId")             |
| [variables](#variables)       | `object` | Required | cannot be null | [Component](component-properties-variable.md "https&#x3A;//variate.ca/definitions/variable.json#/properties/variables") |

## id

Identifier type used within Variate.


`id`

-   is required
-   Type: `string` ([ID](experiment-properties-id-1.md))
-   cannot be null
-   defined in: [Component](experiment-properties-id-1.md "https&#x3A;//variate.ca/definitions/id.json#/properties/id")

### id Type

`string` ([ID](experiment-properties-id-1.md))

### id Examples

```json
"C74lbTFFVUk6Zj76ysMK"
```

```json
"nM3ntXmMj2dX86xnrvVK"
```

## variationId

Identifier type used within Variate.


`variationId`

-   is required
-   Type: `string` ([ID](experiment-properties-id-1.md))
-   cannot be null
-   defined in: [Component](experiment-properties-id-1.md "https&#x3A;//variate.ca/definitions/id.json#/properties/variationId")

### variationId Type

`string` ([ID](experiment-properties-id-1.md))

### variationId Examples

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
-   defined in: [Component](experiment-properties-id-1.md "https&#x3A;//variate.ca/definitions/id.json#/properties/experimentId")

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
-   defined in: [Component](experiment-properties-id-1.md "https&#x3A;//variate.ca/definitions/id.json#/properties/siteId")

### siteId Type

`string` ([ID](experiment-properties-id-1.md))

### siteId Examples

```json
"C74lbTFFVUk6Zj76ysMK"
```

```json
"nM3ntXmMj2dX86xnrvVK"
```

## variables

Key/value pair representing a variable, usually children of components.


`variables`

-   is required
-   Type: `object` ([Variable](component-properties-variable.md))
-   cannot be null
-   defined in: [Component](component-properties-variable.md "https&#x3A;//variate.ca/definitions/variable.json#/properties/variables")

### variables Type

`object` ([Variable](component-properties-variable.md))
