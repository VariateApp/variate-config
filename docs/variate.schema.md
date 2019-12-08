# Variate Schema

```
https://variate.ca/variate.schema.json
```

JSON Schema to define how the Variate config.json file should look like.

| Abstract            | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In                                 |
| ------------------- | ---------- | ------ | ------------ | ----------------- | --------------------- | ------------------------------------------ |
| Can be instantiated | No         | Beta   | No           | Forbidden         | Forbidden             | [variate.schema.json](variate.schema.json) |

# Variate Properties

| Property        | Type     | Required     | Nullable | Defined by            |
| --------------- | -------- | ------------ | -------- | --------------------- |
| [draft](#draft) | `object` | **Required** | No       | Variate (this schema) |
| [live](#live)   | `object` | **Required** | No       | Variate (this schema) |

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

| Property  | Type       | Required     |
| --------- | ---------- | ------------ |
| `buckets` | array      | **Required** |
| `max`     | Percentage | **Required** |
| `min`     | Percentage | **Required** |

#### buckets

`buckets`

- is **required**
- type: Bucket

##### buckets Type

Array type: Bucket

All items must be of the type:

- [Bucket](definitions/bucket.schema.md) – `https://variate.ca/definitions/bucket.json`

#### max

`max`

- is **required**
- type: Percentage

##### max Type

- [Percentage](definitions/percentage.schema.md) – `https://variate.ca/definitions/percentage.json`

#### min

`min`

- is **required**
- type: Percentage

##### min Type

- [Percentage](definitions/percentage.schema.md) – `https://variate.ca/definitions/percentage.json`

#### experiments

##### The Experiments Schema

`experiments`

- is **required**
- type: Experiment

##### experiments Type

Array type: Experiment

All items must be of the type:

- [Experiment](definitions/experiment.schema.md) – `https://variate.ca/definitions/experiment.json`

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

| Property  | Type       | Required     |
| --------- | ---------- | ------------ |
| `buckets` | array      | **Required** |
| `max`     | Percentage | **Required** |
| `min`     | Percentage | **Required** |

#### buckets

`buckets`

- is **required**
- type: Bucket

##### buckets Type

Array type: Bucket

All items must be of the type:

- [Bucket](definitions/bucket.schema.md) – `https://variate.ca/definitions/bucket.json`

#### max

`max`

- is **required**
- type: Percentage

##### max Type

- [Percentage](definitions/percentage.schema.md) – `https://variate.ca/definitions/percentage.json`

#### min

`min`

- is **required**
- type: Percentage

##### min Type

- [Percentage](definitions/percentage.schema.md) – `https://variate.ca/definitions/percentage.json`

#### experiments

##### Experiments List

`experiments`

- is **required**
- type: Experiment

##### experiments Type

Array type: Experiment

All items must be of the type:

- [Experiment](definitions/experiment.schema.md) – `https://variate.ca/definitions/experiment.json`
