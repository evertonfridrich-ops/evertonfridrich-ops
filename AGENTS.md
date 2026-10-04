# AGENTS.md — Canonical Context for AI Coding Assistants

## 1. Project Purpose & Scope
This repository (`evertonfridrich-ops/evertonfridrich-ops`) serves as the official GitHub Profile Repository and engineering index for **Everton Fridrich** (`evertonfridrich-ops`).

Its role is to present a verified, institutional, high-signal overview of engineering competencies, active flagship systems, and technical architectures for human engineering leaders, recruiters, and autonomous agents alike.

## 2. Invariants & Guardrails
All agents modifying this repository MUST adhere to the following rules:

1. **Absolute Evidence Policy:** Never fabricate user counts, uptime percentages (e.g. "99.99%"), SLSA levels, SOC 2 compliance, or unverified job titles. All statements must match verifiable repository implementations.
2. **Semantic-First Content:** All critical technical information must be expressed directly in clean Markdown text. Do NOT rely exclusively on SVGs, badges, or dynamic external widgets to convey project facts.
3. **Restrained Visual Presentation:** Avoid badge walls, typing animations, visitor counters, and heavy decorative widgets. Keep visual elements clean, accessible, and dark/light mode compatible.
4. **Least-Privilege Automation:** Workflow files must explicitly declare permissions (`permissions: contents: read` by default) and only elevate where artifact commits or branch updates are required.
5. **No Secret Exposure:** Never commit `.env` files, API keys, personal phone numbers, or private addresses.

## 3. Repository Map
* `README.md` — Canonical profile portfolio and engineering matrix.
* `SECURITY.md` — Coordinated vulnerability disclosure policy.
* `AGENTS.md` — Canonical agent rules and architectural context.
* `docs/repository-map.md` — Structural catalog of repository files and roles.
* `.github/copilot-instructions.md` — GitHub Copilot instruction adapter.
* `.github/workflows/` — Automation workflows for periodic profile telemetry.
* `assets/` — Repository-owned static graphic assets and charts.

## 4. Definition of Done
A modification to this repository is considered complete only when:
- Markdown renders cleanly with valid syntax and unbroken links.
- Mermaid diagrams parse without syntax errors.
- Workflows are valid YAML and follow least-privilege permissions.
- No unverified claims or false compliance assertions are introduced.
