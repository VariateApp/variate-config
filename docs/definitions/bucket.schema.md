# Bucket Schema

```
https://variate.ca/definitions/bucket.json
```

Special bucket of traffic for canary experiment (experiment ran on a reduced percentage of traffic regardless of
targeting.

| Abstract            | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In                                           |
| ------------------- | ---------- | ------ | ------------ | ----------------- | --------------------- | ---------------------------------------------------- |
| Can be instantiated | No         | Stable | No           | Forbidden         | Forbidden             | [definitions/bucket.schema.json](bucket.schema.json) |

## Schema Hierarchy

- Bucket `https://variate.ca/definitions/bucket.json`
  - [Percentage](percentage.schema.md) `https://variate.ca/definitions/percentage.json`

# Bucket Properties

| Property                    | Type       | Required     | Nullable | Defined by           |
| --------------------------- | ---------- | ------------ | -------- | -------------------- |
| [experiments](#experiments) | Experiment | **Required** | No       | Bucket (this schema) |
| [max](#max)                 | Percentage | **Required** | No       | Bucket (this schema) |
| [min](#min)                 | Percentage | **Required** | No       | Bucket (this schema) |

## experiments

### Experiments

`experiments`

- is **required**
- type: Experiment
- defined in this schema

### experiments Type

Array type: Experiment

All items must be of the type:

- [Experiment](experiment.schema.md) – `https://variate.ca/definitions/experiment.json`

## max

`max`

- is **required**
- type: Percentage
- defined in this schema

### max Type

- [Percentage](percentage.schema.md) – `https://variate.ca/definitions/percentage.json`

## min

`min`

- is **required**
- type: Percentage
- defined in this schema

### min Type

- [Percentage](percentage.schema.md) – `https://variate.ca/definitions/percentage.json`
