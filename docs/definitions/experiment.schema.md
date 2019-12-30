# Experiment Schema

```
https://variate.ca/definitions/experiment.json
```

The experiment object contains the experiment ID, name, status, targeting information and list of variations included
in this experiment.

| Abstract            | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In                                                   |
| ------------------- | ---------- | ------ | ------------ | ----------------- | --------------------- | ------------------------------------------------------------ |
| Can be instantiated | No         | Stable | No           | Forbidden         | Permitted             | [definitions/experiment.schema.json](experiment.schema.json) |

## Schema Hierarchy

- Experiment `https://variate.ca/definitions/experiment.json`
  - [ID](id.schema.md) `https://variate.ca/definitions/id.json`
  - [Environment](status.schema.md) `https://variate.ca/definitions/environment.json`

# Experiment Properties

| Property                                    | Type        | Required     | Nullable | Default                                    | Defined by               |
| ------------------------------------------- | ----------- | ------------ | -------- | ------------------------------------------ | ------------------------ |
| [environment](#environment)                 | Environment | **Required** | No       |                                            | Experiment (this schema) |
| [id](#id)                                   | ID          | **Required** | No       |                                            | Experiment (this schema) |
| [manualQualification](#manualqualification) | `boolean`   | Optional     | No       | `false`                                    | Experiment (this schema) |
| [name](#name)                               | `string`    | **Required** | No       | `""`                                       | Experiment (this schema) |
| [siteId](#siteid)                           | ID          | **Required** | No       |                                            | Experiment (this schema) |
| [targeting](#targeting)                     | `object`    | **Required** | No       |                                            | Experiment (this schema) |
| [variations](#variations)                   | `object`    | **Required** | No       |                                            | Experiment (this schema) |
| `*`                                         | any         | Additional   | Yes      | this schema _allows_ additional properties |

## environment

`environment`

- is **required**
- type: Environment
- defined in this schema

### environment Type

- [Environment](status.schema.md) – `https://variate.ca/definitions/environment.json`

## id

### Experiment ID

`id`

- is **required**
- type: ID
- defined in this schema

### id Type

- [ID](id.schema.md) – `https://variate.ca/definitions/id.json`

## manualQualification

### If set to true, this experiment will not trigger any qualification event

`manualQualification`

- is optional
- type: `boolean`
- default: `false`
- defined in this schema

### manualQualification Type

`boolean`

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

## siteId

### Site ID

`siteId`

- is **required**
- type: ID
- defined in this schema

### siteId Type

- [ID](id.schema.md) – `https://variate.ca/definitions/id.json`

## targeting

### Experiment Targeting Schema

`targeting`

- is **required**
- type: `object`
- defined in this schema

### targeting Type

`object` with following properties:

| Property   | Type     | Required     |
| ---------- | -------- | ------------ |
| `segments` | Segments | **Required** |
| `views`    | Views    | **Required** |

#### segments

`segments`

- is **required**
- type: Segments

##### segments Type

- [Segments](segments.schema.md) – `https://variate.ca/definitions/segments.json`

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
- type: `object`
- defined in this schema

### variations Type

`object` with following properties:

| Property | Type | Required |
| -------- | ---- | -------- |

