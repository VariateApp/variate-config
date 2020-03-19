# Percentage Schema

```txt
https://variate.ca/definitions/percentage.json#/properties/max
```

Percentage value type. Can be an integer of a float, must be a multiple of 0.01 and must be between 0 and 100.


| Abstract            | Extensible | Status | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                             |
| :------------------ | ---------- | ------ | ----------------------- | :---------------- | --------------------- | ------------------- | -------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Stable | Unknown identifiability | Forbidden         | Allowed               | none                | [traffic.schema.json\*](../out/definitions/traffic.schema.json "open original schema") |

## max Type

`number` ([Percentage](traffic-properties-percentage-1.md))

## max Constraints

**multiple of**: the value of this number must be a multiple of: `0.01`

**maximum**: the value of this number must smaller than or equal to: `100`

**minimum**: the value of this number must greater than or equal to: `0`

## max Examples

```json
0
```

```json
33.33
```

```json
100
```
