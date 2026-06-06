# Safety & Compliance – Open Pleasure Labs

**Disclaimer:** This is an open-source project for educational and experimental use. The contributors assume no liability for injury, misuse, or legal consequences. Users must be 18+ and comply with local laws.

## Safety Guidelines for Builders

If you're building this device:

### Electrical Safety
- Never use while charging (liability risk)
- Use only certified USB-C chargers (5V/2A max)
- Inspect for damaged wires or connectors before each use
- Do not modify the battery or charging circuit
- The device is not waterproof – IP67 *only when assembled and sealed*

### Material Safety
- Use only medical-grade silicone (Dow QP1-250 or equivalent)
- Do not use 3D-printed filaments for body contact (porous, cannot be sterilized)
- Avoid nickel-plated contacts (nickel allergy common) – use gold or titanium

### Usage Safety
- Stop immediately if you feel pain, numbness, or burning
- Do not use for more than 30 minutes continuously (overheating risk)
- Clean before and after each use with soap and water or toy cleaner
- Do not share without sterilizing (see cleaning protocol below)

### Medical Precautions
- Do not use if you have a pacemaker, implant, or electrical medical device
- Consult a doctor if you have a heart condition, neuropathy, or bleeding disorders
- If pregnant, consult doctor before use

## Cleaning Protocol

| Material | Method | Frequency |
|----------|--------|-----------|
| Silicone overmold | Soap + warm water, then 70% isopropyl alcohol | Before + after each use |
| Sensor modules (A, C) | Soap + water only (no alcohol – damages optical window) | Before + after each use |
| Module B (pressure) | Soap + water + soft brush | Before + after each use |
| Module D (EMG, electrodes) | Replace electrodes (disposable) | Every use |

**Sterilization (for sharing between partners):**
- Boil silicone parts for 5 minutes (remove electronics first – impossible on this device)
- Alternative: Soak in 70% isopropyl alcohol for 10 minutes (avoid optical sensors)
- Better: Use a condom over the device

## Regulatory Status

| Region | Classification | Path |
|--------|----------------|------|
| USA | Not a medical device (general wellness product) | No FDA registration required |
| EU | General product safety directive (GPSD) | CE marking (self-declared) |
| UK | General product safety regulations 2005 | UKCA marking |
| Canada | Consumer product | No medical device license needed |

**This device does NOT claim to diagnose, treat, cure, or prevent any medical condition.**

## Emissions Compliance

We will test for:

- **FCC Part 15 Subpart B** (unintentional radiator) – Class B (residential)
- **FCC Part 15 Subpart C** (intentional radiator, BLE) – Section 15.247
- **EN 55032** (Europe, emissions)
- **EN 61000-4-2** (ESD immunity)

**Pre-compliance steps for builders:**
- Keep digital traces short (under 50mm where possible)
- Use ground planes on PCB layers 2 and 5
- Add ferrite beads on power lines to USB-C
- Shield the NPU with a grounded copper can

## Certification Timeline (for production)

| Test | Lab | Duration | Cost |
|------|-----|----------|------|
| FCC unintentional radiator | Any certified lab | 2 weeks | $1,500 |
| FCC BLE intentional radiator | Any certified lab | 3 weeks | $2,000 |
| CE (Europe) | NB or self-declaration | 4 weeks | $1,500 |
| RoHS compliance | Material declaration | 1 week | $500 |
| Battery safety (UN38.3) | Battery test lab | 2 weeks | $800 |
| **Total** | | **~12 weeks** | **~$6,300** |

## Recall & Incident Reporting

If you experience:
- Battery swelling or fire
- Skin reaction (rash, burn, blister)
- Electrical shock

**Please report immediately to:** `safety@openpleasure.org` (set this up)

We will:
1. Investigate within 48 hours
2. Issue safety bulletin if needed
3. Work with community to fix design

---

**You are responsible for your own safety. Build and use at your own risk.**
