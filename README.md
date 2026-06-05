# Chroma (chroma)

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
