# WSDL (wsdl)

WSDL (Web Services Description Language) is a W3C standard XML format for describing web
service interfaces. It defines services as collections of network endpoints (ports) that exchange
messages, specifying the abstract operations, message formats, and protocol bindings needed to
interact with a web service. WSDL 2.0 became a W3C Recommendation on June 26, 2007, and adds
support for all HTTP request methods, making it more suitable for RESTful web services than
its predecessor WSDL 1.1.

**URL:** [https://www.w3.org/TR/wsdl20/](https://www.w3.org/TR/wsdl20/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Service Description, W3C, Web Services, WSDL, XML, SOAP, Standards, Protocols

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-03

## Common Properties

- [WSDL 2.0 Part 1 Core Language](https://www.w3.org/TR/wsdl20/)
- [WSDL 2.0 Part 2 Adjuncts](https://www.w3.org/TR/wsdl20-adjuncts/)
- [WSDL 2.0 Part 0 Primer](https://www.w3.org/TR/wsdl20-primer/)
- [WSDL 2.0 RDF Mapping](https://www.w3.org/TR/wsdl20-rdf/)
- [W3C Web Services Activity](https://www.w3.org/standards/techs/wsdl)
- [W3C GitHub](https://github.com/w3c)
- [W3C Web Services Discussion](https://lists.w3.org/Archives/Public/public-ws-desc/)

## Features

| Name | Description |
|------|-------------|
| Abstract Service Interface | Defines abstract interfaces separating service contract from protocol binding. |
| Message Exchange Patterns | Supports In-Only, Robust In-Only, and In-Out message exchange patterns. |
| SOAP Binding | Native SOAP 1.2 binding for web service interoperability. |
| HTTP Binding | HTTP binding supporting all HTTP methods including GET, POST, PUT, DELETE. |
| RPC Style Operations | RPC-style operation dispatch with input and output message wrappers. |
| Type System Integration | Integrates with XML Schema for defining message types. |
| Multiple Endpoints | Supports multiple endpoints per service with different protocol bindings. |
| Namespace and Modularity | Uses XML namespaces to enable modular and reusable service descriptions. |
| Operation Safety Declaration | Allows marking safe read-only operations per web architecture principles. |
| RDF Mapping | Normative mapping to RDF for linked data and semantic web integration. |

## Use Cases

| Name | Description |
|------|-------------|
| SOAP Web Service Description | Describing enterprise SOAP web services for automated client generation. |
| Service Contract Definition | Defining service contracts between service providers and consumers. |
| Code Generation | Generating client proxy code and server stubs from WSDL documents. |
| Service Discovery | Enabling automated discovery and invocation of web services. |
| Interoperability Testing | Validating interoperability between different SOAP implementations. |
| REST Service Description | Describing RESTful services using WSDL 2.0 HTTP binding support. |

## Integrations

| Name | Description |
|------|-------------|
| XML Schema | WSDL 2.0 uses XML Schema for type definitions. |
| SOAP 1.2 | Native SOAP 1.2 binding defined in WSDL 2.0 Part 2. |
| HTTP 1.1 | HTTP binding supporting REST-style services. |
| UDDI | WSDL documents are referenced in UDDI service registries. |
| WS-Policy | Web services policy framework that annotates WSDL descriptions. |
| WS-Addressing | Endpoint reference standards used with WSDL service endpoints. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [WSDL Description](json-schema/wsdl-description.json)
- [WSDL Types](json-schema/wsdl-types.json)
- [WSDL Interface](json-schema/wsdl-interface.json)
- [WSDL Operation](json-schema/wsdl-operation.json)
- [WSDL Interface Fault](json-schema/wsdl-interface-fault.json)
- [WSDL Binding](json-schema/wsdl-binding.json)
- [WSDL Service](json-schema/wsdl-service.json)
- [WSDL Endpoint](json-schema/wsdl-endpoint.json)

### JSON Structure

- [WSDL Description Structure](json-structure/wsdl-description-structure.json)
- [WSDL Types Structure](json-structure/wsdl-types-structure.json)
- [WSDL Interface Structure](json-structure/wsdl-interface-structure.json)
- [WSDL Operation Structure](json-structure/wsdl-operation-structure.json)
- [WSDL Interface Fault Structure](json-structure/wsdl-interface-fault-structure.json)
- [WSDL Binding Structure](json-structure/wsdl-binding-structure.json)
- [WSDL Service Structure](json-structure/wsdl-service-structure.json)
- [WSDL Endpoint Structure](json-structure/wsdl-endpoint-structure.json)

### JSON-LD

- [WSDL JSON-LD Context](json-ld/wsdl-context.jsonld)

## Vocabulary

- [WSDL Vocabulary](vocabulary/wsdl-vocabulary.yaml) — Unified taxonomy mapping 8 resources, 8 actions, 0 workflows, and 0 personas across the WSDL 2.0 specification domain.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
