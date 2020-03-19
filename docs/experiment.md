# Experiment Schema

```txt
https://variate.ca/definitions/experiment.json
```

The experiment object contains the experiment ID, name, status, targeting information and list of variations included in this experiment.


| Abstract            | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                 |
| :------------------ | ---------- | ------ | ------------ | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------------------ |
| Can be instantiated | No         | Stable | No           | Forbidden         | Allowed               | none                | [experiment.schema.json](../out/definitions/experiment.schema.json "open original schema") |

## Experiment Type

`object` ([Experiment](experiment.md))

# Experiment Properties

| Property                                    | Type      | Required | Nullable       | Defined by                                                                                                                                                                                           |
| :------------------------------------------ | --------- | -------- | -------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [id](#id)                                   | `string`  | Required | cannot be null | [Experiment](experiment-properties-id-1.md "https&#x3A;//variate.ca/definitions/id.json#/properties/id")                                                                                             |
| [siteId](#siteId)                           | `string`  | Required | cannot be null | [Experiment](experiment-properties-id-1.md "https&#x3A;//variate.ca/definitions/id.json#/properties/siteId")                                                                                         |
| [name](#name)                               | `string`  | Required | cannot be null | [Experiment](experiment-properties-experiment-name.md "https&#x3A;//variate.ca/definitions/experiment.json#/properties/name")                                                                        |
| [environment](#environment)                 | `string`  | Required | cannot be null | [Experiment](experiment-properties-environment.md "https&#x3A;//variate.ca/definitions/environment.json#/properties/environment")                                                                    |
| [manualQualification](#manualQualification) | `boolean` | Optional | cannot be null | [Experiment](experiment-properties-if-set-to-true-this-experiment-will-not-trigger-any-qualification-event.md "https&#x3A;//variate.ca/definitions/experiment.json#/properties/manualQualification") |
| [targeting](#targeting)                     | `object`  | Required | cannot be null | [Experiment](experiment-properties-experiment-targeting-schema.md "https&#x3A;//variate.ca/definitions/experiment.json#/properties/targeting")                                                       |
| [variations](#variations)                   | `object`  | Required | cannot be null | [Experiment](experiment-properties-experiment-variations-schema.md "https&#x3A;//variate.ca/definitions/experiment.json#/properties/variations")                                                     |
| Additional Properties                       | Any       | Optional | can be null    |                                                                                                                                                                                                      |

## id

Identifier type used within Variate.


`id`

-   is required
-   Type: `string` ([ID](experiment-properties-id-1.md))
-   cannot be null
-   defined in: [Experiment](experiment-properties-id-1.md "https&#x3A;//variate.ca/definitions/id.json#/properties/id")

### id Type

`string` ([ID](experiment-properties-id-1.md))

### id Examples

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
-   defined in: [Experiment](experiment-properties-id-1.md "https&#x3A;//variate.ca/definitions/id.json#/properties/siteId")

### siteId Type

`string` ([ID](experiment-properties-id-1.md))

### siteId Examples

```json
"C74lbTFFVUk6Zj76ysMK"
```

```json
"nM3ntXmMj2dX86xnrvVK"
```

## name




`name`

-   is required
-   Type: `string` ([Experiment Name](experiment-properties-experiment-name.md))
-   cannot be null
-   defined in: [Experiment](experiment-properties-experiment-name.md "https&#x3A;//variate.ca/definitions/experiment.json#/properties/name")

### name Type

`string` ([Experiment Name](experiment-properties-experiment-name.md))

### name Constraints

**pattern**: the string must match the following regular expression: 

```regexp
^(.*)$
```

[try pattern](https://regexr.com/?expression=%5E(.*)%24 "try regular expression with regexr.com")

### name Examples

```json
"Homepage - Hero Banner"
```

## environment

Represent the environment of an experiment.


`environment`

-   is required
-   Type: `string` ([Environment](experiment-properties-environment.md))
-   cannot be null
-   defined in: [Experiment](experiment-properties-environment.md "https&#x3A;//variate.ca/definitions/environment.json#/properties/environment")

### environment Type

`string` ([Environment](experiment-properties-environment.md))

### environment Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | ----------- |
| `"production"`  |             |
| `"development"` |             |

**pattern**: the string must match the following regular expression: 

```regexp
^(.*)$
```

[try pattern](https://regexr.com/?expression=%5E(.*)%24 "try regular expression with regexr.com")

## manualQualification




`manualQualification`

-   is optional
-   Type: `boolean` ([If set to true, this experiment will not trigger any qualification event](experiment-properties-if-set-to-true-this-experiment-will-not-trigger-any-qualification-event.md))
-   cannot be null
-   defined in: [Experiment](experiment-properties-if-set-to-true-this-experiment-will-not-trigger-any-qualification-event.md "https&#x3A;//variate.ca/definitions/experiment.json#/properties/manualQualification")

### manualQualification Type

`boolean` ([If set to true, this experiment will not trigger any qualification event](experiment-properties-if-set-to-true-this-experiment-will-not-trigger-any-qualification-event.md))

## targeting




`targeting`

-   is required
-   Type: `object` ([Experiment Targeting Schema](experiment-properties-experiment-targeting-schema.md))
-   cannot be null
-   defined in: [Experiment](experiment-properties-experiment-targeting-schema.md "https&#x3A;//variate.ca/definitions/experiment.json#/properties/targeting")

### targeting Type

`object` ([Experiment Targeting Schema](experiment-properties-experiment-targeting-schema.md))

## variations




`variations`

-   is required
-   Type: `object` ([Experiment Variations Schema](experiment-properties-experiment-variations-schema.md))
-   cannot be null
-   defined in: [Experiment](experiment-properties-experiment-variations-schema.md "https&#x3A;//variate.ca/definitions/experiment.json#/properties/variations")

### variations Type

`object` ([Experiment Variations Schema](experiment-properties-experiment-variations-schema.md))

## Additional Properties

Additional properties are allowed and do not have to follow a specific schema
