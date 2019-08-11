# Component schema Schema

```
https://variate.ca/definitions/component.json
```

| Abstract            | Extensible | Status       | Identifiable | Custom Properties | Additional Properties | Defined In                                                 |
| ------------------- | ---------- | ------------ | ------------ | ----------------- | --------------------- | ---------------------------------------------------------- |
| Can be instantiated | No         | Experimental | No           | Forbidden         | Permitted             | [definitions/component.schema.json](component.schema.json) |

## Schema Hierarchy

- Component schema `https://variate.ca/definitions/component.json`
  - [id.schema](id.schema.md) `https://variate.ca/definitions/id.json`
  - [Attribute schema (can be any key value pair)](attribute.schema.md) `https://variate.ca/definitions/attribute.json`

# Component schema Properties

| Property                  | Type                                         | Required     | Nullable | Defined by                                 |
| ------------------------- | -------------------------------------------- | ------------ | -------- | ------------------------------------------ |
| [attributes](#attributes) | Attribute schema (can be any key value pair) | **Required** | No       | Component schema (this schema)             |
| [id](#id)                 | id.schema                                    | **Required** | No       | Component schema (this schema)             |
| `*`                       | any                                          | Additional   | Yes      | this schema _allows_ additional properties |

## attributes

### Attributes object

`attributes`

- is **required**
- type: Attribute schema (can be any key value pair)
- defined in this schema

### attributes Type

- [Attribute schema (can be any key value pair)](attribute.schema.md) – `https://variate.ca/definitions/attribute.json`

## id

### Component ID

`id`

- is **required**
- type: id.schema
- defined in this schema

### id Type

- [id.schema](id.schema.md) – `https://variate.ca/definitions/id.json`
