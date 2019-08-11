# Experiment Schema Schema

```
https://variate.ca/definitions/experiment.json
```

| Abstract            | Extensible | Status       | Identifiable | Custom Properties | Additional Properties | Defined In                                                   |
| ------------------- | ---------- | ------------ | ------------ | ----------------- | --------------------- | ------------------------------------------------------------ |
| Can be instantiated | No         | Experimental | No           | Forbidden         | Permitted             | [definitions/experiment.schema.json](experiment.schema.json) |

## Schema Hierarchy

- Experiment Schema `https://variate.ca/definitions/experiment.json`
  - [id.schema](id.schema.md) `https://variate.ca/definitions/id.json`
  - [Experiment status schema](status.schema.md) `https://variate.ca/definitions/status.json`

# Experiment Schema Properties

| Property                  | Type                     | Required     | Nullable | Default                                    | Defined by                      |
| ------------------------- | ------------------------ | ------------ | -------- | ------------------------------------------ | ------------------------------- |
| [id](#id)                 | id.schema                | **Required** | No       |                                            | Experiment Schema (this schema) |
| [name](#name)             | `string`                 | **Required** | No       | `""`                                       | Experiment Schema (this schema) |
| [status](#status)         | Experiment status schema | **Required** | No       |                                            | Experiment Schema (this schema) |
| [targeting](#targeting)   | `object`                 | **Required** | No       |                                            | Experiment Schema (this schema) |
| [variations](#variations) | Variation schema         | **Required** | No       |                                            | Experiment Schema (this schema) |
| `*`                       | any                      | Additional   | Yes      | this schema _allows_ additional properties |

## id

### Experiment ID

`id`

- is **required**
- type: id.schema
- defined in this schema

### id Type

- [id.schema](id.schema.md) – `https://variate.ca/definitions/id.json`

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
- type: Experiment status schema
- defined in this schema

### status Type

- [Experiment status schema](status.schema.md) – `https://variate.ca/definitions/status.json`

## targeting

### Experiment Targeting Schema

`targeting`

- is **required**
- type: `object`
- defined in this schema

### targeting Type

`object` with following properties:

| Property    | Type                               | Required     |
| ----------- | ---------------------------------- | ------------ |
| `audiences` | Audiences schema (uses json logic) | **Required** |
| `views`     | View schema                        | **Required** |

#### audiences

`audiences`

- is **required**
- type: Audiences schema (uses json logic)

##### audiences Type

- [Audiences schema (uses json logic)](audiences.schema.md) – `https://variate.ca/definitions/audiences.json`

#### views

`views`

- is **required**
- type: View schema

##### views Type

- [View schema](views.schema.md) – `https://variate.ca/definitions/views.json`

## variations

### Experiment Variations Schema

`variations`

- is **required**
- type: Variation schema
- defined in this schema

### variations Type

Array type: Variation schema

All items must be of the type:

- [Variation schema](variation.schema.md) – `https://variate.ca/definitions/variation.json`
