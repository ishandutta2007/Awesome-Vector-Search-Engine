# Awesome-Vector-Search-Engine

## Top Vector Search Engine Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on AI-First Search, Hybrid Keyword + Vector Retrieval, Enterprise Search & Semantic Engines*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Vector Search Engines**. These systems combine dense vector similarity with classical search—powering site search, enterprise knowledge retrieval, RAG, and AI-first discovery experiences.



**Examples** include Elastic Enterprise Search, Algolia, Coveo, Sinequa, Lucidworks Fusion, Amazon Kendra, Google Cloud Search, Pinecone, Weaviate, Qdrant, and **Weaviate** (`weaviate/weaviate`)—an open-source AI-first vector search engine.



**Open-source emphasis**: Vector and hybrid search engines are strongly open. **Weaviate**, **Qdrant**, **Milvus**, **OpenSearch**, **Elasticsearch**, **Typesense**, **Meilisearch**, and **Vespa** cover the spectrum from pure vector DB to full search platforms. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Algolia, Coveo, Elastic Enterprise Search, Lucidworks, Sinequa](https://www.algolia.com/)**  

  Enterprise and site-search platforms—relevance tuning, analytics, and increasingly hybrid vector capabilities.



- **[Amazon Kendra, Google Cloud Search, Azure AI Search](https://aws.amazon.com/kendra/)**  

  Cloud enterprise search services with connectors, ranking, and semantic features.



- **[Pinecone, Weaviate Cloud, Qdrant Cloud, Zilliz](https://www.pinecone.io/)**  

  Managed vector-first engines used as the retrieval layer for AI applications.



- **[Other commercial AI search platforms](https://www.coveo.com/)**  

  Additional relevance and generative-search products.



## Open-Source GitHub Projects



### AI-First / Vector Search Engines



- **[Weaviate](https://github.com/weaviate/weaviate)**  

  Open-source AI-first vector search engine—vector and hybrid search, modular vectorizers, and GraphQL/REST APIs.



- **[Qdrant](https://github.com/qdrant/qdrant)**  

  Open vector search engine in Rust—rich filtering, payloads, and production-focused ANN retrieval.



- **[Milvus](https://github.com/milvus-io/milvus)**  

  Open distributed vector database—large-scale similarity search with multiple index types.



- **[Vespa](https://github.com/vespa-engine/vespa)**  

  Open search and serving engine—hybrid ranking, vectors, and big-data scale query execution.



- **[Chroma](https://github.com/chroma-core/chroma)**  

  Open embedding store widely used in LLM/RAG prototypes and apps.



### Full-Text & Hybrid Search Platforms



- **[OpenSearch](https://github.com/opensearch-project/OpenSearch)**  

  Open search and analytics suite—k-NN vector plugin, full-text, and enterprise search patterns.



- **[Elasticsearch](https://github.com/elastic/elasticsearch)**  

  Widely deployed open search engine (license evolved)—dense vector fields and hybrid retrieval features.



- **[Typesense](https://github.com/typesense/typesense)**  

  Open fast typo-tolerant search engine—developer-friendly APIs and growing vector features.



- **[Meilisearch](https://github.com/meilisearch/meilisearch)**  

  Open lightweight search engine—instant search UX and hybrid/vector capabilities in recent versions.



- **[Apache Solr](https://github.com/apache/solr)**  

  Open enterprise search platform built on Lucene—mature full-text with extension paths for vectors.



- **[ZincSearch / other lightweight engines](https://github.com/zincsearch/zincsearch)**  

  Community search engines aimed at simpler self-hosted deployment.



### Libraries & Building Blocks



- **[Faiss](https://github.com/facebookresearch/faiss)**  

  Open similarity search library—core ANN indexes embedded in many engines.



- **[hnswlib](https://github.com/nmslib/hnswlib)**  

  Open HNSW implementation used across the vector search ecosystem.



- **[pgvector](https://github.com/pgvector/pgvector)**  

  Open PostgreSQL extension for vector search beside relational data.



- **[Lucene](https://github.com/apache/lucene)**  

  Foundational open search library under Solr and OpenSearch/Elasticsearch lineages.



### Additional Strong Open-Source Options



- **AI-first vector engine**: Weaviate or Qdrant.

- **Distributed vector scale**: Milvus.

- **Hybrid enterprise search**: OpenSearch or Vespa.

- **Simple product search**: Typesense or Meilisearch.

- **SQL + vectors**: pgvector.

- **Composable stacks**: Embeddings → Weaviate/Qdrant/Milvus → app; or OpenSearch hybrid for keyword + k-NN.

- Commercial search still leads for connectors, relevance consulting, and fully managed enterprise SLAs.



**Frameworks for building custom systems**:  

**Weaviate** for AI-first hybrid search; **Qdrant**/**Milvus** for pure vector workloads; **OpenSearch**/**Vespa** when classical search + vectors must coexist at scale.  

Fully open vector search engines are production-ready for RAG, semantic site search, and internal knowledge bases.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Search quality depends on embeddings, ranking, and data hygiene—not only the engine. Protect indexes that contain private documents. Test recall/latency on your corpus before production cutover.

- Open-source engines offer control and portability. Managed search shifts operations and often relevance tooling to the vendor. Neither replaces content quality and evaluation of search success metrics.



---



**Made for search engineers, platform teams, and builders of AI retrieval systems.**  

Let's expand open vector search engines while recognizing the connector and relevance depth that leading commercial search platforms deliver.
