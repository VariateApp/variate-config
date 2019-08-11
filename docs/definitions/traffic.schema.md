# Traffic Schema

```
https://variate.ca/definitions/traffic.json
```

The traffic object contains a minimum and maximum percentage of traffic.

| Abstract            | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In                                             |
| ------------------- | ---------- | ------ | ------------ | ----------------- | --------------------- | ------------------------------------------------------ |
| Can be instantiated | No         | Stable | No           | Forbidden         | Forbidden             | [definitions/traffic.schema.json](traffic.schema.json) |

## Schema Hierarchy

- Traffic `https://variate.ca/definitions/traffic.json`
  - [Percentage](percentage.schema.md) `https://variate.ca/definitions/percentage.json`

# Traffic Properties

| Property    | Type       | Required     | Nullable | Defined by            |
| ----------- | ---------- | ------------ | -------- | --------------------- |
| [max](#max) | Percentage | **Required** | No       | Traffic (this schema) |
| [min](#min) | Percentage | **Required** | No       | Traffic (this schema) |

## max

### Minimum traffic percentage allowed.

`max`

- is **required**
- type: Percentage
- defined in this schema

### max Type

- [Percentage](percentage.schema.md) – `https://variate.ca/definitions/percentage.json`

## min

### Maximum traffic percentage allowed.

`min`

- is **required**
- type: Percentage
- defined in this schema

### min Type

- [Percentage](percentage.schema.md) – `https://variate.ca/definitions/percentage.json`
