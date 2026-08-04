# UML (uml)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

UML (Unified Modeling Language) is the standard modeling language for software architecture, system design, and technical documentation. Governed by the Object Management Group (OMG), UML defines a set of notation conventions and diagram types — class, sequence, activity, use case, state, component, deployment, and more — used across the software development lifecycle. This collection profiles the ecosystem of tools, APIs, and services that work with UML diagrams programmatically.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/uml/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/uml/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- UML
- Modeling
- Diagrams
- Software Architecture
- Design
- Standards

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### PlantUML Server API

PlantUML Server provides a public REST API for generating UML diagrams from plain-text descriptions. Diagrams are encoded in the URL path using a deflate + base64 scheme. The server supports multiple output formats including PNG, SVG, ASCII art, and PDF. Diagram types include class, sequence, activity, component, state, use case, deployment, timing, and more.

- **Human URL:** [https://plantuml.com/](https://plantuml.com/)
- **Base URL:** `https://www.plantuml.com/plantuml`

#### Tags

- UML
- Diagrams
- PlantUML
- Text-To-Diagram

#### Properties

- [Documentation](https://plantuml.com/)
- [Documentation](https://deepwiki.com/plantuml/plantuml-server/6-api-reference)
- [OpenAPI](openapi/plantuml-server-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/plantuml-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plantuml-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kroki Diagram API

Kroki provides a unified HTTP API for generating diagrams from textual descriptions. It supports over 20 diagram types including PlantUML, Mermaid, GraphViz, BlockDiag, BPMN, C4, Structurizr, Excalidraw, Vega, and WaveDrom. Requests can be sent as GET (diagram encoded in URL) or POST (diagram in request body). Output formats include SVG, PNG, PDF, and JPEG. Kroki is open source and can be self-hosted.

- **Human URL:** [https://kroki.io/](https://kroki.io/)
- **Base URL:** `https://kroki.io`

#### Tags

- UML
- Diagrams
- Multi-Format
- Text-To-Diagram
- Open Source

#### Properties

- [Documentation](https://docs.kroki.io/kroki/)
- [Getting Started](https://docs.kroki.io/kroki/setup/usage/)
- [OpenAPI](openapi/kroki-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kroki.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kroki.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Git Hub  Org](https://github.com/plantuml)
- [Git Hub  Org](https://github.com/yuzutech)
- [Website](https://www.omg.org/uml/)
- [Standard](https://www.omg.org/spec/UML/)
- [Wikipedia](https://en.wikipedia.org/wiki/Unified_Modeling_Language)
- [Git Hub](https://github.com/plantuml/plantuml)
- [Git Hub](https://github.com/yuzutech/kroki)
- [Documentation](https://plantuml.com/)
- [Documentation](https://docs.kroki.io/kroki/)
- [JSON-LD](json-ld/uml-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/uml-vocabulary.yml)
- [JSON Schema](json-schema/uml-diagram-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral  Rules](rules/uml-rules.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
