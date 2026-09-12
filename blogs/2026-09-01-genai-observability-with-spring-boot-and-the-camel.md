---
title: "GenAI Observability with Spring Boot and the Camel Observability Stack"
url: "https://camel.apache.org/blog/2026/09/camel-genai-observability-spring-boot/"
date: "2026-09-01"
feed_url: "https://camel.apache.org/blog/index.xml"
---
In Part 1 we prototyped GenAI observability with the Camel CLI and TUI. This follow-up — Phase 3 (Operate) — shows the same gen_ai.* telemetry in a Spring Boot application wired to the observability stack Camel ships for local development: Prometheus, VictoriaTraces, and Perses. The runnable sample lives in the camel-spring-boot-examples repository at genai-observability (reworked in PR #192).
