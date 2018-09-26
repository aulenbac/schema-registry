# schema-registry

One of the other components we need in the USGS Biogeographic Information System is a bschema registry where we bring together all of the detailed documentation on data models we are building and exposing through the bis-api. The API is an initial motivator for this work where we need to provide detailed documentation on every API method response. There are lots of ways we could go about this work, and we are taking into account other major use cases of needing to consult models and individual properties in the registry for the "mystery data sniffing" use case we first explored under the EarthCube DigitalCrust project some time ago.

In the near term, we are using this repo to collaborate on building json-schema docs that will be contributed to and versioned by folks across our team. These docs will be pulled into a common index and exposed via the bis-api for immediate uses, and we will work on evolving the concept as we progress.
