---
title: "Graph-RAG: Integrating Knowledge Graphs for Improved Interpretability"
excerpt: "Using knowledge graphs to optimize hallucination issues in LLMs and improve interpretability.<br/><img src='https://tonyqjh.github.io/jinhuqi.github.io/images/tibet_graphrag.png'>"
collection: portfolio
---
![WorkFlow](https://tonyqjh.github.io/jinhuqi.github.io/images/tibet_graphrag.png){: .align-right width="300px"}

In collaboration with **Professor Wang**, I continued research on a project aimed at integrating **knowledge graphs** with **LLMs** to address the hallucination problem. Our goal was to transform the "black box" logic of LLMs into a more interpretable "white box" system, where users could understand how the model reaches its conclusions.

By leveraging **Microsoft's prompt engineering techniques**, we automatically generated knowledge graph triples based on Tibetan tourist attractions. I developed a function-calling LLM mechanism that accurately extracted triple keywords from user queries, improving extraction accuracy by **7%** compared to a fine-tuned LLM.

We also built two retrieval engines for the knowledge graph: **logical chain retrieval** and **multi-node brute-force retrieval**. A user survey of 100 participants revealed that **Graph-RAG**, when combined with the logical chain retrieval engine, resulted in a **60% higher user preference** than the baseline LLM.

Our research shows that integrating **knowledge graphs** with LLMs significantly reduces hallucinations and enhances user satisfaction by making the reasoning process more transparent. Moving forward, I plan to refine our knowledge graph construction and retrieval methods to further improve LLM performance across various domains. Paper will be coming [here]()!
