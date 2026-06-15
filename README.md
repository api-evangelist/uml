# UML (uml)

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
