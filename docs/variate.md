# Variate Schema

```txt
https://variate.ca/variate.schema.json
```

JSON Schema to define how the Variate config.json file should look like.


| Abstract            | Extensible | Status  | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                               |
| :------------------ | ---------- | ------- | ------------ | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown | No           | Forbidden         | Forbidden             | none                | [variate.schema.json](../out/variate.schema.json "open original schema") |

## Variate Type

`object` ([Variate](variate.md))

# Variate Properties

| Property                    | Type     | Required | Nullable       | Defined by                                                                                            |
| :-------------------------- | -------- | -------- | -------------- | :---------------------------------------------------------------------------------------------------- |
| [experiments](#experiments) | `object` | Required | cannot be null | [Variate](variate-properties-experiments-list.md "\#/properties/experiments#/properties/experiments") |

## experiments




`experiments`

-   is required
-   Type: `object` ([Experiments List](variate-properties-experiments-list.md))
-   cannot be null
-   defined in: [Variate](variate-properties-experiments-list.md "\#/properties/experiments#/properties/experiments")

### experiments Type

`object` ([Experiments List](variate-properties-experiments-list.md))
