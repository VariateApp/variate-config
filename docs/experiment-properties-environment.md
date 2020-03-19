# Environment Schema

```txt
https://variate.ca/definitions/environment.json#/properties/environment
```

Represent the environment of an experiment.


| Abstract            | Extensible | Status | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                   |
| :------------------ | ---------- | ------ | ----------------------- | :---------------- | --------------------- | ------------------- | -------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Stable | Unknown identifiability | Forbidden         | Allowed               | none                | [experiment.schema.json\*](../out/definitions/experiment.schema.json "open original schema") |

## environment Type

`string` ([Environment](experiment-properties-environment.md))

## environment Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | ----------- |
| `"production"`  |             |
| `"development"` |             |

**pattern**: the string must match the following regular expression: 

```regexp
^(.*)$
```

[try pattern](https://regexr.com/?expression=%5E(.*)%24 "try regular expression with regexr.com")
