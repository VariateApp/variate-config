# Traffic allocation schema Schema

```
https://variate.ca/definitions/traffic.json
```

| Abstract            | Extensible | Status       | Identifiable | Custom Properties | Additional Properties | Defined In                                             |
| ------------------- | ---------- | ------------ | ------------ | ----------------- | --------------------- | ------------------------------------------------------ |
| Can be instantiated | No         | Experimental | No           | Forbidden         | Permitted             | [definitions/traffic.schema.json](traffic.schema.json) |

## Schema Hierarchy

- Traffic allocation schema `https://variate.ca/definitions/traffic.json`
  - [percentage.schema](percentage.schema.md) `https://variate.ca/definitions/percentage.json`

# Traffic allocation schema Properties

| Property    | Type              | Required     | Nullable | Defined by                                 |
| ----------- | ----------------- | ------------ | -------- | ------------------------------------------ |
| [max](#max) | percentage.schema | **Required** | No       | Traffic allocation schema (this schema)    |
| [min](#min) | percentage.schema | **Required** | No       | Traffic allocation schema (this schema)    |
| `*`         | any               | Additional   | Yes      | this schema _allows_ additional properties |

## max

### Minimum traffic allowed.

`max`

- is **required**
- type: percentage.schema
- defined in this schema

### max Type

- [percentage.schema](percentage.schema.md) – `https://variate.ca/definitions/percentage.json`

## min

### Maximum traffic allowed.

`min`

- is **required**
- type: percentage.schema
- defined in this schema

### min Type

- [percentage.schema](percentage.schema.md) – `https://variate.ca/definitions/percentage.json`
