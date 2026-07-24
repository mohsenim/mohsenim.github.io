---
layout: single
title: "Projects"
permalink: /projects/
author_profile: false
header:
  overlay_color: "#0f1f2e"
  overlay_image: # /assets/images/mm-home-page-feature.jpg
  overlay_filter: "rgba(15, 31, 46, 0.75)"
---


## Enterprise Engineering Projects

### Real-Time Time-Series Analytics & Data Pipeline Framework

Designed and engineered the core backend microservice infrastructure to support real-time time-series anomaly detection and clustering across 5 major German utility and environmental organizations:

* Stadtentwässerungsbetriebe Köln (**StEB Köln**)
* Rheinisch-Westfälische Wasserwerksgesellschaft (**RWW**)
* Landesamt für Natur, Umwelt und Verbraucherschutz NRW (**LANUV**)
* Emschergenossenschaft und Lippeverband (**EGLV**)
* Bitcontrol GmbH (**Bitcontrol**)

**Key Engineering Contributions:**

* **Scalable Microservices:** Developed a decoupled, event-driven microservice architecture containerized with **Docker** to process high-density data streams.
* **Data Streaming & Processing:** Implemented **Kafka** and **Kafka Streams** to build reliable, real-time data ingestion pipelines and dedicated project-specific import adapters.
* **Stream Variations:** Configured pipelines to adaptively handle varying data granularities (1-minute to 15-minute frequencies) and system latencies across up to 1,100 concurrent time series.
* **Data Lifecycle Management:** Built robust scheduling mechanisms executing distinct execution workflows based on client readiness, supporting **real-time streaming**, **scheduled batch processing**, and historical **backfilling/reprocessing** for up to 15 years of archive data.


### Intelligent Conversational LLM Pipeline & Intent Routing Engine

#### Conversational Commerce & Customer Support Automation

Designed and developed an early-stage conversational AI pipeline for a leading food and beverage delivery platform, enabling automated customer ordering, intelligent semantic search, and automated support routing.

* **Client / Platform:** Snappfood (Food & Beverage Delivery Marketplace)

**Key Engineering Contributions:**

* **Intent Classification & Parameter Extraction:** Built NLP pipelines to process raw customer chat text, classifying requests into operational intents (e.g., "food search") while dynamically extracting search parameters and filtering criteria.
* **Context-Aware Recommendations:** Integrated user profile data with intent parameters to query the product database, dynamically serving personalized restaurant and food recommendations directly within the chat interface.
* **Intelligent Support Routing:** Developed an automated detection mechanism to identify customer complaints and seamlessly hand off complex order issues to live support team members.
* **Domain Fine-Tuning:** Fine-tuned open-source transformer models using tailored, domain-specific instruction datasets to maximize classification and parameter-extraction accuracy under production constraints.


## Solo Projects & Open-Source Contributions
* **[A RAG-based Document Q&A Agent on Azure](https://github.com/mohsenim/DocAgentAzure)**
Developed an AI agent for document question answering, enabling users to interact with documents through natural language queries and retrieve relevant information using Azure AI Foundry and Document Intelligence.
* **Intelligent Receipt & Invoice Processing Android App on Azure**
Developed an Android app with a Microsoft Azure backend for automated receipt and invoice processing, extracting, categorizing, and structuring financial data from images and PDFs for reporting and expense management.
* **[GitLab Management MCP Agent](https://github.com/mohsenim/gitlab-management-agent)**
Built an MCP (Model Context Protocol) server that lets AI assistants like Cursor to create, update, label, and assign GitLab issues.
* **Digital Onboarding & Presence Mobile App for Small and Medium Businesses**
Built a mobile application designed to simplify and automate the digital footprint, online presence, and local marketing workflows for freelancers and SMEs.
* **[Local-RAG: Retrieval-Augmented Document System](https://github.com/mohsenim/Local-RAG-with-LangChain-and-Chroma)**
Built a Retrieval-Augmented Generation (RAG) application for querying local documents using LangChain, a Chroma vector database, and ChatGPT.
* **[FastAPI Azure Full-Stack Template](https://github.com/mohsenim/FastAPI-Backend-Frontend-Azure)**
Engineered a production-ready FastAPI backend and frontend boilerplate template optimized for containerized cloud environments (Azure/Docker).
* **[BentoML: Serve & Deploy Machine Learning Models](https://github.com/mohsenim/BentoMl-Deploy-Docker)**
Streamlined deployment pipelines by packaging machine learning weights into containerized REST APIs and reproducible Docker images using BentoML.
* **[Text2Image-NN Classifier: Fractal Analysis of Long Texts](https://github.com/mohsenim/Text-Image-NN-Classifier)**
Developed a cross-domain NLP framework mapping long texts into visual structures to leverage pre-trained computer vision neural networks for classification.
* **[Sequence Labeling System (fastai)](https://github.com/mohsenim/Sequence-Labeling-fastai)**
Implemented an optimized sequence labeling pipeline over language models to process entire, long-context documents without token-length limits or memory constraints.
* **MorphoBERT: State-of-the-Art Named Entity Recognition (NER) System**
Awarded 1st place in the NLP Solutions for Under-Resourced Languages shared-task competition for designing a custom BERT and morphological pipeline.
* **[Persianp: High-Performance Text Processing Toolbox](https://github.com/mohsenim/persianp)**
Authored an enterprise-grade Java text processing library implementing optimized pipelines for core tokenization, lemmatization, and POS tagging.