# Apache Camel (apache-camel)
Apache Camel is an open-source integration framework developed by the Apache Software Foundation that implements Enterprise Integration Patterns (EIPs) for connecting systems, services, and data. It provides a domain-specific language (DSL) in Java, XML, YAML, and Kotlin for defining routes between components. Camel ships with over 300 components for connecting to messaging systems, databases, cloud services, APIs, and file formats. Camel K extends this with a Kubernetes-native integration runtime and operator with a REST management API.

**URL:** [https://camel.apache.org/](https://camel.apache.org/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Apache, Enterprise Integration, Integration, Messaging, Open Source, Routing

## Timestamps

- **Created:** 2025-06-05
- **Modified:** 2026-04-19

## APIs

### Apache Camel Java DSL API
The Apache Camel Java DSL provides a fluent API for defining integration routes using Enterprise Integration Patterns. Developers define RouteBuilder subclasses to connect Camel components via endpoints, processors, and transformers.

**Human URL:** [https://camel.apache.org/manual/java-dsl.html](https://camel.apache.org/manual/java-dsl.html)

#### Tags

 - DSL, Integration, Java, Routing

#### Properties

- [Documentation](https://camel.apache.org/manual/java-dsl.html)
- [APIReference](https://camel.apache.org/manual/camelcontext.html)
- [GettingStarted](https://camel.apache.org/manual/getting-started.html)

### Apache Camel REST DSL API
The Apache Camel REST DSL provides a concise syntax for exposing and consuming RESTful services within Camel routes. It supports both REST service definition and REST proxy/consumer patterns.

**Human URL:** [https://camel.apache.org/manual/rest-dsl.html](https://camel.apache.org/manual/rest-dsl.html)

#### Tags

 - DSL, REST, Routing

#### Properties

- [Documentation](https://camel.apache.org/manual/rest-dsl.html)

### Apache Camel K Operator API
The Apache Camel K Operator exposes a Kubernetes Custom Resource API for deploying and managing Camel integrations as cloud-native serverless workloads on Kubernetes and OpenShift.

**Human URL:** [https://camel.apache.org/camel-k/next/apis/operator/](https://camel.apache.org/camel-k/next/apis/operator/)

#### Tags

 - Kubernetes, Operator, Serverless

#### Properties

- [Documentation](https://camel.apache.org/camel-k/next/apis/operator/)
- [GettingStarted](https://camel.apache.org/camel-k/next/installation/installation.html)

### Apache Camel Quarkus API
Apache Camel Quarkus provides native compilation and fast startup of Camel routes on Quarkus, enabling serverless and microservice deployments with Camel's integration components.

**Human URL:** [https://camel.apache.org/camel-quarkus/next/index.html](https://camel.apache.org/camel-quarkus/next/index.html)

#### Tags

 - Quarkus, Serverless

#### Properties

- [Documentation](https://camel.apache.org/camel-quarkus/next/index.html)

## Common Properties

- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/camel)
- [Documentation](https://camel.apache.org/docs/)
- [GettingStarted](https://camel.apache.org/manual/getting-started.html)
- [Support](https://camel.apache.org/community/support/)
- [TermsOfService](https://www.apache.org/licenses/)
- [ChangeLog](https://github.com/apache/camel/releases)
- [Java SDK (Maven)](https://search.maven.org/artifact/org.apache.camel/camel-core)

## Features

| Name | Description |
|------|-------------|
| Enterprise Integration Patterns | Implementation of 65+ EIPs including splitter, aggregator, content-based router, message translator, and dead letter channel. |
| 300+ Components | Pre-built connectors for messaging (Kafka, ActiveMQ, RabbitMQ), cloud (AWS, Azure, GCP), databases, REST, SOAP, and file formats. |
| Multi-DSL Support | Define routes in Java, XML, YAML, Kotlin, or Groovy DSL with full feature parity across languages. |
| REST DSL | Concise DSL for exposing and consuming RESTful services with OpenAPI/Swagger integration. |
| Camel K Kubernetes Operator | Deploy Camel integrations as cloud-native serverless workloads on Kubernetes and OpenShift. |
| Camel Quarkus | Native compilation of Camel routes with Quarkus for fast startup and low memory serverless deployments. |
| Data Formats | Built-in support for 50+ data format conversions including JSON, XML, CSV, Avro, Protobuf, and EDI. |
| Route Templates | Parameterized route templates for building reusable integration patterns. |
| Saga Pattern | Distributed transaction support using the saga pattern with compensating actions. |
| Observability | Built-in metrics, tracing (OpenTelemetry), and health check endpoints for Camel routes. |

## Use Cases

| Name | Description |
|------|-------------|
| System Integration | Connect disparate enterprise systems including ERP, CRM, databases, and cloud services using EIP patterns. |
| API Gateway | Build lightweight API gateways for routing, transformation, and protocol mediation using the REST DSL. |
| Event-Driven Architecture | Implement event-driven integrations with Kafka, ActiveMQ, and other messaging platforms. |
| Data Pipeline | Build ETL pipelines transforming and routing data between storage systems and data formats. |
| Microservice Integration | Wire microservices together using Camel K serverless integrations on Kubernetes. |
| Legacy Modernization | Bridge legacy SOAP, FTP, and EDI systems with modern REST and cloud-native services. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Kafka | Camel Kafka component for producing and consuming Kafka topic messages in integration routes. |
| Apache ActiveMQ | Camel ActiveMQ component for JMS messaging with Apache ActiveMQ Classic and Artemis. |
| AWS Services | Camel AWS components for S3, SQS, SNS, DynamoDB, Lambda, and other AWS services. |
| Kubernetes | Camel K Operator for deploying integrations as native Kubernetes Custom Resources. |
| OpenAPI | Camel REST DSL generates OpenAPI specifications and can create routes from OpenAPI contracts. |
| Spring Boot | Camel Spring Boot starter for integrating Camel into Spring Boot applications. |
| Quarkus | Camel Quarkus extensions for native compilation and serverless deployment of integration routes. |

## Vocabulary

- [Apache Camel Vocabulary](vocabulary/apache-camel-vocabulary.yaml) — Domain taxonomy mapping 8 resources, 7 actions, and 2 personas for integration route development

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
