# GEAR

**RTFM.** Field equipment technical reference and service records.

An indexed repository for power systems, tools, adapters, sensors and other deployed hardware. Content favors **field diagnostics, safe service disposition and repeatable evidence** over product advertising.

## Equipment directory

| Family | Coverage | Entry point |
| --- | --- | --- |
| M18 — Milwaukee 18 V batteries | HIGH OUTPUT XC6.0 and HIGH OUTPUT HD12.0 | [M18 index](M18/README.md) |
| Future field equipment | Add one family directory per platform, and one model directory per exact variant | [Reusable gear README template](_templates/FIELD_GEAR_README.md) |

### First model sheets

- [M18 / XC6.0 — field service sheet](M18/XC6.0/README.md) — `48-11-1865`, includes a dated unresolved charger-fault case.
- [M18 / HD12.0 — field service sheet](M18/HD12.0/README.md) — `48-11-1812`, baseline reference, no documented unit fault.

## Repository conventions

```text
GEAR/
├── README.md
├── _templates/
│   └── FIELD_GEAR_README.md
└── M18/
    ├── README.md
    ├── XC6.0/
    │   └── README.md
    └── HD12.0/
        └── README.md
```

Each model's README keeps the same numbered structure:

1. Identification
2. Service-relevant baseline
3. Current field status
4. Non-invasive field checks
5. Fault evidence and working hypotheses
6. Service route
7. Manuals and technical references
8. Open questions / next review

**Evidence tags:** `VERIFIED` / `OBSERVED` / `INFERRED` / `PENDING`. Preserve manufacturer catalog numbers and revision applicability. Record dated measurements and instrument setup; never promote an unverified hypothesis or third-party diagram to canonical wiring.

**Public-repository hygiene:** Do not commit full serial numbers, receipts containing personal information, precise equipment locations, API keys, sensitive photos or credentials.

## Expansion pattern

Add `<family>/README.md` as an index and `<family>/<model>/README.md` from the shared template. Later, store revision-specific documents in `manuals/`, `diagrams/`, `photos/`, and `logs/` within a model folder **only when there is an actual document to add**. Cross-link assets from the relevant README and cite their source/revision.

> This is a field-reference project, not a substitute for official service instructions or a declaration that internal battery repairs have been validated.
