# README

## Top-level Schemas

-   [Component](./component.md "Component ID along with its list of attributes") – `https://variate.ca/definitions/component.json`
-   [Environment](./status.md "Represent the environment of an experiment") – `https://variate.ca/definitions/environment.json`
-   [Experiment](./experiment.md "The experiment object contains the experiment ID, name, status, targeting information and list of variations included in this experiment") – `https://variate.ca/definitions/experiment.json`
-   [ID](./id.md "Identifier type used within Variate") – `https://variate.ca/definitions/id.json`
-   [Percentage](./percentage.md "Percentage value type") – `https://variate.ca/definitions/percentage.json`
-   [Segments](./segments.md "Segments are defined using JSON logic (see http&#x3A;//jsonlogic") – `https://variate.ca/definitions/segments.json`
-   [Traffic](./traffic.md "The traffic object contains a minimum and maximum percentage of traffic") – `https://variate.ca/definitions/traffic.json`
-   [Variable](./variable.md "Key/value pair representing a variable, usually children of components") – `https://variate.ca/definitions/variable.json`
-   [Variate](./variate.md "JSON Schema to define how the Variate config") – `https://variate.ca/variate.schema.json`
-   [Variation](./variation.md "The variation object contains the variation ID, traffic allocation information and the list of components for this variation") – `https://variate.ca/definitions/variation.json`
-   [Views](./views.md "The views object contains two arrays: include and exclude") – `https://variate.ca/definitions/views.json`

## Other Schemas

### Objects

-   [Component](./variation-properties-component-list-patternproperties-component.md "Component ID along with its list of attributes") – `https://variate.ca/definitions/component.json#/properties/components/patternProperties/[a-zA-Z0-9]+`
-   [Component list](./variation-properties-component-list.md) – `https://variate.ca/definitions/variation.json#/properties/components`
-   [Component list](./variation-properties-component-list.md) – `https://variate.ca/definitions/variation.json#/properties/components`
-   [Experiment](./variate-properties-experiments-list-patternproperties-experiment.md "The experiment object contains the experiment ID, name, status, targeting information and list of variations included in this experiment") – `https://variate.ca/definitions/experiment.json#/properties/experiments/patternProperties/[a-zA-Z0-9]+`
-   [Experiment Targeting Schema](./experiment-properties-experiment-targeting-schema.md) – `https://variate.ca/definitions/experiment.json#/properties/targeting`
-   [Experiment Targeting Schema](./experiment-properties-experiment-targeting-schema.md) – `https://variate.ca/definitions/experiment.json#/properties/targeting`
-   [Experiment Variations Schema](./experiment-properties-experiment-variations-schema.md) – `https://variate.ca/definitions/experiment.json#/properties/variations`
-   [Experiment Variations Schema](./experiment-properties-experiment-variations-schema.md) – `https://variate.ca/definitions/experiment.json#/properties/variations`
-   [Experiments List](./variate-properties-experiments-list.md) – `#/properties/experiments#/properties/experiments`
-   [Segments](./experiment-properties-experiment-targeting-schema-properties-segments.md "Segments are defined using JSON logic (see http&#x3A;//jsonlogic") – `https://variate.ca/definitions/segments.json#/properties/targeting/properties/segments`
-   [Traffic](./variation-properties-traffic.md "The traffic object contains a minimum and maximum percentage of traffic") – `https://variate.ca/definitions/traffic.json#/properties/trafficAllocation`
-   [Variable](./component-properties-variable.md "Key/value pair representing a variable, usually children of components") – `https://variate.ca/definitions/variable.json#/properties/variables`
-   [Variation](./experiment-properties-experiment-variations-schema-patternproperties-variation.md "The variation object contains the variation ID, traffic allocation information and the list of components for this variation") – `https://variate.ca/definitions/variation.json#/properties/variations/patternProperties/[a-zA-Z0-9]+`
-   [Views](./experiment-properties-experiment-targeting-schema-properties-views.md "The views object contains two arrays: include and exclude") – `https://variate.ca/definitions/views.json#/properties/targeting/properties/views`

### Arrays

-   [Untitled array in Views](./views-properties-include.md) – `https://variate.ca/definitions/views.json#/properties/include`
-   [Untitled array in Views](./views-properties-exclude.md) – `https://variate.ca/definitions/views.json#/properties/exclude`
-   [Untitled array in Views](./views-properties-include.md) – `https://variate.ca/definitions/views.json#/properties/include`
-   [Untitled array in Views](./views-properties-exclude.md) – `https://variate.ca/definitions/views.json#/properties/exclude`

## Version Note

The schemas linked above follow the JSON Schema Spec version: `http://json-schema.org/draft-07/schema#`
