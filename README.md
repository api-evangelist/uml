# UML

UML (Unified Modeling Language) is the standard modeling language for software architecture, system design, and technical documentation. Governed by the Object Management Group (OMG), UML defines a set of notation conventions and diagram types — class, sequence, activity, use case, state, component, deployment, and more — used across the software development lifecycle.

This collection profiles the ecosystem of tools, APIs, and services that work with UML diagrams programmatically.

## APIs

### PlantUML Server API

The PlantUML Server provides a public REST API for generating UML diagrams from plain-text descriptions. The diagram source is encoded into the URL path using a deflate + base64 algorithm. Multiple output formats are supported including PNG, SVG, ASCII art, and PDF.

- **Base URL:** https://www.plantuml.com/plantuml
- **Documentation:** https://plantuml.com/
- **OpenAPI:** [openapi/plantuml-server-openapi.yml](openapi/plantuml-server-openapi.yml)

### Kroki Diagram API

Kroki provides a unified HTTP API for generating diagrams from textual descriptions. It supports over 20 diagram types including PlantUML, Mermaid, GraphViz, BlockDiag, BPMN, C4, Structurizr, Excalidraw, Vega, WaveDrom, and more.

- **Base URL:** https://kroki.io
- **Documentation:** https://docs.kroki.io/kroki/
- **OpenAPI:** [openapi/kroki-openapi.yml](openapi/kroki-openapi.yml)

## Artifacts

### OpenAPI Specs

| File | Description |
|------|-------------|
| [openapi/plantuml-server-openapi.yml](openapi/plantuml-server-openapi.yml) | PlantUML Server REST API — PNG, SVG, ASCII, PDF, and validation endpoints |
| [openapi/kroki-openapi.yml](openapi/kroki-openapi.yml) | Kroki Unified Diagram API — GET and POST rendering for 20+ diagram types |

### JSON Schema

| File | Description |
|------|-------------|
| [json-schema/uml-diagram-schema.json](json-schema/uml-diagram-schema.json) | Schema for a UML diagram definition including type, source, format, and output metadata |

### JSON Structure

| File | Description |
|------|-------------|
| [json-structure/uml-diagram-structure.json](json-structure/uml-diagram-structure.json) | Field-level documentation for the UML Diagram entity |

### JSON-LD

| File | Description |
|------|-------------|
| [json-ld/uml-context.jsonld](json-ld/uml-context.jsonld) | JSON-LD context mapping UML terms to schema.org and UML ontology vocabulary |

### Examples

| File | Description |
|------|-------------|
| [examples/plantuml-get-diagram-png-example.json](examples/plantuml-get-diagram-png-example.json) | Example GET request to PlantUML Server for PNG diagram rendering |
| [examples/kroki-post-diagram-example.json](examples/kroki-post-diagram-example.json) | Example POST request to Kroki for Mermaid SVG rendering |

### Spectral Rules

| File | Description |
|------|-------------|
| [rules/uml-rules.yml](rules/uml-rules.yml) | Spectral ruleset enforcing API design conventions for UML diagram services |

### Vocabulary

| File | Description |
|------|-------------|
| [vocabulary/uml-vocabulary.yml](vocabulary/uml-vocabulary.yml) | Domain vocabulary covering UML diagram types, notation, tools, API concepts, and governance |

## Related Resources

- [OMG UML Specification](https://www.omg.org/uml/)
- [PlantUML GitHub](https://github.com/plantuml/plantuml)
- [Kroki GitHub](https://github.com/yuzutech/kroki)
- [Wikipedia: Unified Modeling Language](https://en.wikipedia.org/wiki/Unified_Modeling_Language)
