# Bucket definition Schema

```
https://variate.ca/definitions/bucket.json
```

| Abstract            | Extensible | Status       | Identifiable | Custom Properties | Additional Properties | Defined In                                           |
| ------------------- | ---------- | ------------ | ------------ | ----------------- | --------------------- | ---------------------------------------------------- |
| Can be instantiated | No         | Experimental | No           | Forbidden         | Permitted             | [definitions/bucket.schema.json](bucket.schema.json) |

## Schema Hierarchy

- Bucket definition `https://variate.ca/definitions/bucket.json`
  - [percentage.schema](percentage.schema.md) `https://variate.ca/definitions/percentage.json`

# Bucket definition Properties

| Property                    | Type              | Required     | Nullable | Defined by                                 |
| --------------------------- | ----------------- | ------------ | -------- | ------------------------------------------ |
| [experiments](#experiments) | Experiment Schema | **Required** | No       | Bucket definition (this schema)            |
| [max](#max)                 | percentage.schema | **Required** | No       | Bucket definition (this schema)            |
| [min](#min)                 | percentage.schema | **Required** | No       | Bucket definition (this schema)            |
| `*`                         | any               | Additional   | Yes      | this schema _allows_ additional properties |

## experiments

### Experiments

`experiments`

- is **required**
- type: Experiment Schema
- defined in this schema

### experiments Type

Array type: Experiment Schema

All items must be of the type:

- [Experiment Schema](experiment.schema.md) – `https://variate.ca/definitions/experiment.json`

## max

`max`

- is **required**
- type: percentage.schema
- defined in this schema

### max Type

- [percentage.schema](percentage.schema.md) – `https://variate.ca/definitions/percentage.json`

## min

`min`

- is **required**
- type: percentage.schema
- defined in this schema

### min Type

- [percentage.schema](percentage.schema.md) – `https://variate.ca/definitions/percentage.json`
