# AWS-Certified-Generative-AI-Developer-Professional

## Choosing a Database (Knowledge Base Data Store) for RAG.

- You should just use whatever database is appropriate for the types of data you are retrieving.
- Graph Database
- RAG mostly uses a Vector Database.
- Elasticsearch / Opensearch can function as vector DB.

### What is embedding?
- An embedding is just a **big vector** associated with your data.
- Think of it as a point in **multidimensional space** (Typically 100's or thousands of dimensions).
- Embeddings are **computed** such that **items** that are **similar to each other** are **close to each other** in that space.
- We can use **embedding** base models like (Titan) to compute them enmasse.
