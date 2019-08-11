# Variate configuration file schema. Schema

```
https://variate.ca/config.schema.json
```

| Abstract            | Extensible | Status       | Identifiable | Custom Properties | Additional Properties | Defined In                                 |
| ------------------- | ---------- | ------------ | ------------ | ----------------- | --------------------- | ------------------------------------------ |
| Can be instantiated | No         | Experimental | No           | Forbidden         | Permitted             | [variate.schema.json](variate.schema.json) |

# Variate configuration file schema. Properties

| Property        | Type     | Required     | Nullable | Defined by                                       |
| --------------- | -------- | ------------ | -------- | ------------------------------------------------ |
| [draft](#draft) | `object` | **Required** | No       | Variate configuration file schema. (this schema) |
| [live](#live)   | `object` | **Required** | No       | Variate configuration file schema. (this schema) |
| `*`             | any      | Additional   | Yes      | this schema _allows_ additional properties       |

## draft

### Draft experiments

`draft`

- is **required**
- type: `object`
- defined in this schema

### draft Type

`object` with following properties:

| Property      | Type   | Required     |
| ------------- | ------ | ------------ |
| `bucketed`    | object | **Required** |
| `experiments` | array  | **Required** |

#### bucketed

##### Use bucketed experiments to run experiments on a subset of your traffic.

`bucketed`

- is **required**
- type: `object`

##### bucketed Type

`object` with following properties:

| Property  | Type              | Required     |
| --------- | ----------------- | ------------ |
| `buckets` | array             | **Required** |
| `max`     | percentage.schema | **Required** |
| `min`     | percentage.schema | **Required** |

#### buckets

`buckets`

- is **required**
- type: Bucket definition

##### buckets Type

Array type: Bucket definition

All items must be of the type:

- [Bucket definition](definitions/bucket.schema.md) – `https://variate.ca/definitions/bucket.json`

#### max

`max`

- is **required**
- type: percentage.schema

##### max Type

- [percentage.schema](definitions/percentage.schema.md) – `https://variate.ca/definitions/percentage.json`

#### min

`min`

- is **required**
- type: percentage.schema

##### min Type

- [percentage.schema](definitions/percentage.schema.md) – `https://variate.ca/definitions/percentage.json`

#### experiments

##### The Experiments Schema

`experiments`

- is **required**
- type: Experiment Schema

##### experiments Type

Array type: Experiment Schema

All items must be of the type:

- [Experiment Schema](definitions/experiment.schema.md) – `https://variate.ca/definitions/experiment.json`

## live

### Live experiments bucketed or audience-wide.

`live`

- is **required**
- type: `object`
- defined in this schema

### live Type

`object` with following properties:

| Property      | Type   | Required     |
| ------------- | ------ | ------------ |
| `bucketed`    | object | **Required** |
| `experiments` | array  | **Required** |

#### bucketed

##### Use bucketed experiments to run experiments on a subset of your traffic.

`bucketed`

- is **required**
- type: `object`

##### bucketed Type

`object` with following properties:

| Property  | Type              | Required     |
| --------- | ----------------- | ------------ |
| `buckets` | array             | **Required** |
| `max`     | percentage.schema | **Required** |
| `min`     | percentage.schema | **Required** |

#### buckets

`buckets`

- is **required**
- type: Bucket definition

##### buckets Type

Array type: Bucket definition

All items must be of the type:

- [Bucket definition](definitions/bucket.schema.md) – `https://variate.ca/definitions/bucket.json`

#### max

`max`

- is **required**
- type: percentage.schema

##### max Type

- [percentage.schema](definitions/percentage.schema.md) – `https://variate.ca/definitions/percentage.json`

#### min

`min`

- is **required**
- type: percentage.schema

##### min Type

- [percentage.schema](definitions/percentage.schema.md) – `https://variate.ca/definitions/percentage.json`

#### experiments

##### Experiments List

`experiments`

- is **required**
- type: Experiment Schema

##### experiments Type

Array type: Experiment Schema

All items must be of the type:

- [Experiment Schema](definitions/experiment.schema.md) – `https://variate.ca/definitions/experiment.json`
