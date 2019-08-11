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
  - [Attribute](attribute.schema.md) `https://variate.ca/definitions/attribute.json`

# Component Properties

| Property                  | Type      | Required     | Nullable | Defined by              |
| ------------------------- | --------- | ------------ | -------- | ----------------------- |
| [attributes](#attributes) | Attribute | **Required** | No       | Component (this schema) |
| [id](#id)                 | ID        | **Required** | No       | Component (this schema) |

## attributes

### Attributes object

`attributes`

- is **required**
- type: Attribute
- defined in this schema

### attributes Type

- [Attribute](attribute.schema.md) – `https://variate.ca/definitions/attribute.json`

## id

### Component ID

`id`

- is **required**
- type: ID
- defined in this schema

### id Type

- [ID](id.schema.md) – `https://variate.ca/definitions/id.json`
