# API Commons API Snack for AI — Send a Message with Twilio

This is an **API Snack** for artificial intelligence (AI): a single, machine-readable definition of one useful API-powered capability — sending a message with the [Twilio](https://www.twilio.com) API — packaged with the supporting semantics and properties an agent needs to understand and use it.

An API Snack narrows a large provider API down to one focused capability and bundles everything an AI application needs to invoke it: the operation definition, ready-to-run tooling, and the surrounding context (documentation, signup, pricing, and terms of service) expressed as machine-readable [APIs.json](https://apisjson.org) with linked [Schema.org](https://schema.org) semantics.

## What's in this repo

- [apis.yml](apis.yml) — The APIs.json (`type: Snack`, specification 0.19) index that ties everything together: the `Send Twilio Message` operation and its linked artifacts, plus `Documentation`, `Signup`, `Pricing`, and `TermsOfService` common properties, each annotated with JSON-LD (`HowTo`, `RegisterAction`, `PriceSpecification`, `Service`).
- [openapi.yml](openapi.yml) — The OpenAPI definition for the single "send a message" operation.
- [postman.json](postman.json) — A Postman collection for exercising the operation.
- [Send Message with Twilio.postman_environment.json](Send%20Message%20with%20Twilio.postman_environment.json) — A Postman environment with the variables the collection expects.

## How it fits API Commons

Snacks are one of the [API Commons](https://apicommons.org) building blocks aimed squarely at the agent layer: instead of pointing an AI at a whole provider API, you hand it one small, well-described, ready-to-use capability. Each Snack is discoverable and reusable alongside every other artifact in the [APIs.io](https://apis.io) catalog.

## Support
If you have any questions please [submit an issue](https://github.com/api-commons/snacks-twilio-messages/issues/new) or feel free to email [kin@apievangelist.com](mailto:kin@apievangelist.com), and I will see how I can help.

## Part of API Commons

A machine-readable building block from **[API Commons](https://apicommons.org)** — open specifications and schemas for the APIs you produce and consume. See all building blocks and tools at **[apicommons.org](https://apicommons.org)** and the tools at **[apicommons.org/tools](https://apicommons.org/tools/)**.

**Related building blocks**
- [examples](https://github.com/api-commons/examples) — shared request/response examples for API operations
- [api-onboarding](https://github.com/api-commons/api-onboarding) — the API Onboarding Descriptor (AID) for what it takes to onboard with a provider like Twilio
- [train-travel](https://github.com/api-commons/train-travel) — a full APIs.json + OpenAPI template for a complete example API
