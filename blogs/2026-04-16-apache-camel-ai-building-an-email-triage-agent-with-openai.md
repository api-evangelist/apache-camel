---
title: "Apache Camel AI: Building an Email Triage Agent with OpenAI, Gmail Transformers, and Camel JBang"
url: "https://camel.apache.org/blog/2026/04/email-triage-agent/"
date: "2026-04-16"
feed_url: "https://camel.apache.org/blog/index.xml"
---
Recent Camel releases introduced several features that work well together for AI-powered integrations: the camel-openai component (4.17), the SimpleFunction interface, chain operator, and structured output with JSON Schema (4.18), and Gmail DataType Transformers (4.19). To show how these pieces fit, I built an email triage agent that classifies Gmail messages using an LLM, moves them to labels, and drafts smart replies. The whole thing runs with Camel JBang.
