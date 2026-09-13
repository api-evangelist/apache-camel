---
title: "Workload identity in Apache Camel with SPIFFE and SPIRE"
url: "https://camel.apache.org/blog/2026/09/camel-spiffe-workload-identity/"
date: "2026-09-07"
feed_url: "https://camel.apache.org/blog/index.xml"
---
Camel 4.23 is planned for October and it adds a new component, camel-spiffe. The problem it solves is not obvious if you have never looked at SPIFFE, so I want to explain what it is for, what it does, and point at the example I wrote for it. The problem Two services that talk to each other need to know who is on the other side.
