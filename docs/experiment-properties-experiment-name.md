# Experiment Name Schema

```txt
https://variate.ca/definitions/experiment.json#/properties/name
```




| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                   |
| :------------------ | ---------- | -------------- | ----------------------- | :---------------- | --------------------- | ------------------- | -------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [experiment.schema.json\*](../out/definitions/experiment.schema.json "open original schema") |

## name Type

`string` ([Experiment Name](experiment-properties-experiment-name.md))

## name Constraints

**pattern**: the string must match the following regular expression: 

```regexp
^(.*)$
```

[try pattern](https://regexr.com/?expression=%5E(.*)%24 "try regular expression with regexr.com")

## name Examples

```json
"Homepage - Hero Banner"
```
