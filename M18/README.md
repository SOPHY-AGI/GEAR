# M18 — 18 V field battery system

[← GEAR](../README.md) · [Field gear template](../_templates/FIELD_GEAR_README.md)

## Scope

Working technical reference for Milwaukee M18 battery packs and their relationships to chargers, power adapters, tools, and field power systems. Focus: identification, inspection, triage, service disposition, and evidence. This is not a manufacturer's repair manual.

## Pack catalog

| Variant | Milwaukee catalog no. | Nominal capacity | Nominal energy (calculated) | Field sheet |
| --- | --- | ---: | ---: | --- |
| REDLITHIUM HIGH OUTPUT XC6.0 | `48-11-1865` | 6.0 Ah | 108 Wh | [XC6.0](XC6.0/README.md) |
| REDLITHIUM HIGH OUTPUT HD12.0 | `48-11-1812` | 12.0 Ah | 216 Wh | [HD12.0](HD12.0/README.md) |

**Variant control:** HIGH OUTPUT XC6.0 (`48-11-1865`) is distinct from older XC6.0 (`48-11-1860`) and FORGE XC6.0 (`48-11-1861`). HIGH OUTPUT HD12.0 (`48-11-1812`) is distinct from FORGE HD12.0 (`48-11-1813`). Do not transplant assumptions between revisions.

## Field-use principles

- Identify physical pack model and charger model **before** applying any wiring diagram or troubleshooting procedure.
- Record both pack voltage and the exact condition under which it was measured; unloaded terminal voltage alone does not prove pack health or safe current delivery.
- Record indicator behavior (charger, pack fuel gauge, inverter/adapter) independently; different devices can report the same failure differently.
- Keep electrical measurements, hypotheses, and verified pin assignments separate.
- Do not bridge batteries, bypass charge protection, or apply power to unidentified contacts. Failed lithium packs should be isolated and assessed for authorized service.
- Distinguish M12 and M18 packs: they have different interfaces even where a charger supports both systems.

## Shared documentation standard

All equipment sheets follow the same sequence: **Identification → Service baseline → Field status → Non-invasive checks → Fault evidence → Service route → References → Follow-up**. Copy [the field gear template](../_templates/FIELD_GEAR_README.md) for later hardware families.

**Evidence labels:** `VERIFIED` = primary source or directly reproduced measurement; `OBSERVED` = operator-reported measurement/event; `INFERRED` = engineering interpretation; `PENDING` = not yet established. A source's existence does not verify that its board revision matches our equipment.

## Reference links

- [Milwaukee battery warranty and model table](https://www.milwaukeetool.com/support/registration-and-warranty)
- [Milwaukee eService](https://service.milwaukeetool.com/)

> This section is a documentation scaffold; individual pack serials, PCB revisions, internal wiring and charger specifics are not yet verified.
