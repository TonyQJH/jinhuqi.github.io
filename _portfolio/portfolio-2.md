---
title: "Vector-RAG: Optimizing Hallucination Issues in LLMs through Retrieval Augmented Generation"
excerpt: "Combining LLMs with vector databases to enhance recommendation systems and reduce hallucinations<br/><img src='/images/tibet_vectorRAG.jpg'>"
collection: portfolio
---
![WorkFlow](https://tonyqjh.github.io/jinhuqi.github.io/images/tibet_vectorRAG.jpg)

Building on our previous work, we explored the hallucination problem in LLMs by utilizing **Retrieval-Augmented Generation (RAG)**, a technique that retrieves relevant information from a database before generating responses. I collected data on tourist attractions in Tibet, converting it into vectors using pre-trained **BERT** and **TF-IDF** models, which were stored in an **FAISS vector database**. User queries were also converted into vectors, and we tested various retrieval methods to search the database.

We achieved **65% accuracy** in retrieving the top three relevant results. The retrieved information was passed to the LLM, improving its quality score from **0.7429 to 0.9225** using RAG. Our results were published in **AIPR 2024**, demonstrating that **Vector-RAG** effectively addressed hallucination and personalization challenges in LLM-based tourism recommendation systems. You can find the paper [here](https://arxiv.org/abs/2408.12003).
