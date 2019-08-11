# Experiment Schema

```
https://variate.ca/definitions/experiment.json
```

The experiment object contains the experiment ID, name, status, targeting information and list of variations included
in this experiment.

| Abstract            | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In                                                   |
| ------------------- | ---------- | ------ | ------------ | ----------------- | --------------------- | ------------------------------------------------------------ |
| Can be instantiated | No         | Draft  | No           | Forbidden         | Permitted             | [definitions/experiment.schema.json](experiment.schema.json) |

## Schema Hierarchy

- Experiment `https://variate.ca/definitions/experiment.json`
  - [ID](id.schema.md) `https://variate.ca/definitions/id.json`
  - [Status](status.schema.md) `https://variate.ca/definitions/status.json`

# Experiment Properties

| Property                  | Type      | Required     | Nullable | Default                                    | Defined by               |
| ------------------------- | --------- | ------------ | -------- | ------------------------------------------ | ------------------------ |
| [id](#id)                 | ID        | **Required** | No       |                                            | Experiment (this schema) |
| [name](#name)             | `string`  | **Required** | No       | `""`                                       | Experiment (this schema) |
| [status](#status)         | Status    | **Required** | No       |                                            | Experiment (this schema) |
| [targeting](#targeting)   | `object`  | **Required** | No       |                                            | Experiment (this schema) |
| [variations](#variations) | Variation | **Required** | No       |                                            | Experiment (this schema) |
| `*`                       | any       | Additional   | Yes      | this schema _allows_ additional properties |

## id

### Experiment ID

`id`

- is **required**
- type: ID
- defined in this schema

### id Type

- [ID](id.schema.md) – `https://variate.ca/definitions/id.json`

## name

### Experiment Name

`name`

- is **required**
- type: `string`
- default: `""`
- defined in this schema

### name Type

`string`

All instances must conform to this regular expression

```regex
^(.*)$
```

- test example: [Homepage - Hero Banner](<https://regexr.com/?expression=%5E(.*)%24&text=Homepage%20-%20Hero%20Banner>)

### name Example

```json
"Homepage - Hero Banner"
```

## status

`status`

- is **required**
- type: Status
- defined in this schema

### status Type

- [Status](status.schema.md) – `https://variate.ca/definitions/status.json`

## targeting

### Experiment Targeting Schema

`targeting`

- is **required**
- type: `object`
- defined in this schema

### targeting Type

`object` with following properties:

| Property    | Type      | Required     |
| ----------- | --------- | ------------ |
| `audiences` | Audiences | **Required** |
| `views`     | Views     | **Required** |

#### audiences

`audiences`

- is **required**
- type: Audiences

##### audiences Type

- [Audiences](audiences.schema.md) – `https://variate.ca/definitions/audiences.json`

#### views

`views`

- is **required**
- type: Views

##### views Type

- [Views](views.schema.md) – `https://variate.ca/definitions/views.json`

## variations

### Experiment Variations Schema

`variations`

- is **required**
- type: Variation
- defined in this schema

### variations Type

Array type: Variation

All items must be of the type:

- [Variation](variation.schema.md) – `https://variate.ca/definitions/variation.json`
