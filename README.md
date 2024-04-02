# OpenAI vs open-source multilingual embeddings models

<a href="https://colab.research.google.com/github/Yannael/multilingual-embeddings/blob/main/Multilingual_Embeddings_OpenAI_vs_OpenSource.ipynb)" target="_blank"><img align="center" src="https://colab.research.google.com/assets/colab-badge.svg" /></a>

This noteboook provides example code to assess which embedding model works best for your data. The example task is a retrieval task (as in RAG - retrieval augmented generation), on multilingual data. See associated Medium article [here](https://medium.com/p/e5ccb7c90f05).

The data source is based on the European AI Act, and models cover some of the latest OpenAI and open-source embeddings models (as of 02/2024) to deal with multilingual data:

OpenAI released [two models](https://openai.com/blog/new-embedding-models-and-api-updates) in January 2024:

- text-embedding-3-small (released 25/01/2024)
- text-embedding-3-large (released 25/01/2024)

We compare with the following open-source models

- [e5-mistral-7b-instruct](https://huggingface.co/intfloat/e5-mistral-7b-instruct) (released 04/01/2024)
- [multilingual-e5-large-instruct](https://huggingface.co/intfloat/multilingual-e5-large-instruct) (released 08/02/2024)
- [BGE-M3](https://huggingface.co/BAAI/bge-m3) (released 29/01/2024)
- [nomic-embed-text-v1](https://huggingface.co/nomic-ai/nomic-embed-text-v1) (released 10/02/2024)
