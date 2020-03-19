# Traffic Schema

```txt
https://variate.ca/definitions/traffic.json
```

The traffic object contains a minimum and maximum percentage of traffic.


| Abstract            | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                           |
| :------------------ | ---------- | ------ | ------------ | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------------ |
| Can be instantiated | No         | Stable | No           | Forbidden         | Forbidden             | none                | [traffic.schema.json](../out/definitions/traffic.schema.json "open original schema") |

## Traffic Type

`object` ([Traffic](traffic.md))

# Traffic Properties

| Property    | Type     | Required | Nullable       | Defined by                                                                                                          |
| :---------- | -------- | -------- | -------------- | :------------------------------------------------------------------------------------------------------------------ |
| [max](#max) | `number` | Required | cannot be null | [Traffic](traffic-properties-percentage-1.md "https&#x3A;//variate.ca/definitions/percentage.json#/properties/max") |
| [min](#min) | `number` | Required | cannot be null | [Traffic](traffic-properties-percentage-1.md "https&#x3A;//variate.ca/definitions/percentage.json#/properties/min") |

## max

Percentage value type. Can be an integer of a float, must be a multiple of 0.01 and must be between 0 and 100.


`max`

-   is required
-   Type: `number` ([Percentage](traffic-properties-percentage-1.md))
-   cannot be null
-   defined in: [Traffic](traffic-properties-percentage-1.md "https&#x3A;//variate.ca/definitions/percentage.json#/properties/max")

### max Type

`number` ([Percentage](traffic-properties-percentage-1.md))

### max Constraints

**multiple of**: the value of this number must be a multiple of: `0.01`

**maximum**: the value of this number must smaller than or equal to: `100`

**minimum**: the value of this number must greater than or equal to: `0`

### max Examples

```json
0
```

```json
33.33
```

```json
100
```

## min

Percentage value type. Can be an integer of a float, must be a multiple of 0.01 and must be between 0 and 100.


`min`

-   is required
-   Type: `number` ([Percentage](traffic-properties-percentage-1.md))
-   cannot be null
-   defined in: [Traffic](traffic-properties-percentage-1.md "https&#x3A;//variate.ca/definitions/percentage.json#/properties/min")

### min Type

`number` ([Percentage](traffic-properties-percentage-1.md))

### min Constraints

**multiple of**: the value of this number must be a multiple of: `0.01`

**maximum**: the value of this number must smaller than or equal to: `100`

**minimum**: the value of this number must greater than or equal to: `0`

### min Examples

```json
0
```

```json
33.33
```

```json
100
```
