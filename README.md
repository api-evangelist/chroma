# Chroma (chroma)

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

Chroma (Chroma DB) is an open-source AI-native embedding database designed to make it easy to build LLM applications by providing storage, retrieval, and management for vector embeddings, full-text search, regex search, and multi-modal retrieval (text, image, audio). Distributed under the Apache 2.0 license, Chroma can be self-hosted (single-node Python or distributed Rust-based deployment) or consumed via Chroma Cloud, a managed serverless vector database service offering usage-based pricing. Chroma is the open-source data infrastructure for AI agents and RAG (Retrieval-Augmented Generation) applications, with first-party SDKs for Python and JavaScript/TypeScript and integrations with leading embedding providers (OpenAI, Cohere, Hugging Face, sentence-transformers).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/chroma/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/chroma/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI
- AI Native
- Apache 2.0
- Cloud
- Embeddings
- Hybrid Search
- JavaScript
- LLM
- Machine Learning
- Multi-Modal
- Open Source
- Python
- RAG
- Retrieval
- SDK
- Search
- Serverless
- TypeScript
- Vector Database

## Timestamps

- **Created:** 2025-03-07
- **Modified:** 2026-05-19

## APIs

### Chroma Server API

The Chroma Server API is a REST API that provides access to the Chroma open-source vector database. It enables developers to create and manage collections of embeddings, add documents with automatic tokenization and embedding, and perform vector similarity searches. The API supports metadata filtering, full-text search, and collection management operations. An OpenAPI specification is available at the server endpoint for client generation in various programming languages.

- **Human URL:** [https://docs.trychroma.com/reference/chroma-reference](https://docs.trychroma.com/reference/chroma-reference)
- **Base URL:** `https://api.trychroma.com`

#### Tags

- AI
- Embeddings
- Machine Learning
- Search
- Vector Database

#### Properties

- [Documentation](https://docs.trychroma.com/reference/chroma-reference)
- [OpenAPI](openapi/chroma-server-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chroma-server-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chroma-server-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Chroma Cloud API

Chroma Cloud is a managed, serverless vector database service that provides fast and scalable vector, full-text, and metadata search across terabytes of data. It is backed by Chroma's Apache 2.0 distributed database and offers usage-based pricing with starter and team plans. Developers can connect to Chroma Cloud using the Python or JavaScript client SDKs without needing to manage infrastructure.

- **Human URL:** [https://docs.trychroma.com/cloud/pricing](https://docs.trychroma.com/cloud/pricing)
- **Base URL:** `https://api.trychroma.com`

#### Tags

- AI
- Cloud
- Embeddings
- Serverless
- Vector Database

#### Properties

- [Documentation](https://docs.trychroma.com/cloud/sync/overview)
- [OpenAPI](openapi/chroma-cloud-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chroma-cloud-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chroma-cloud-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Chroma Python Client

The Chroma Python Client is a first-party SDK for interacting with both self-hosted Chroma servers and Chroma Cloud. It provides a simple, developer-friendly interface with a core API of just four functions for managing collections, adding documents, and querying embeddings. The client handles automatic tokenization, embedding, and indexing of documents, making it straightforward to build AI applications that require vector similarity search.

- **Human URL:** [https://docs.trychroma.com/reference/python/client](https://docs.trychroma.com/reference/python/client)

#### Tags

- Embeddings
- Python
- SDK
- Vector Database

#### Properties

- [Documentation](https://docs.trychroma.com/reference/python/client)
- [Source Code](https://github.com/chroma-core/chroma)
- [Postman Collection](collections/chroma-cloud-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chroma-cloud-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chroma-server-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chroma-server-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Chroma JavaScript Client

The Chroma JavaScript and TypeScript Client is a first-party SDK for interacting with Chroma from JavaScript or TypeScript applications. The v3 rewrite focused on reducing bundle size and improving developer experience, making it well-suited for deployment on serverless platforms like Vercel. It supports both self-hosted Chroma instances and Chroma Cloud via the CloudClient class, providing collection management, document ingestion, and vector similarity search capabilities.

- **Human URL:** [https://docs.trychroma.com/reference/js/client](https://docs.trychroma.com/reference/js/client)

#### Tags

- Embeddings
- JavaScript
- SDK
- TypeScript
- Vector Database

#### Properties

- [Documentation](https://docs.trychroma.com/reference/js/client)
- [Source Code](https://github.com/chroma-core/chroma-js)
- [Postman Collection](collections/chroma-cloud-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chroma-cloud-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chroma-server-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chroma-server-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/trychroma)
- [Website](https://www.trychroma.com/)
- [Documentation](https://docs.trychroma.com/docs/overview/introduction)
- [Portal](https://docs.trychroma.com/)
- [Login](https://cloud.trychroma.com/)
- [Pricing](https://docs.trychroma.com/cloud/pricing)
- [Blog](https://www.trychroma.com/blog)
- [Git Hub Org](https://github.com/chroma-core)
- [Source Code](https://github.com/chroma-core/chroma)
- [Discord](https://discord.gg/MMeYNTmh3x)
- [Twitter](https://twitter.com/trychroma)
- [License](https://github.com/chroma-core/chroma/blob/main/LICENSE)
- [Terms of Service](https://www.trychroma.com/tos)
- [Privacy Policy](https://www.trychroma.com/privacy)
- [J S O N L D Context](json-ld/chroma-context.jsonld)
- [JSON Schema](json-schema/chroma-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/chroma-record-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Rules](spectral/chroma-spectral.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)
- [Features](undefined)
- [Embedding Providers](undefined)
- [Use Cases](undefined)
- [Standards](undefined)
- [L L Ms Txt](https://docs.trychroma.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
