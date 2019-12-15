# Component Schema

```
https://variate.ca/definitions/component.json
```

Component ID along with its list of attributes.

| Abstract            | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In                                                 |
| ------------------- | ---------- | ------ | ------------ | ----------------- | --------------------- | ---------------------------------------------------------- |
| Can be instantiated | No         | Stable | No           | Forbidden         | Forbidden             | [definitions/component.schema.json](component.schema.json) |

## Schema Hierarchy

- Component `https://variate.ca/definitions/component.json`
  - [ID](id.schema.md) `https://variate.ca/definitions/id.json`
  - [Variable](variable.schema.md) `https://variate.ca/definitions/variable.json`

# Component Properties

| Property                      | Type     | Required     | Nullable | Defined by              |
| ----------------------------- | -------- | ------------ | -------- | ----------------------- |
| [experimentId](#experimentid) | ID       | **Required** | No       | Component (this schema) |
| [id](#id)                     | ID       | **Required** | No       | Component (this schema) |
| [siteId](#siteid)             | ID       | **Required** | No       | Component (this schema) |
| [variables](#variables)       | Variable | **Required** | No       | Component (this schema) |
| [variationId](#variationid)   | ID       | **Required** | No       | Component (this schema) |

## experimentId

### Experiment ID

`experimentId`

- is **required**
- type: ID
- defined in this schema

### experimentId Type

- [ID](id.schema.md) – `https://variate.ca/definitions/id.json`

## id

### Component ID

`id`

- is **required**
- type: ID
- defined in this schema

### id Type

- [ID](id.schema.md) – `https://variate.ca/definitions/id.json`

## siteId

### Site ID

`siteId`

- is **required**
- type: ID
- defined in this schema

### siteId Type

- [ID](id.schema.md) – `https://variate.ca/definitions/id.json`

## variables

### Variables object

`variables`

- is **required**
- type: Variable
- defined in this schema

### variables Type

- [Variable](variable.schema.md) – `https://variate.ca/definitions/variable.json`

## variationId

### Variation ID

`variationId`

- is **required**
- type: ID
- defined in this schema

### variationId Type

- [ID](id.schema.md) – `https://variate.ca/definitions/id.json`
