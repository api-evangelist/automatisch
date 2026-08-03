# Automatisch (automatisch)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Automatisch is an open source business automation tool and self-hosted alternative to Zapier that connects different services to automate workflows without programming knowledge. Built with JavaScript/Node.js, it supports 100+ integrations including Slack, GitHub, Gmail, PostgreSQL, and AI services. Licensed under AGPL-3.0 for the community edition, with an enterprise edition for commercial deployments.

**URL:** [https://automatisch.io](https://automatisch.io)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Workflow Automation, Self-Hosted, Open Source, Zapier Alternative, No-Code, JavaScript, Node.js, AGPL

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-04-19

## APIs

### Automatisch REST API

Automatisch exposes a REST API used by its web application for managing flows (automated workflows), connections (service credentials), users, and integrations. The API supports webhook trigger endpoints for receiving events from external services.

**Human URL:** [https://github.com/automatisch/automatisch](https://github.com/automatisch/automatisch)

#### Tags

 - Workflow Automation, Flows, Connections, Webhooks, REST

#### Properties

- [Documentation](https://automatisch.io/docs)
- [Getting Started](https://automatisch.io/docs/installation/docker)
- [GitHub Repository](https://github.com/automatisch/automatisch)

## Common Properties

- [Website](https://automatisch.io)
- [Documentation](https://automatisch.io/docs)
- [GitHub Organization](https://github.com/automatisch)
- [GitHub Repository](https://github.com/automatisch/automatisch)
- [Getting Started](https://automatisch.io/docs/installation/docker)
- [Release Notes](https://github.com/automatisch/automatisch/releases)

## Features

| Name | Description |
|------|-------------|
| 100+ Built-In Integrations | Automatisch ships with over 100 pre-built connectors for popular services including Slack, Discord, GitHub, GitLab, Gmail, Google Sheets, Airtable, Notion, Trello, OpenAI, Anthropic, PostgreSQL, and many more. |
| Self-Hosted Deployment | Deploy Automatisch on your own infrastructure using Docker Compose, keeping all workflow data and credentials under your control with no data sent to third-party cloud services. |
| Webhook Triggers | Built-in webhook trigger support allows external services to trigger Automatisch flows via HTTP POST, enabling event-driven automation from any service that supports outbound webhooks. |
| No-Code Workflow Builder | A visual drag-and-drop interface for building multi-step automation workflows connecting triggers from one service to actions in another without writing code. |
| AGPL-3.0 Open Source | The community edition is licensed under AGPL-3.0, allowing free use, modification, and distribution. An enterprise edition with additional features is available for commercial deployments. |
| Custom App Development | Extend Automatisch by developing custom app integrations using the JavaScript SDK. Custom apps follow the same trigger/action pattern as built-in integrations. |

## Use Cases

| Name | Description |
|------|-------------|
| Business Process Automation | Automate repetitive business processes such as lead routing, support ticket triage, and data synchronization between SaaS tools without relying on cloud automation vendors. |
| Data Privacy Compliance | Self-host workflow automation to keep sensitive business data on-premises or in private cloud infrastructure, meeting GDPR and data residency requirements. |
| Developer Workflow Automation | Automate developer workflows including GitHub issue-to-Slack notifications, CI/CD status updates, and pull request review reminders. |
| CRM and Marketing Automation | Connect CRM tools with marketing platforms to automate lead nurturing, email sequences, and customer data synchronization across tools. |

## Integrations

| Name | Description |
|------|-------------|
| Slack | Send messages, create channels, and respond to Slack events in automated flows. |
| GitHub | Trigger flows from GitHub events and create issues, PRs, and comments programmatically. |
| Gmail | Send emails and trigger flows from incoming Gmail messages. |
| Google Sheets | Read and write rows in Google Sheets as steps in automated workflows. |
| OpenAI | Call OpenAI APIs (GPT, DALL-E, Whisper) as steps within Automatisch automation flows. |
| PostgreSQL | Query and write to PostgreSQL databases as steps in automation flows. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
