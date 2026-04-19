# Amazon MQ (amazon-mq)
Amazon MQ is a managed message broker service for Apache ActiveMQ and RabbitMQ that makes it easy to set up and operate message brokers in the cloud, enabling you to migrate to a message broker without writing the code that typically enables interoperability with existing applications.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-mq/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Broadcasting, Media Processing, Media

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon MQ API
Amazon MQ is a managed message broker service for Apache ActiveMQ and RabbitMQ that makes it easy to set up and operate message brokers in the cloud, enabling you to migrate to a message broker without writing the code that typically enables interoperability with existing applications.

**Human URL:** [https://aws.amazon.com/mq/](https://aws.amazon.com/mq/)

#### Tags:

 - Broadcasting, Media Processing, Media

#### Properties

- [Documentation](https://docs.aws.amazon.com/mq/)
- [OpenAPI](openapi/amazon-mq-openapi-original.yml)
- [GettingStarted](https://aws.amazon.com/mq/getting-started/)
- [Pricing](https://aws.amazon.com/mq/pricing/)
- [FAQ](https://aws.amazon.com/mq/faqs/)

## Common Properties

- [Portal](https://aws.amazon.com/mq/)
- [Documentation](https://docs.aws.amazon.com/mq/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/media/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/mq/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)

## Features

| Name | Description |
|------|-------------|
| Managed Message Brokers | Fully managed Apache ActiveMQ and RabbitMQ brokers with automated provisioning and maintenance. |
| Protocol Support | Supports AMQP, MQTT, OpenWire, STOMP, and WebSocket protocols for broad compatibility. |
| High Availability | Active/standby configurations with automatic failover for high availability. |
| Network of Brokers | Create networks of brokers for distributed messaging across regions and availability zones. |
| Broker Management API | Programmatically create, configure, and manage brokers and configurations. |
| Security | Encryption at rest and in transit, VPC isolation, and IAM integration. |

## Use Cases

| Name | Description |
|------|-------------|
| Application Migration | Migrate on-premises ActiveMQ or RabbitMQ workloads to AWS without code changes. |
| Microservices Decoupling | Use message queues to decouple microservices for improved reliability and scalability. |
| Enterprise Integration | Connect enterprise applications using standard messaging protocols. |
| Event-Driven Architecture | Build event-driven applications with reliable message delivery. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon VPC | Deploy brokers within a VPC for network isolation and security. |
| Amazon CloudWatch | Monitor broker metrics, queue depths, and consumer lag. |
| AWS KMS | Encrypt broker data at rest using AWS KMS keys. |
| AWS IAM | Control access to Amazon MQ resources with IAM policies. |
| Amazon CloudFormation | Provision and manage brokers using CloudFormation templates. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon MQ OpenAPI](openapi/amazon-mq-openapi-original.yml)

### JSON Schema

- 74 schema files in [json-schema/](json-schema/)

### JSON Structure

- 74 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Amazon MQ API Context](json-ld/amazon-mq-mq-api-context.jsonld)

### Examples

- 74 example files in [examples/](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon MQ](capabilities/shared/mq.yaml) — 22 operations for media processing

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Amazon MQ Workflow](capabilities/amazon-mq-media-workflow.yaml) | Amazon MQ | 8 | Broadcast Engineer |

## Vocabulary

- [Amazon MQ Vocabulary](vocabulary/amazon-mq-vocabulary.yaml) — Unified taxonomy mapping resources, actions, workflows, and personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon MQ Spectral Rules](rules/amazon-mq-spectral-rules.yml) — 20 rules across 8 categories enforcing Amazon MQ API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
