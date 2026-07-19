# Service Contexts

[한국어](./services.md)

This document summarizes the services I operate or research in my personal
server workspace at a public-safe level. It focuses on product direction,
engineering problems, and operational learning rather than private
configuration.

## Current Research Direction

The active work converges around three themes.

- AI-assisted operations and development workflows
- Personal knowledge and career-context management
- Operating a small production environment: routing, health, persistence, and recovery

## Services In Operation And Research

| Service | Public-safe context | Current direction |
| --- | --- | --- |
| `vodex` | A private AI workspace built around LibreChat and a Codex-compatible adapter. | Exploring practical AI support for server operations, documentation, code review, and workflow automation while controlling local context access. |
| `vodex-console` | An operator console experiment for working with Codex sessions more directly on a personal server. | Session persistence, streaming state, process control, and an interface shaped around server work. |
| `career-ai` | A private career workflow for organizing role context, positioning, and application materials. | Improving structured, evidence-based career decisions without exposing resumes or application data. |
| `obsidian-vault` | A private knowledge base for leadership notes, technical decisions, and project history. | Turning scattered notes into reusable operational context for reviews, decision-making, and AI-assisted work. |
| `daily-writing` | A local writing assistant for generating, saving, editing, and improving short-form draft ideas. | Human-reviewed AI writing workflows rather than automatic publishing. |
| `local-dns` | A small DNS support service for stabilizing personal domain access inside the LAN. | Keeping local service access predictable without publishing internal routing details. |
| [`index-page`](https://vumy.kr/) | A public profile and service index. | Presenting operated services and engineering ownership rather than raw server topology. |
| `quartz-obsidian` | A Quartz-based layer for publishing selected knowledge-base content. | Maintaining a repeatable path from private notes to public-safe pages. |
| `vumy_kr` | A small PHP-based site/service kept in the personal web workspace. | Managing legacy or lightweight web experiments separately from the main profile. |
| `sudoku-solver` | A small static utility served through nginx. | Keeping a simple algorithm utility as a lightweight web service. |
| `obsidian-sync` | A WebDAV layer for syncing a private knowledge store. | Supporting controlled note synchronization and automation access without exposing accounts, paths, or access details. |
| `career-vault` | A compatibility entry point for a private career workspace. | Covered under the broader `career-ai` context in public documentation. |

## Portfolio Signal

These services are not a list meant to show that many containers are running.
The core signal is the process of turning repeated work into maintainable
systems.

- Personal AI operations are treated as controlled workflows, not one-off prompts.
- Knowledge and career materials are managed as structured context to improve the reliability and auditability of AI-assisted work.
- Even small utilities are operated with service boundaries, persistence, and documentation in mind.

## Public Scope

This document does not publish private configuration, internal URLs, secrets,
server paths, database credentials, media locations, user data, or company-specific
details.
