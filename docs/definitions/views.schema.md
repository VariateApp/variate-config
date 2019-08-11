# Views Schema

```
https://variate.ca/definitions/views.json
```

The views object contains two arrays: include and exclude. Each array contains a list of urls or regular expressions to
include or exclude from targeting.

| Abstract            | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In                                         |
| ------------------- | ---------- | ------ | ------------ | ----------------- | --------------------- | -------------------------------------------------- |
| Can be instantiated | No         | Draft  | No           | Forbidden         | Forbidden             | [definitions/views.schema.json](views.schema.json) |

# Views Properties

| Property            | Type       | Required     | Nullable | Defined by          |
| ------------------- | ---------- | ------------ | -------- | ------------------- |
| [exclude](#exclude) | `string[]` | **Required** | No       | Views (this schema) |
| [include](#include) | `string[]` | **Required** | No       | Views (this schema) |

## exclude

`exclude`

- is **required**
- type: `string[]`
- defined in this schema

### exclude Type

Array type: `string[]`

All items must be of the type: `string`

All instances must conform to this regular expression

```regex
^(.*)$
```

- test example: [&amp;#x2F;\$](<https://regexr.com/?expression=%5E(.*)%24&text=%2F%24>)

## include

`include`

- is **required**
- type: `string[]`
- defined in this schema

### include Type

Array type: `string[]`

All items must be of the type: `string`

All instances must conform to this regular expression

```regex
^(.*)$
```

- test example: [&amp;#x2F;\$](<https://regexr.com/?expression=%5E(.*)%24&text=%2F%24>)
