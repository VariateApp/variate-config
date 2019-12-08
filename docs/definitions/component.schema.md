# Component Schema

```
https://variate.ca/definitions/component.json
```

Component ID along with its list of attributes.

| Abstract            | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In                                                 |
| ------------------- | ---------- | ------ | ------------ | ----------------- | --------------------- | ---------------------------------------------------------- |
| Can be instantiated | No         | Draft  | No           | Forbidden         | Forbidden             | [definitions/component.schema.json](component.schema.json) |

## Schema Hierarchy

- Component `https://variate.ca/definitions/component.json`
  - [ID](id.schema.md) `https://variate.ca/definitions/id.json`
  - [Variable](variable.schema.md) `https://variate.ca/definitions/variable.json`

# Component Properties

| Property                | Type     | Required     | Nullable | Defined by              |
| ----------------------- | -------- | ------------ | -------- | ----------------------- |
| [id](#id)               | ID       | **Required** | No       | Component (this schema) |
| [variables](#variables) | Variable | **Required** | No       | Component (this schema) |

## id

### Component ID

`id`

- is **required**
- type: ID
- defined in this schema

### id Type

- [ID](id.schema.md) – `https://variate.ca/definitions/id.json`

## variables

### Variables object

`variables`

- is **required**
- type: Variable
- defined in this schema

### variables Type

- [Variable](variable.schema.md) – `https://variate.ca/definitions/variable.json`
