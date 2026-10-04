<p align="center">
  <a href="https://docs.rinda.dev">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset=".github/rinda-logo-dark.svg">
      <img src=".github/rinda-logo-light.svg" alt="Rinda" height="56">
    </picture>
  </a>
</p>

<p align="center">
  <strong>Managed message queues with object storage, for your code and your agents.</strong>
</p>

<p align="center">
  <a href="https://docs.rinda.dev"><strong>Documentation</strong></a>
  &nbsp;·&nbsp;
  <a href="https://docs.rinda.dev/docs/getting-started/quickstart">Quickstart</a>
  &nbsp;·&nbsp;
  <a href="https://docs.rinda.dev/docs/api-reference/rinda-api">API Reference</a>
  &nbsp;·&nbsp;
  <a href="https://docs.rinda.dev/docs/sdk-reference">SDK Reference</a>
</p>

---

This repository hosts the published documentation for Rinda, served at
**[docs.rinda.dev](https://docs.rinda.dev)**.

## Getting started

| Page | Description |
|:---|:---|
| [Quickstart](https://docs.rinda.dev/docs/getting-started/quickstart) | Create a queue and send your first message in under five minutes. |
| [Core Concepts](https://docs.rinda.dev/docs/getting-started/concepts) | Projects, environments, queues, messages and storage, and how they relate. |
| [Authentication](https://docs.rinda.dev/docs/getting-started/authentication) | Authenticate with the Rinda API using API keys. |

## Guides

| Guide | Description |
|:---|:---|
| [Queues](https://docs.rinda.dev/docs/guides/queues) | Create, configure and manage message queues. |
| [Messages](https://docs.rinda.dev/docs/guides/messages) | Send, receive and manage messages. |
| [Message Storage](https://docs.rinda.dev/docs/guides/storage) | How message bodies too large for the queue are stored, and for how long. |
| [Workers](https://docs.rinda.dev/docs/guides/workers) | Build reliable message consumers with `QueueWorker`. |
| [FIFO Queues](https://docs.rinda.dev/docs/guides/fifo-queues) | Strict ordering and exactly-once delivery. |
| [Dead-Letter Queues](https://docs.rinda.dev/docs/guides/dead-letter-queues) | Isolate and recover messages that fail processing. |
| [Environments](https://docs.rinda.dev/docs/guides/environments) | Separate development, staging and production. |
| [Message Introspection](https://docs.rinda.dev/docs/guides/message-introspection) | Trace, debug and monitor individual messages. |
| [Migrating from the AWS SDK](https://docs.rinda.dev/docs/guides/aws-sdk-migration) | Move an existing Amazon SQS integration to Rinda. |
| [Using Rinda from an AI Agent](https://docs.rinda.dev/docs/guides/mcp-server) | Give AI agents access to Rinda through the MCP server. |

## Reference

| Reference | Description |
|:---|:---|
| [API Reference](https://docs.rinda.dev/docs/api-reference/rinda-api) | Every REST endpoint, with request and response schemas. |
| [SDK Reference](https://docs.rinda.dev/docs/sdk-reference) | The TypeScript SDK, `@rindahq/sdk`. |

## Documentation for AI tools

The documentation is also published in plain text for language models and
coding agents, following the [`llms.txt`](https://llmstxt.org) standard.

| File | Contents |
|:---|:---|
| [`llms.txt`](https://docs.rinda.dev/llms.txt) | An index of every page, with a short summary of each. |
| [`llms-full.txt`](https://docs.rinda.dev/llms-full.txt) | The complete documentation in a single file. |

## About this repository

This repository contains the built documentation site, deployed with GitHub
Pages. The documentation is maintained alongside the Rinda platform and
published here automatically on every change. Each publish replaces the
repository's contents, so changes cannot be made here directly and pull
requests are not accepted.

## Support

To report an error in the documentation, or for help using Rinda, email
[support@rinda.dev](mailto:support@rinda.dev). When reporting a documentation
issue, please include a link to the page concerned.

## Security

If you believe you have found a security vulnerability in Rinda, please email
[security@rinda.dev](mailto:security@rinda.dev) rather than reporting it
publicly. We acknowledge every report within two business days.

---

<p align="center">
  <sub>© Rinda</sub>
</p>
