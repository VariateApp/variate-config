# View schema Schema

```
https://variate.ca/definitions/views.json
```

| Abstract            | Extensible | Status       | Identifiable | Custom Properties | Additional Properties | Defined In                                         |
| ------------------- | ---------- | ------------ | ------------ | ----------------- | --------------------- | -------------------------------------------------- |
| Can be instantiated | No         | Experimental | No           | Forbidden         | Permitted             | [definitions/views.schema.json](views.schema.json) |

# View schema Properties

| Property            | Type       | Required     | Nullable | Defined by                                 |
| ------------------- | ---------- | ------------ | -------- | ------------------------------------------ |
| [exclude](#exclude) | `string[]` | **Required** | No       | View schema (this schema)                  |
| [include](#include) | `string[]` | **Required** | No       | View schema (this schema)                  |
| `*`                 | any        | Additional   | Yes      | this schema _allows_ additional properties |

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
