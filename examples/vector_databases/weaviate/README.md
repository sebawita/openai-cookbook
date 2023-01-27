# Weaviate <> OpenAI

[​Weaviate](https://weaviate.io) is an open-source vector search engine ([docs](https://weaviate.io/developers/weaviate) - [Github](https://github.com/weaviate/weaviate)) that can store and search through OpenAI embeddings _and_ data objects. The database allows you to do similarity search, hybrid search (the combining of multiple search techniques, such as keyword-based and vector search), and generative search (like Q&A). Weaviate also supports a wide variety of OpenAI-based modules (e.g., [`text2vec-openai`](https://weaviate.io/developers/weaviate/modules/retriever-vectorizer-modules/text2vec-openai), [`qna-openai`](https://weaviate.io/developers/weaviate/modules/reader-generator-modules/qna-openai)), allowing you to vectorize and query data fast and efficiently.

This folder contains a variety of Weaviate and OpenAI examples. 

| Name | Description | lanugage |
| --- | --- | --- |
| [Getting Started with Weaviate and OpenAI](./getting-started-with-weaviate-and-openai.ipynb) | A simple getting started guide for Weaviate using the OpenAI vectorization module `text2vec-openai` | Python |