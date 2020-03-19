# Percentage Schema

```txt
https://variate.ca/definitions/percentage.json
```

Percentage value type. Can be an integer of a float, must be a multiple of 0.01 and must be between 0 and 100.


| Abstract            | Extensible | Status | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                 |
| :------------------ | ---------- | ------ | ----------------------- | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------------------ |
| Can be instantiated | No         | Stable | Unknown identifiability | Forbidden         | Allowed               | none                | [percentage.schema.json](../out/definitions/percentage.schema.json "open original schema") |

## Percentage Type

`number` ([Percentage](percentage.md))

## Percentage Constraints

**multiple of**: the value of this number must be a multiple of: `0.01`

**maximum**: the value of this number must smaller than or equal to: `100`

**minimum**: the value of this number must greater than or equal to: `0`

## Percentage Examples

```json
0
```

```json
33.33
```

```json
100
```
