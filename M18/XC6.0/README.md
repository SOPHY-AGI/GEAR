# M18 HIGH OUTPUT XC6.0 — Field service sheet

[← M18 index](../README.md) · [Common template](../../_templates/FIELD_GEAR_README.md)

## 1. Identification

| Field | Record |
| --- | --- |
| Manufacturer | Milwaukee Tool |
| Family | M18 REDLITHIUM HIGH OUTPUT |
| Variant | XC6.0 (not standard XC6.0 or FORGE XC6.0) |
| Manufacturer catalog no. | **48-11-1865** |
| Battery chemistry | Lithium-ion |
| Nominal pack voltage | 18 V |
| Rated capacity | 6.0 Ah |
| Nominal stored energy | **108 Wh**, calculated as 18 V × 6.0 Ah |
| Individual pack identifier / serial | PENDING — do not post serial publicly |
| PCB / cell revision | PENDING — physical verification required |

## 2. Service-relevant baseline

- Tool, charger and adapter compatibility must be checked at the device level; a mechanically fitting pack does not alone prove a given adapter is appropriate.
- An M18 pack's open-circuit voltage is **not** a measure of its available current, remaining capacity, or individual cell-group balance.
- The on-pack fuel gauge, charger indicator, and external inverter/adapter indicators are separate observations.
- The five external contacts include power and signal connections; **the factory pin assignment and internal wiring for our exact pack revision remain UNVERIFIED**. Do not assume readings on smaller terminals are exposed cell taps.
- A persistent charger fault should be resolved through approved service, not by bypassing the pack's protection system.
- Milwaukee lists a **three-year limited battery warranty** for catalog no. 48-11-1865, subject to coverage terms and examination.

## 3. Current field status

**OBSERVED, 2026-11-08 — one suspect XC6.0 pack; serial not recorded.** Reported stored disconnected, nearly exhausted, for roughly one month; ambient nights reached approximately the 40s °F. Fuel-gauge button completely dark. Two different Milwaukee chargers immediately reported an alternating red/green fault. The TOP-OFF did not activate or report a useful indication; a larger inverter also signaled fault.

### External terminal measurements (operator-reported, DC relative to a chosen ground contact)

**Contact order/orientation is NOT yet independently verified.** These are indexed probe positions, *not* a certified pinout.

| Measured position | Suspect pack | Comparison working pack |
| --- | ---: | ---: |
| 1 | 19.47 V | 20.40 V |
| 2 | 0.00 V | 0.00 V |
| 3 | 19.01 V | 19.96 V |
| 4 | **17.17 V** | **0.00 V** |
| 5 | Ground reference | Ground reference |

**INFERRED:** Position 4 differs substantially between measured packs. Its electrical function, meter-loading effects, and whether comparison pack has the same board revision are PENDING. The 19.47 V total does **not** substantiate a whole-pack deep-discharge diagnosis, nor rule out an isolated cell-group problem. Do not inject power based on this table.

**Current disposition:** Suspect pack; avoid use/charging attempts pending warranty/service evaluation. Comparison pack assumed operational based on operator report; exact model unconfirmed.

## 4. Non-invasive field checks

- [x] Measure suspect pack external voltage: 19.47 V (operator-reported)
- [x] Repeat charger test on second charger: immediate fault (operator-reported)
- [x] Compare five external contact readings to working pack (operator-reported)
- [ ] Confirm identical physical orientation and actual model of comparison pack
- [ ] Inspect contacts, housing, and label for moisture, dirt, cracks and damage without opening
- [ ] Record charger catalog numbers and exact indicator patterns
- [ ] Capture model label, purchase record, and service disposition in private inventory
- [ ] Request manufacturer warranty evaluation

**Meter caution:** Voltage mode only across positively identified terminals; never put a meter in current mode directly across a battery. Do not short adjacent contacts.

## 5. Fault evidence and working hypotheses

| Possibility | Status | Evidence needed |
| --- | --- | --- |
| Whole-pack deeply discharged | Not supported by 19.47 V terminal measurement alone | Internal cell-group data and authorized diagnostics |
| Internal protection, sensing, communication, or interconnect fault | INFERRED / unconfirmed | Exact-board service information |
| Failed individual cell group / imbalance | PENDING | Authorized internal diagnostics |
| Charger-only defect | Less likely | Two chargers reported same immediate fault |

No exact fault code, internal schematic, or repair procedure verified for this pack revision.

## 6. Service route

- First path: Milwaukee warranty/eService evaluation. Manufacturer lists 3 years limited coverage for this catalog number; eligibility depends on findings.
- Source purchase channel: Home Depot (operator-reported); purchase less than one year before incident (operator-reported); receipt retrieval PENDING.
- Follow manufacturer instructions before shipping a lithium-ion pack.

## 7. Manuals and technical references

- [Milwaukee product page — 48-11-1865](https://www.milwaukeetool.com/products/details/m18-redlithium-high-output-xc6-0-battery-pack/48-11-1865)
- [Milwaukee warranty and exclusions](https://www.milwaukeetool.com/support/registration-and-warranty)
- [Milwaukee eService](https://service.milwaukeetool.com/)
- [Third-party M18 pinout overview (revision compatibility UNVERIFIED)](https://toolcroze.com/milwaukee-m18-battery-pinout-wiring-diagram/)

## 8. Open questions / next review

- Exact manufacturing date and PCB revision.
- Correct terminal identification and numbering from physical photographs.
- Charger models, troubleshooting codes, and manufacturer service conclusion.
- Whether the comparison pack is the same catalog number and board revision.
- Add dated photos, approved manuals and test logs as separate linked artifacts once verified.
