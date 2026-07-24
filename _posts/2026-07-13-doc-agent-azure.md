---
layout: post
header:
  teaser: /assets/images/medium.svg
  icon: fas fa-robot
title: "A RAG-based Document Q&A Agent on Azure"
date: 2026-07-13
tags: ["Retrieval Augmented Gen",
"Azure",
"AI Foundry",
]
description: "I built a system for a customer that needed to work with large volumes of invoices and contracts. The idea was: upload documents; extract, index and save information from documents; ask a question in plain language; prepare the context; get a direct answer with the source cited. The system was deployed on Azure."
draft: false
---

I built a system for a customer that needed to work with large volumes of invoices and contracts. The idea was: upload documents; extract, index and save information from documents; ask a question in plain language; prepare the context; get a direct answer with the source cited. The system was deployed on Azure. Two things shaped the design from the start. First, no API keys anywhere. Every service call uses Managed Identity and RBAC. This is not just a security preference. It removes a whole class of problems: no key rotation, no secrets in CI/CD, no risk of keys leaking in logs. Second, the infrastructure is fully described in Bicep, so the entire system can be provisioned with one command and torn down just as easily. Any changes reflected in the repo, will be projected in the infrastructure and app automatically.

As this core structure of the project is similar to other RAG-baed agentic system, I stripped the customer-specific parts and turned it into a reusable template.

This post walks through the architecture, the agent, and how to deploy it.

![Architecture](https://miro.medium.com/v2/resize:fit:720/format:webp/1*CJqZGpcyjgFwm565tm-5Uw.png)

[Read more ...](https://medium.com/@mohsenim/a-rag-based-document-q-a-agent-on-azure-8f69239e795f)