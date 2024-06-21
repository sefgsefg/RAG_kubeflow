# RAG Component

This is a Kubeflow pipeline component that retrieves answers from a provided document using a Retrieval-Augmented Generation (RAG) approach. The component utilizes various libraries such as `langchain`, `pinecone`, and `transformers` to process a PDF document, create embeddings, and generate answers based on the retrieved content.

## Prework

### Pinecone 
---
In this example, we use pinecone to create a vector database. Create an account and create an index, enter the index name, dimensions, enter 384 and then create the index
![](https://github.com/sefgsefg/RAG_kubeflow/blob/main/Pinecone_create_index.png)
