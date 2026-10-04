# Repository Intelligence Map

```text
evertonfridrich-ops/
├── README.md                          # Canonical profile README and flagship engineering showcase
├── SECURITY.md                        # Vulnerability disclosure and security contacts
├── AGENTS.md                          # Canonical AI agent instructions and repository boundaries
├── docs/
│   └── repository-map.md              # Machine-readable directory catalog (this document)
├── .github/
│   ├── copilot-instructions.md        # Copilot adapter pointing to AGENTS.md
│   └── workflows/
│       ├── profile-3d.yml             # Generates 3D commit visualization (daily cron)
│       └── snake.yml                  # Generates contribution grid snake animation
└── assets/
    ├── header.svg                     # Optional visual banner
    ├── telemetry.svg                  # Operational telemetry diagram
    └── snake/                         # Output target for snake animation assets
```

## Directory Responsibilities

* **Root (`/`)**: Core identity and governance files. Changes should only reflect real, evidenced architectural milestones.
* **`.github/workflows/`**: Scheduled automation. Maintained with least privilege (`permissions: contents: read` baseline, `contents: write` scoped specifically to commit jobs).
* **`assets/`**: Static repository-owned visual assets. Avoid third-party unauthenticated external tracking pixels or dynamic badge APIs.
