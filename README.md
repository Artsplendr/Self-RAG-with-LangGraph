# Self-RAG-with-LangGraph

## Project Goal
The goal of this project is to experiment with Self-RAG with LangGraph.  This project is based on ["Self-Reflective RAG with LangGraph"](https://blog.langchain.dev/agentic-rag-with-langgraph/) blog by LangChain Team.

## Self-RAG Introduction

Large Language Models (LLMs), can generate impressive text but often produce **factually incorrect responses** because they rely on **pre-trained knowledge** and don’t dynamically verify facts. To solve this, researchers have developed **Self-Reflective Retrieval-Augmented Generation (Self-RAG)**—a framework that enables LLMs to fetch relevant external information **when needed** and **self-assess** their own outputs for accuracy and reliability.

## How Self-RAG Works

Self-RAG improves the traditional Retrieval-Augmented Generation (RAG) process by introducing three core components:

**1.  Adaptive Retrieval:**

* Unlike standard retrieval models, which fetch a fixed number of documents, Self-RAG allows the model to determine when and what information to retrieve based on the complexity of the question.
* This helps the model avoid unnecessary information overload and focus only on relevant data.
* 
**2.  Response Generation:**

* After retrieving information, the LLM integrates it into a coherent and accurate response.

**3.  Self-Reflection with Specialized Tokens:**

* Self-RAG uses reflection tokens that allow the model to evaluate its own response in real time.
* These special tokens are embedded in the model’s reasoning process to check and refine the accuracy of its generated responses.

## References

1. [“Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection" ](https://arxiv.org/abs/2310.11511)by Akari Asai, Zeqiu Wu, Yizhong Wang, Avirup Sil, Hannaneh Hajishirzi. 2023

2. ["Self-Reflective RAG with LangGraph"](https://blog.langchain.dev/agentic-rag-with-langgraph/) blog is available at LangChain.


If you find this repository useful, light the star ⭐:)! 
