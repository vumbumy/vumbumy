# Service Contexts

[한국어](./services.md)

This document summarizes the services I operate or research in my personal
server workspace at a public-safe level. It focuses on my personal AX work, or
AI transformation: turning systems I actually use into AI-centered, operable
workflows, rather than publishing private configuration.

## Current AX Direction

The active work converges around three themes.

- AI-assisted operations and development workflows
- Personal knowledge and career-context management
- Operating a small production environment: routing, health, persistence, and recovery

## Services In Operation And Research

| Service | Public-safe context | Current direction |
| --- | --- | --- |
| `vodex` | A private AI workspace built around LibreChat and a Codex-compatible adapter. | Exploring practical AI support for server operations, documentation, code review, and workflow automation while controlling local context access. |
| `vodex-console` | An operator console experiment for working with Codex sessions more directly on a personal server. | Session persistence, streaming state, process control, and an interface shaped around server work. |
| `ops-toolbox` | A maintenance container that collects Git, network, database, and Docker helper tools needed during server operations. | Reducing interruptions caused by missing tools and keeping inspection and recovery work in a reproducible shell environment. |
| `career-ai` | A private career workflow for organizing role context, positioning, and application materials. | Improving structured, evidence-based career decisions without exposing resumes or application data. |
| `obsidian-vault` | A private knowledge base for leadership notes, technical decisions, and project history. | Turning scattered notes into reusable operational context for reviews, decision-making, and AI-assisted work. |
| `daily-writing` | A local writing assistant for generating, saving, editing, and improving short-form draft ideas. | Human-reviewed AI writing workflows rather than automatic publishing. |
| `beszel` | A lightweight monitoring hub for personal-server state. | Focusing on quick operating signals such as disk usage, container health, and resource pressure rather than a large observability stack. |
| `security-report` | A small automated report for server security signals. | Surfacing only the items likely to need attention, such as login failures, important container health, disk pressure, and external exposure. |
| `local-dns` | A small DNS support service for stabilizing personal domain access inside the LAN. | Keeping local service access predictable without publishing internal routing details. |
| [`index-page`](https://vumy.kr/) | A public profile and service index. | Presenting operated services and engineering ownership rather than raw server topology. |
| `quartz-obsidian` | A Quartz-based layer for publishing selected knowledge-base content. | Maintaining a repeatable path from private notes to public-safe pages. |
| `vumy_kr` | A small PHP-based site/service kept in the personal web workspace. | Managing legacy or lightweight web experiments separately from the main profile. |
| `sudoku-solver` | A small static utility served through nginx. | Keeping a simple algorithm utility as a lightweight web service. |
| `obsidian-sync` | A WebDAV layer for syncing a private knowledge store. | Supporting controlled note synchronization and automation access without exposing accounts, paths, or access details. |
| `career-vault` | A compatibility entry point for a private career workspace. | Covered under the broader `career-ai` context in public documentation. |
| `immich-migration` | Operational work for moving the photo server toward a more durable primary-server structure. | Preserving existing media while organizing new storage, read-only legacy sources, and recovery procedures. |
| `immich-dedup` | Helper work for handling duplicate photos while balancing original preservation and upload stability. | Prioritizing trash, manifests, quality comparison, and mobile-backup stability over blind deletion. |

## Portfolio Signal

These services are not a list meant to show that many containers are running.
The core signal is my personal AX process: turning repeated personal needs into
maintainable systems with AI-assisted workflows.

- Personal AI operations are treated as controlled workflows, not one-off prompts.
- Knowledge and career materials are managed as structured context to improve the reliability and auditability of AI-assisted work.
- Even small utilities are operated with service boundaries, persistence, and documentation in mind.
- For personal-data services such as the photo server, restore confidence and preservation policy come before feature work.

## Public Scope

This document does not publish private configuration, internal URLs, secrets,
server paths, database credentials, media locations, user data, or company-specific
details.
