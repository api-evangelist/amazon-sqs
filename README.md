# Amazon SQS

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.

**Areas:** AWS · Cloud · Distributed Systems · Messaging · Microservices · Queues

## Amazon SQS on APIs.io

Everything profiled for Amazon SQS is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/amazon-sqs/](https://apis.io/providers/amazon-sqs/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [Amazon SQS Messages API](https://apis.io/apis/amazon-sqs/amazon-sqs-messages-api/) — Operations for sending, receiving, and deleting messages in SQS queues
- [Amazon SQS Permissions API](https://apis.io/apis/amazon-sqs/amazon-sqs-permissions-api/) — Operations for managing queue access permissions
- [Amazon SQS Queues API](https://apis.io/apis/amazon-sqs/amazon-sqs-queues-api/) — Operations for creating, managing, and deleting SQS queues
- [Amazon SQS Tags API](https://apis.io/apis/amazon-sqs/amazon-sqs-tags-api/) — The Tags API from Amazon SQS — 1 operation(s) for tags.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Amazon Simple Queue Service (SQS) Event Source Mapping](https://apis.io/asyncapis/amazon-sqs/amazon-sqs-asyncapi/)

#### Event channels (4)

Individual events and webhooks the provider emits.

- [arn:aws:sqs:{region}:{accountId}:{queueName}](https://apis.io/channels/amazon-sqs/arn-aws-sqs-region-accountid-queuename/)
- [https://sqs.{region}.amazonaws.com/{accountId}/{dlqName}](https://apis.io/channels/amazon-sqs/https-sqs-region-amazonaws-com-accountid-dlqname/)
- [https://sqs.{region}.amazonaws.com/{accountId}/{queueName}](https://apis.io/channels/amazon-sqs/https-sqs-region-amazonaws-com-accountid-queuename/)
- [https://sqs.{region}.amazonaws.com/{accountId}/{queueName}.fifo](https://apis.io/channels/amazon-sqs/https-sqs-region-amazonaws-com-accountid-queuename-fifo/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Amazon Sqs Agentic Access](https://apis.io/agentic-access/amazon-sqs/amazon-sqs-agentic-access/)

#### JSON Schema (19)

The data models the API reads and writes.

- [BatchResultErrorEntry](https://apis.io/schemas/amazon-sqs/amazon-sqs-batch-result-error-entry/)
- [CancelMessageMoveTaskResponse](https://apis.io/schemas/amazon-sqs/amazon-sqs-cancel-message-move-task-response/)
- [ChangeMessageVisibilityBatchResponse](https://apis.io/schemas/amazon-sqs/amazon-sqs-change-message-visibility-batch-response/)
- [CreateQueueResponse](https://apis.io/schemas/amazon-sqs/amazon-sqs-create-queue-response/)
- [DeleteMessageBatchResponse](https://apis.io/schemas/amazon-sqs/amazon-sqs-delete-message-batch-response/)
- [ErrorResponse](https://apis.io/schemas/amazon-sqs/amazon-sqs-error-response/)
- [GenericResponse](https://apis.io/schemas/amazon-sqs/amazon-sqs-generic-response/)
- [GetQueueAttributesResponse](https://apis.io/schemas/amazon-sqs/amazon-sqs-get-queue-attributes-response/)
- [GetQueueUrlResponse](https://apis.io/schemas/amazon-sqs/amazon-sqs-get-queue-url-response/)
- [ListDeadLetterSourceQueuesResponse](https://apis.io/schemas/amazon-sqs/amazon-sqs-list-dead-letter-source-queues-response/)
- [ListMessageMoveTasksResponse](https://apis.io/schemas/amazon-sqs/amazon-sqs-list-message-move-tasks-response/)
- [ListQueueTagsResponse](https://apis.io/schemas/amazon-sqs/amazon-sqs-list-queue-tags-response/)
- [ListQueuesResponse](https://apis.io/schemas/amazon-sqs/amazon-sqs-list-queues-response/)
- [Message](https://apis.io/schemas/amazon-sqs/amazon-sqs-message/)
- [ReceiveMessageResponse](https://apis.io/schemas/amazon-sqs/amazon-sqs-receive-message-response/)
- [ResponseMetadata](https://apis.io/schemas/amazon-sqs/amazon-sqs-response-metadata/)
- [SendMessageBatchResponse](https://apis.io/schemas/amazon-sqs/amazon-sqs-send-message-batch-response/)
- [SendMessageResponse](https://apis.io/schemas/amazon-sqs/amazon-sqs-send-message-response/)
- [StartMessageMoveTaskResponse](https://apis.io/schemas/amazon-sqs/amazon-sqs-start-message-move-task-response/)

#### JSON Structure (19)

Data models expressed in JSON Structure.

- [Amazon Sqs Batch Result Error Entry Structure](https://apis.io/json-structure/amazon-sqs/amazon-sqs-batch-result-error-entry-structure/)
- [Amazon Sqs Cancel Message Move Task Response Structure](https://apis.io/json-structure/amazon-sqs/amazon-sqs-cancel-message-move-task-response-structure/)
- [Amazon Sqs Change Message Visibility Batch Response Structure](https://apis.io/json-structure/amazon-sqs/amazon-sqs-change-message-visibility-batch-response-structure/)
- [Amazon Sqs Create Queue Response Structure](https://apis.io/json-structure/amazon-sqs/amazon-sqs-create-queue-response-structure/)
- [Amazon Sqs Delete Message Batch Response Structure](https://apis.io/json-structure/amazon-sqs/amazon-sqs-delete-message-batch-response-structure/)
- [Amazon Sqs Error Response Structure](https://apis.io/json-structure/amazon-sqs/amazon-sqs-error-response-structure/)
- [Amazon Sqs Generic Response Structure](https://apis.io/json-structure/amazon-sqs/amazon-sqs-generic-response-structure/)
- [Amazon Sqs Get Queue Attributes Response Structure](https://apis.io/json-structure/amazon-sqs/amazon-sqs-get-queue-attributes-response-structure/)
- [Amazon Sqs Get Queue Url Response Structure](https://apis.io/json-structure/amazon-sqs/amazon-sqs-get-queue-url-response-structure/)
- [Amazon Sqs List Dead Letter Source Queues Response Structure](https://apis.io/json-structure/amazon-sqs/amazon-sqs-list-dead-letter-source-queues-response-structure/)
- [Amazon Sqs List Message Move Tasks Response Structure](https://apis.io/json-structure/amazon-sqs/amazon-sqs-list-message-move-tasks-response-structure/)
- [Amazon Sqs List Queue Tags Response Structure](https://apis.io/json-structure/amazon-sqs/amazon-sqs-list-queue-tags-response-structure/)
- [Amazon Sqs List Queues Response Structure](https://apis.io/json-structure/amazon-sqs/amazon-sqs-list-queues-response-structure/)
- [Amazon Sqs Message Structure](https://apis.io/json-structure/amazon-sqs/amazon-sqs-message-structure/)
- [Amazon Sqs Receive Message Response Structure](https://apis.io/json-structure/amazon-sqs/amazon-sqs-receive-message-response-structure/)
- [Amazon Sqs Response Metadata Structure](https://apis.io/json-structure/amazon-sqs/amazon-sqs-response-metadata-structure/)
- [Amazon Sqs Send Message Batch Response Structure](https://apis.io/json-structure/amazon-sqs/amazon-sqs-send-message-batch-response-structure/)
- [Amazon Sqs Send Message Response Structure](https://apis.io/json-structure/amazon-sqs/amazon-sqs-send-message-response-structure/)
- [Amazon Sqs Start Message Move Task Response Structure](https://apis.io/json-structure/amazon-sqs/amazon-sqs-start-message-move-task-response-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Amazon Sqs Context](https://apis.io/jsonld/amazon-sqs/amazon-sqs-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [amazon-sqs API Vocabulary](https://apis.io/vocabularies/amazon-sqs/amazon-sqs-vocabulary/)

#### Examples (19)

Example requests and responses.

- [Amazon Sqs Batch Result Error Entry Example](https://apis.io/examples/amazon-sqs/amazon-sqs-batch-result-error-entry-example/)
- [Amazon Sqs Cancel Message Move Task Response Example](https://apis.io/examples/amazon-sqs/amazon-sqs-cancel-message-move-task-response-example/)
- [Amazon Sqs Change Message Visibility Batch Response Example](https://apis.io/examples/amazon-sqs/amazon-sqs-change-message-visibility-batch-response-example/)
- [Amazon Sqs Create Queue Response Example](https://apis.io/examples/amazon-sqs/amazon-sqs-create-queue-response-example/)
- [Amazon Sqs Delete Message Batch Response Example](https://apis.io/examples/amazon-sqs/amazon-sqs-delete-message-batch-response-example/)
- [Amazon Sqs Error Response Example](https://apis.io/examples/amazon-sqs/amazon-sqs-error-response-example/)
- [Amazon Sqs Generic Response Example](https://apis.io/examples/amazon-sqs/amazon-sqs-generic-response-example/)
- [Amazon Sqs Get Queue Attributes Response Example](https://apis.io/examples/amazon-sqs/amazon-sqs-get-queue-attributes-response-example/)
- [Amazon Sqs Get Queue Url Response Example](https://apis.io/examples/amazon-sqs/amazon-sqs-get-queue-url-response-example/)
- [Amazon Sqs List Dead Letter Source Queues Response Example](https://apis.io/examples/amazon-sqs/amazon-sqs-list-dead-letter-source-queues-response-example/)
- [Amazon Sqs List Message Move Tasks Response Example](https://apis.io/examples/amazon-sqs/amazon-sqs-list-message-move-tasks-response-example/)
- [Amazon Sqs List Queue Tags Response Example](https://apis.io/examples/amazon-sqs/amazon-sqs-list-queue-tags-response-example/)
- [Amazon Sqs List Queues Response Example](https://apis.io/examples/amazon-sqs/amazon-sqs-list-queues-response-example/)
- [Amazon Sqs Message Example](https://apis.io/examples/amazon-sqs/amazon-sqs-message-example/)
- [Amazon Sqs Receive Message Response Example](https://apis.io/examples/amazon-sqs/amazon-sqs-receive-message-response-example/)
- [Amazon Sqs Response Metadata Example](https://apis.io/examples/amazon-sqs/amazon-sqs-response-metadata-example/)
- [Amazon Sqs Send Message Batch Response Example](https://apis.io/examples/amazon-sqs/amazon-sqs-send-message-batch-response-example/)
- [Amazon Sqs Send Message Response Example](https://apis.io/examples/amazon-sqs/amazon-sqs-send-message-response-example/)
- [Amazon Sqs Start Message Move Task Response Example](https://apis.io/examples/amazon-sqs/amazon-sqs-start-message-move-task-response-example/)

#### Collections (9)

Postman and Open Collection request collections.

- [Amazon SQS Amazon Simple Queue Service (SQS) API](https://apis.io/collections/amazon-sqs/open-amazon-sqs/)
- [Amazon SQS Amazon Simple Queue Service (SQS) Messages API](https://apis.io/collections/amazon-sqs/open-amazon-sqs-messages-api/)
- [Amazon SQS Amazon Simple Queue Service (SQS) Messages Permissions API](https://apis.io/collections/amazon-sqs/open-amazon-sqs-permissions-api/)
- [Amazon SQS Amazon Simple Queue Service (SQS) Messages Queues API](https://apis.io/collections/amazon-sqs/open-amazon-sqs-queues-api/)
- [Amazon SQS Amazon Simple Queue Service (SQS) Messages Tags API](https://apis.io/collections/amazon-sqs/open-amazon-sqs-tags-api/)
- [Amazon SQS Amazon Simple Queue Service (SQS) Messages API](https://apis.io/collections/amazon-sqs/postman-amazon-sqs-messages-api/)
- [Amazon SQS Amazon Simple Queue Service (SQS) Messages Permissions API](https://apis.io/collections/amazon-sqs/postman-amazon-sqs-permissions-api/)
- [Amazon SQS Amazon Simple Queue Service (SQS) Messages Queues API](https://apis.io/collections/amazon-sqs/postman-amazon-sqs-queues-api/)
- [Amazon SQS Amazon Simple Queue Service (SQS) Messages Tags API](https://apis.io/collections/amazon-sqs/postman-amazon-sqs-tags-api/)

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [Amazon SQS — asyncapi rules](https://apis.io/rules/amazon-sqs/amazon-sqs-asyncapi-spectral-rules/)
- [Amazon SQS — jsonschema rules](https://apis.io/rules/amazon-sqs/amazon-sqs-jsonschema-spectral-rules/)
- [Amazon SQS API Rules](https://apis.io/rules/amazon-sqs/amazon-sqs-spectral-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Amazon Sqs Authentication](https://apis.io/security/amazon-sqs/amazon-sqs-authentication/)
- [Amazon Sqs Domain Security](https://apis.io/security/amazon-sqs/amazon-sqs-domain-security/)
- [Amazon Sqs Trust Center](https://apis.io/security/amazon-sqs/amazon-sqs-trust-center/)
- [Amazon Sqs Vulnerability Disclosure](https://apis.io/security/amazon-sqs/amazon-sqs-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Amazon Sqs Plans Pricing](https://apis.io/plans/amazon-sqs/amazon-sqs-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Amazon Sqs Rate Limits](https://apis.io/rate-limits/amazon-sqs/amazon-sqs-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Amazon Sqs Finops](https://apis.io/finops/amazon-sqs/amazon-sqs-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://aws.amazon.com/sqs/)
- [Support](https://console.aws.amazon.com/support/home)
- [Blog](https://aws.amazon.com/blogs/compute/)
- [Terms of service](https://aws.amazon.com/service-terms/)
- [Privacy policy](https://aws.amazon.com/privacy/)
- [Status](https://status.aws.amazon.com/)

## API Evangelist rating

**Kin Score 57.2** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 66.3 |
| Contract governance | 13.6 |
| Operational transparency | 44.7 |
| Developer ergonomics | 70.2 |
| Access clarity | 55.3 |

**Agent readiness 31.1** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 35.3** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/amazon-sqs/](https://apis.io/providers/amazon-sqs/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Amazon SQS: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/amazon-sqs/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
