# Variation schema Schema

```
https://variate.ca/definitions/variation.json
```

| Abstract            | Extensible | Status       | Identifiable | Custom Properties | Additional Properties | Defined In                                                 |
| ------------------- | ---------- | ------------ | ------------ | ----------------- | --------------------- | ---------------------------------------------------------- |
| Can be instantiated | No         | Experimental | No           | Forbidden         | Permitted             | [definitions/variation.schema.json](variation.schema.json) |

## Schema Hierarchy

- Variation schema `https://variate.ca/definitions/variation.json`
  - [id.schema](id.schema.md) `https://variate.ca/definitions/id.json`
  - [Traffic allocation schema](traffic.schema.md) `https://variate.ca/definitions/traffic.json`

# Variation schema Properties

| Property                                  | Type                      | Required     | Nullable | Defined by                                 |
| ----------------------------------------- | ------------------------- | ------------ | -------- | ------------------------------------------ |
| [components](#components)                 | `object`                  | **Required** | No       | Variation schema (this schema)             |
| [id](#id)                                 | id.schema                 | **Required** | No       | Variation schema (this schema)             |
| [traffic_allocation](#traffic_allocation) | Traffic allocation schema | **Required** | No       | Variation schema (this schema)             |
| `*`                                       | any                       | Additional   | Yes      | this schema _allows_ additional properties |

## components

### Component list

`components`

- is **required**
- type: `object`
- defined in this schema

### components Type

`object` with following properties:

| Property | Type | Required |
| -------- | ---- | -------- |


## id

### Variation ID

`id`

- is **required**
- type: id.schema
- defined in this schema

### id Type

- [id.schema](id.schema.md) – `https://variate.ca/definitions/id.json`

## traffic_allocation

`traffic_allocation`

- is **required**
- type: Traffic allocation schema
- defined in this schema

### traffic_allocation Type

- [Traffic allocation schema](traffic.schema.md) – `https://variate.ca/definitions/traffic.json`
