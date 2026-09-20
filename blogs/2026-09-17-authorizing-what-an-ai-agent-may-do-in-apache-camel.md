---
title: "Authorizing what an AI agent may do in Apache Camel"
url: "https://camel.apache.org/blog/2026/09/securing-ai-agent-tools/"
date: "2026-09-17"
feed_url: "https://camel.apache.org/blog/index.xml"
---
Camel can expose a route as a tool an AI agent can call, and it can run the agent that calls it. Camel 4.22 added camel-ai-tool, a way to register a route as a tool once and use it from LangChain4j, Spring AI or OpenAI, and over MCP (see Camel Routes as AI Tools). The agent reads a request, picks the tools it needs and calls them.
