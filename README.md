# Neuro-Symbolic AI Projects Hub

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.8%2B-green.svg)](https://www.python.org/)

A central hub for cutting-edge **Neuro-Symbolic AI** projects—integrating neural networks (e.g., Large Language Models) with symbolic reasoning systems (e.g., ontologies, rule engines) to build more accurate, explainable, and robust AI applications.

---

## Table of Contents

1. [Neuro-Symbolic Interaction](#neuro-symbolic-interaction)
2. [Neuro-Symbolic Ontologic Transformer](#neuro-symbolic-ontologic-transformer)
3. [AI Chatbot with Rules & Ontology (ODM)](#ai-chatbot-with-rules--ontology-odm)
4. [Neuro-Symbolic Decision Trade Compliance](#neuro-symbolic-decision-trade-compliance)
5. [watsonx-NeuroSymbolic-Decision](#watsonx-neurosymbolic-decision)
6. [Neuro-Symbolic Fine-Tuning with Ontology-Guided GRPO](#neuro-symbolic-fine-tuning-with-ontology-guided-grpo)
7. [How to Validate NLP Answers Using Python and Ontologies](#how-to-validate-nlp-answers-using-python-and-ontologies)
8. [Agent-driven Ontology Repair and Evolution (ADORE)](#agent-driven-ontology-repair-and-evolution)
9. [Multi-Agent MCP Stack for Regulatory & Contract Analysis](#multi-agent-mcp-stack-for-regulatory-&-contract-analysis)
---

## Neuro-Symbolic Interaction

**Repository:** [ruslanmv/Neuro-symbolic-interaction](https://github.com/ruslanmv/Neuro-symbolic-interaction)

This repository showcases a focused model designed to enhance the accuracy of Large Language Models (LLMs) by integrating knowledge from an OWL ontology. It provides a practical, single-purpose example of how combining neural and symbolic AI can correct biases and factual errors in LLM outputs. The system not only improves accuracy but also offers logical explanations for its corrections based on the ontology. It features a Gradio-based interface to clearly demonstrate this core neuro-symbolic capability, making it an excellent starting point for understanding the concept.

For a comprehensive description of the methodology and evaluation, please refer to the accompanying paper: [https://arxiv.org/abs/2504.07640](https://arxiv.org/abs/2504.07640).

---

## Neuro-Symbolic Ontologic Transformer

**Repository:** [ruslanmv/Neuro-Symbolic-Ontologic-Tranformer](https://github.com/ruslanmv/Neuro-Symbolic-Ontologic-Tranformer)

This repository is dedicated to the research and development of **Axiom-Guided GPT**, a novel approach to reduce hallucinations in Large Language Models. Rather than a full application, this project focuses on a deep, conceptual mechanism. The core idea is to introduce an axiom-guided check directly into the GPT architecture's token-generation process. By ensuring the generated text adheres to predefined logical rules (axioms), the model can avoid producing factually incorrect statements, leading to more trustworthy AI.

---

## AI Chatbot with Rules & Ontology (ODM)

**Repository:** [ruslanmv/ai-chatbot-rules-ontology-odm](https://github.com/ruslanmv/ai-chatbot-rules-ontology-odm)

This project is a complete, end-to-end tutorial for building an intelligent diagnostic chatbot for engine failures. It details the entire multi-step pipeline, from defining domain knowledge in an OWL ontology, to generating a Java Object Model (XOM) for IBM Operational Decision Manager (ODM), authoring business rules, and connecting it all to a chatbot. It's a comprehensive guide that builds a full, albeit specific, application, demonstrating how multiple symbolic and neural components work together in practice.

---

## Neuro-Symbolic Decision Trade Compliance

**Repository:** [ruslanmv/Neuro-Symbolic-Decision-Trade-Compliance](https://github.com/ruslanmv/Neuro-Symbolic-Decision-Trade-Compliance)

This repository demonstrates a sophisticated, real-world application of a neuro-symbolic framework to solve the highly complex problem of EU-US trade compliance. The system, G-CoW (Granite-Copilot for Workflow), acts as a copilot that uses an LLM to understand user queries and a complex symbolic layer (rules and ontologies) to accurately calculate tariffs based on dynamic 2025 regulations. This project represents a significant step up in complexity due to the intricate and ever-changing nature of the trade compliance domain it tackles.

---

## watsonx-NeuroSymbolic-Decision

**Repository:** [ruslanmv/watsonx-neurosymbolic-decision](https://github.com/ruslanmv/watsonx-neurosymbolic-decision)

This repository contains the most complex and foundational project: a robust, extensible, and generic **framework** for building neuro-symbolic applications. It is not just a single application but a platform designed to support various use cases (like the Trade Compliance project). It provides a complete architecture including a neuro-symbolic agent, connectors for multiple LLMs (watsonx.ai, Ollama) and symbolic systems (ODM, ontologies), sample services, and a chatbot front-end, all containerized. Its nature as a comprehensive, multi-component platform makes it the most complex project in this collection.

---

## Neuro-Symbolic Fine-Tuning with Ontology-Guided GRPO

**Repository:** [ruslanmv/Neuro-Symbolic-Fine-Tuning-with-Ontology-Guided-GRPO](https://github.com/ruslanmv/Neuro-Symbolic-Fine-Tuning-with-Ontology-Guided-GRPO)

This project presents an advanced, end-to-end implementation of fine-tuning a Llama-3.2 model to be more factually consistent. It uses a novel reinforcement learning technique, Generative Reinforcement with Policy Optimization (GRPO), where the reward signal is automatically generated by validating the LLM's output against a formal diabetes ontology. This technically deep tutorial covers LoRA for efficient fine-tuning, building a hybrid neuro-symbolic validator, and using the resulting consistency score to guide the model's training, fundamentally improving its domain awareness.

---

## How to Validate NLP Answers Using Python and Ontologies

**Repository:** [ruslanmv/How-to-Validate-NLP-Answers-Using-Python-and-Ontologies](https://github.com/ruslanmv/How-to-Validate-NLP-Answers-Using-Python-and-Ontologies)

This repository provides a foundational, hands-on tutorial for validating answers from NLP models against a formal knowledge base. Using the Human Phenotype Ontology (HPO) as an example, it walks through a multi-pass validation pipeline with Python. It covers techniques ranging from simple exact and fuzzy string matching to more advanced semantic similarity with embeddings and logical verification using an OWL reasoner. This project is the perfect starting point as it explains the core validation techniques that are essential building blocks for more complex neuro-symbolic systems.



## Agent-driven Ontology Repair and Evolution

**Repository** [ruslanmv/Agent-driven-Ontology-Repair-and-Evolution](https://github.com/ruslanmv/Agent-driven-Ontology-Repair-and-Evolution)

This repository demonstrates **ADORE (Agent-driven Ontology Repair and Evolution)**, a highly advanced conceptual framework for managing how ontologies evolve with input from LLMs. It proposes a multi-agent system where specialized AI agents collaborate to propose, validate, and repair knowledge. When an LLM suggests a new fact that causes a logical inconsistency, the framework treats it as a trigger for a repair cycle, using formal axiom weakening and human-in-the-loop oversight to resolve the conflict. This project represents the cutting edge of research into creating autonomous, reflective, and trustworthy knowledge systems.



## Multi Agent MCP Stack for Regulatory & Contract Analysis

**Repository** [ruslanmv/mcp-graph-rag](https://github.com/ruslanmv/mcp-graph-rag)

Goal A scalable, maintainable solution for hybrid GRAPH-RAG over regulatory corpora (DL/DM, decrees, laws) and contracts. It combines vector search and a knowledge graph, exposed through minimal MCP servers (Knowledge, Writer, Review) orchestrated by a thin Orchestrator and served by a Web BFF/UI. Designed for traceability (citations/“as-of” anchors), governance/HITL, and end-to-end audit. Reference storage: Neo4j (KG), Qdrant (embeddings/chunks), MinIO/S3 (artifacts/originals), SQL (audit).


---

## Supporters


* [Ruslan Magana Vsevolodovna](https://github.com/ruslanmv/)
* [Marco Monti](https://github.com/MarcoMontiPhD/)



