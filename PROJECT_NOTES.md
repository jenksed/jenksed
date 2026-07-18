# Project notes

This page gives more context for the projects featured in the profile README. The descriptions are intentionally specific about what the repositories contain and what they do not prove.

## [Clusterwise](https://github.com/jenksed/clusterwise)

**Status:** Active learning project

Clusterwise is an open-source, lab-driven Kubernetes apprenticeship and static learning system. It contains fifteen canonical capability sequences, original curriculum structure, diagrams, labs, validation tooling, and documentation published through a dependency-free static approach.

### Evidence in the repository

- A committed static site and curriculum structure
- Capability sequences organized around observation, investigation, operational reasoning, troubleshooting, and evidence of learning
- Original diagrams, lab material, and validation tooling
- Lifecycle distinctions between published content, technical review, executed labs, learner testing, and stability

### What it demonstrates

Kubernetes learning and operational thinking, systems decomposition, information architecture, technical writing, static-site engineering, and safety-conscious documentation quality controls.

### What it does not claim

It is not a hosted lab platform, LMS, automated grader, certification program, or Kubernetes distribution. Published content should not be treated as proof that every lab has been executed or learner-tested.

## [RoleForge](https://github.com/jenksed/roleforge)

**Status:** In progress

RoleForge is a local-first native macOS application for organizing career personas, applications, evidence, and grounded job-search workflows. It is implemented in Swift and SwiftUI.

### Evidence in the repository

- A Swift Package and SwiftUI/AppKit application foundation
- Local persistence and recovery-oriented application structure
- Persona and application tracking
- Résumé ingestion and drafting workflows
- Templates, attachments, and job-import parsing work
- QA matrices, smoke tests, and documented release gates

### What it demonstrates

Native application development, Swift and SwiftUI project work, local-first product design, persistence thinking, requirement-driven planning, grounded workflow design, and QA-oriented delivery.

### What it does not claim

RoleForge is still under active development. Workflow completeness, provider hardening, manual QA, and release validation remain unfinished. It is not described as launched, commercially available, complete, or production-ready.

## [oc-elixir-scout](https://github.com/jenksed/oc-elixir-scout)

**Status:** Early developer-tooling project

oc-elixir-scout is a lightweight, read-only impact scout for AI coding agents working in Elixir repositories. The primary implementation is Bash. It gathers pre-edit context such as likely callers, related tests, nearby references, risk hints, and suggested validation commands.

### Evidence in the repository

- Bash command-line implementation
- Optional use of `mix`, `git`, and `rg`
- Operation without an installed Elixir runtime when possible
- Read-only reconnaissance before an edit
- Smoke coverage and documented limitations
- A release and changelog history for the tool

### What it demonstrates

Developer tooling, shell scripting, Elixir and OTP learning, AI-agent workflow design, safe-change thinking, graceful degradation, and clear documentation of limitations.

### What it does not claim

The analysis is heuristic and substring-based rather than full AST analysis. It is not a complete dependency analyzer, formal static-analysis system, CI-integrated safety guarantee, or tool that can guarantee a safe code modification.

## [supportlab-relay](https://github.com/jenksed/supportlab-relay)

**Status:** Prototype

supportlab-relay is an early Go prototype for connecting learner-local terminal sessions to browser-based SupportLab experiences.

### Evidence in the repository

- A Go module and command-line entrypoints
- A local WebSocket server
- Pairing-message groundwork
- PTY input and output streaming
- Terminal resizing and signal handling
- A validation command
- Localhost as the default bind address with guarded routable binding
- Tests around relay behavior and protocol concerns

### What it demonstrates

Early Go development, WebSocket and PTY experimentation, local-first system boundaries, protocol design, educational-tool integration, and security-default thinking.

### What it does not claim

The repository explicitly describes itself as a prototype skeleton. Parts of the pairing lifecycle and rate limiting remain unfinished. It is not described as secure for untrusted networks, production-ready, or a completed remote-terminal platform.

## [macadmin](https://github.com/jenksed/macadmin)

**Status:** Public utility collection

macadmin is a collection of Zsh-based utilities for inspecting and managing macOS systems through a shared command dispatcher. Its commands cover system information, updates, cleanup, settings, networking, backups, and basic hardening.

### Evidence in the repository

- A shared command dispatcher and shell helpers
- Read-only system probes
- Dry-run behavior and confirmation gates
- Protected operations for higher-risk commands
- Structured logging, including JSON-oriented output
- Lightweight tests and mocks

### What it demonstrates

Practical support automation, shell scripting, command-line interface design, structured logging, operational safety, and testing of system utilities.

### What it does not claim

macadmin is not enterprise device management, an MDM replacement, or a fully audited security tool. The repository is presented as a practical utility collection rather than a complete operations platform.
