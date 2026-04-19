# Amazon SQS (amazon-sqs)
Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-sqs/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Cloud, Distributed Systems, Messaging, Microservices, Queue

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-18

## APIs

### Amazon SQS API
RESTful API for Amazon Simple Queue Service operations including queue management, message sending and receiving, batch operations, dead-letter queues, and access control.

**Human URL:** [https://aws.amazon.com/sqs/](https://aws.amazon.com/sqs/)

#### Tags:

 - AWS, Messaging, Queue

#### Properties

- [Documentation](https://docs.aws.amazon.com/sqs/)
- [OpenAPI](openapi/amazon-sqs-openapi.yml)
- [APIReference](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/APIReference/)
- [GettingStarted](https://aws.amazon.com/sqs/getting-started/)
- [Pricing](https://aws.amazon.com/sqs/pricing/)
- [FAQ](https://aws.amazon.com/sqs/faqs/)
- [BestPractices](https://docs.aws.amazon.com/sqs/latest/dg/best-practices.html)
- [SDK](https://aws.amazon.com/tools/)
- [Tutorials](https://docs.aws.amazon.com/sqs/latest/dg/sqs-tutorials.html)
- [Features](https://aws.amazon.com/sqs/features/)
- [Security](https://docs.aws.amazon.com/sqs/latest/dg/sqs-security.html)
- [Compliance](https://aws.amazon.com/compliance/services-in-scope/)
- [CLI](https://docs.aws.amazon.com/cli/latest/reference/sqs/)
- [CodeExamples](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/service_code_examples.html)
- [RateLimits](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-quotas.html)
- [Regions](https://docs.aws.amazon.com/general/latest/gr/sqs-service.html)
- [ReleaseNotes](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-release-notes.html)

## Common Properties

- [Blog](https://aws.amazon.com/blogs/compute/)
- [Console](https://console.aws.amazon.com/sqs/)
- [StatusPage](https://status.aws.amazon.com/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://console.aws.amazon.com/support/home)
- [KnowledgeCenter](https://repost.aws/knowledge-center)
- [CodeExamples](https://docs.aws.amazon.com/code-library/latest/ug/sqs_code_examples.html)
- [GitHubRepository](https://github.com/awsdocs/aws-doc-sdk-examples)

## Features

| Name | Description |
|------|-------------|
| Standard Queues | Maximum throughput, best-effort ordering, and at-least-once delivery for high-volume messaging workloads. |
| FIFO Queues | Exactly-once processing and strict ordering guarantees for applications requiring message sequence preservation. |
| Dead-Letter Queues | Automatic routing of failed messages to dead-letter queues for debugging and reprocessing. |
| Message Move Tasks | Bulk movement of messages between queues for reprocessing dead-letter queue contents. |
| Server-Side Encryption | Automatic encryption of messages at rest using AWS KMS keys for data protection. |
| Long Polling | Reduced API costs and latency by allowing consumers to wait for messages to arrive before responding. |

## Use Cases

| Name | Description |
|------|-------------|
| Microservices Decoupling | Decouple microservices by using SQS queues as asynchronous communication buffers between services. |
| Serverless Event Processing | Trigger AWS Lambda functions from SQS messages for event-driven serverless architectures. |
| Order Processing Pipelines | Use FIFO queues to ensure ordered processing of e-commerce orders and financial transactions. |
| Work Queue Distribution | Distribute compute-intensive tasks across multiple workers using standard queues for parallel processing. |
| Batch Job Orchestration | Queue batch processing jobs and manage their execution across distributed compute resources. |

## Integrations

| Name | Description |
|------|-------------|
| AWS Lambda | Automatically invoke Lambda functions when messages arrive in SQS queues for serverless processing. |
| Amazon SNS | Fan out SNS notifications to multiple SQS queues for parallel processing of published messages. |
| Amazon EventBridge | Route events from EventBridge to SQS queues for reliable event-driven architectures. |
| AWS CloudFormation | Provision and manage SQS queues as infrastructure-as-code using CloudFormation templates. |
| Terraform | Create and manage SQS resources using HashiCorp Terraform infrastructure-as-code provider. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon SQS API](openapi/amazon-sqs-openapi.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon SQS](capabilities/shared/sqs.yaml) -- 23 operations for message queuing

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Message Queuing](capabilities/message-queuing.yaml) | SQS | 18 | Developer / DevOps Engineer |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
