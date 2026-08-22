# WSDL (wsdl)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
