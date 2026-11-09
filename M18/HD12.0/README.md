# M18 HIGH OUTPUT HD12.0 — Field service sheet

[← M18 index](../README.md) · [Common template](../../_templates/FIELD_GEAR_README.md)

## 1. Identification

| Field | Record |
| --- | --- |
| Manufacturer | Milwaukee Tool |
| Family | M18 REDLITHIUM HIGH OUTPUT |
| Variant | HD12.0 (not FORGE HD12.0) |
| Manufacturer catalog no. | **48-11-1812** |
| Battery chemistry | Lithium-ion |
| Nominal pack voltage | 18 V |
| Rated capacity | 12.0 Ah |
| Nominal stored energy | **216 Wh**, calculated as 18 V × 12.0 Ah |
| Individual pack identifier / serial | PENDING — do not post serial publicly |
| PCB / cell revision | PENDING — physical verification required |

## 2. Service-relevant baseline

- This pack provides **twice the nominal energy** of the HIGH OUTPUT XC6.0 at equal nominal pack voltage; that is not a promise of twice the runtime for every load.
- Larger housing may limit fit in some older M18 tools/accessories. Confirm device compatibility before field deployment.
- The rated voltage and capacity do not establish maximum safe output current, charger behavior or internal circuit topology.
- Compare external indicators and individual observations with known-good equipment; do not transfer pinouts or internal repair assumptions from XC6.0 without verifying board revisions.
- Milwaukee lists a **three-year limited battery warranty** for catalog no. 48-11-1812, subject to coverage terms and examination.
- The manufacturer's product page currently labels this particular HIGH OUTPUT HD12.0 listing as no longer available; do not confuse it with the distinct FORGE HD12.0 model 48-11-1813.

## 3. Current field status

**PENDING.** This page establishes the model reference only. No specific HD12.0 pack, state of charge, location, failure, or inventory quantity has been independently documented here.

## 4. Non-invasive field checks

- [ ] Confirm pack model and revision from label and housing
- [ ] Record housing/contacts condition and whether fuel gauge responds
- [ ] Record terminal DC voltage using identified power terminals
- [ ] Record charger model, indicator behavior, and charge-cycle outcome
- [ ] Confirm accessory physical fit and rated device compatibility
- [ ] Record date, ambient conditions and field use history
- [ ] Record service disposition and warranty status

**Meter caution:** Voltage mode only across positively identified terminals; do not short contacts or bridge batteries.

## 5. Fault evidence and working hypotheses

No field fault case logged yet. Record symptoms separately from hypotheses and repair conclusions. A nominal terminal voltage does not establish full pack health or cell-group balance.

## 6. Service route

Use Milwaukee warranty/eService for suspected internal pack faults. Record proof of purchase and serial only in private inventory, not this public repository. Do not ship lithium-ion packs without approved carrier/service instructions.

## 7. Manuals and technical references

- [Milwaukee product page — 48-11-1812](https://www.milwaukeetool.com/products/details/m18-redlithium-high-output-hd12-0-battery-pack/48-11-1812)
- [Milwaukee battery warranty and model table](https://www.milwaukeetool.com/support/registration-and-warranty)
- [Milwaukee eService](https://service.milwaukeetool.com/)
- [Milwaukee M18 HD12.0 + rapid charger kit (charger reference)](https://www.milwaukeetool.com/products/details/m18-redlithium-high-output-hd12-0-battery-pack-w-rapid-charger/48-59-1200)

## 8. Open questions / next review

- Identify exact field units, revisions and charger combinations.
- Obtain the correct manual/parts list and confirm its scope.
- Verify internal topology and any third-party pinout against the physical revision before documenting.
- Add field records, photographs, compatible accessories and diagnostics when available.
