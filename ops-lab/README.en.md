# Ops Lab

[한국어](./README.md)

I operate a small personal production environment that connects product
development, AI-assisted workflows, personal data management, and knowledge
publishing.

The goal is not to showcase a large infrastructure footprint. It is to build my
own version of AX, or AI transformation: redesigning the personal and work
systems I actually use around AI, automation, and operable feedback loops.

## Focus

- Personal AX
- AI-assisted Operations & Development
- Developer Experience & Workflow Automation
- Knowledge, Career Context & Publishing

## Running Services

### [Public Profile](https://vumy.kr/)

A public entry point for my engineering profile, operated services, and career
positioning.

### Immich

A private photo and video library used as a real personal media system, with
ongoing attention to storage, backups, service health, and data continuity.

Recently, the work has moved beyond simply running a photo server. I treat it
as a long-term operations problem that includes primary-server migration,
separating old and new storage roles, backup verification, and duplicate
cleanup policy.

### Vodex

A private AI work environment built around LibreChat and a Codex-compatible
adapter, used to support server operations, writing, code review, and workflow
automation.

Vodex Console extends that work into a more direct operator console. It focuses
on session persistence, cancellation, streaming state, and Telegram input
routing for real server-operation workflows.

### Career AI

A personal career workflow project for organizing application materials,
positioning, and job-search related context.

### Obsidian / Quartz

A personal knowledge-management and publishing pipeline, connecting private
notes with selectively published content.

### Operations Toolkit

I also maintain an operations toolbox, monitoring, and security-report
automation. The goal is not to build a large observability stack, but to turn
easy-to-miss personal-server signals such as disk pressure, service health,
external exposure, and backup freshness into small repeatable checks.

## Current Operating Questions

- Turning personal workflows such as photo archiving, knowledge management, career decisions, and writing into AI-assisted systems
- Permission boundaries, session persistence, and cancellable workflows when AI agents operate on real servers and data
- The boundary between public-safe AX experiments and private infrastructure details
- How to keep small services organized around health checks and recovery procedures instead of just increasing the service count

## More Context

- [Service Contexts](./services.en.md) / [한국어](./services.md)

## Operating Responsibilities

- Docker-based deployment and service maintenance
- Web entrypoint and WAF configuration
- Service health checks, log review, and incident follow-up
- Resource monitoring and capacity planning
- Configuration management for self-hosted services
- Backup planning for media, databases, and critical service configuration

## Public-Safe Notes

This document intentionally avoids publishing private configuration, secrets,
internal IP addresses, database credentials, media paths, backup paths, and
personal data.
