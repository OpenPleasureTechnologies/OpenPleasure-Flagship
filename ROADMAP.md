# Roadmap – Open Pleasure Labs Flagship

## Current Status: 🔴 Phase 0 – Team Formation

*Last updated: 2026-06-06*

---

## Phase 0: Team Formation (Month 0-1) – YOU ARE HERE

| Task | Owner | Status |
|------|-------|--------|
| Recruit hardware engineer | Community | 🔴 Not started |
| Recruit embedded engineer | Community | 🔴 Not started |
| Recruit ML engineer | Community | 🔴 Not started |
| Create Discord server | Maintainer | 🔴 Not started |
| Legal review (licenses) | Volunteer | 🔴 Not started |
| Set up GitHub Actions CI | Volunteer | 🔴 Not started |

**Goal:** 5 core engineers committed by end of Month 1

---

## Phase 1: Prototype PCB v1 (Month 1-3)

- Desktop-sized board (100x150mm)
- Wired sensors (no flex)
- USB-powered
- Sensor data streaming to PC

**Milestones:**
- [ ] Schematic complete
- [ ] PCB layout complete
- [ ] First fabrication order placed
- [ ] Assembly (hand-solder) complete
- [ ] I2C/SPI drivers reading all sensors

**Budget needed:** $2,000 (crowdfunding or self-funded)

---

## Phase 2: Compact PCB v2 (Month 3-5)

- 6-layer rigid, 50x30mm
- Battery integration
- BLE working
- Simple 3D-printed enclosure

**Milestones:**
- [ ] Power management circuit working
- [ ] Battery life >2 hours
- [ ] BLE pairing + data streaming to app
- [ ] First silicone prototype (simple cylinder)

**Budget needed:** $3,000

---

## Phase 3: Modular Connector (Month 5-7)

- 12-pin magnetic pogo working
- Module A (GSR/HR) functional
- Module C (IMU) functional
- Hot-swap detection firmware

**Milestones:**
- [ ] Connector supplier locked
- [ ] Flex PCB for modules designed
- [ ] Module detection <100ms
- [ ] Both modules streaming to main processor

**Budget needed:** $4,000

---

## Phase 4: ML Pipeline + App (Month 7-9)

- On-device inference (50ms target)
- Flutter app with pattern recording
- Preset sharing (anonymized)

**Milestones:**
- [ ] TinyTransformer running on NPU
- [ ] 50ms latency achieved
- [ ] App connects to device via BLE
- [ ] Preset export/import working

**Budget needed:** $3,000

---

## Phase 5: Beta + Certification (Month 9-12)

- 10 beta units to community
- FCC/CE testing passed
- Design finalized

**Milestones:**
- [ ] Beta units shipped
- [ ] Feedback collected from 10 users
- [ ] FCC test report received
- [ ] Final BOM under $150/unit

**Budget needed:** $3,000

---

## Phase 6: Crowdsupply Launch (Month 12+)

- Pre-order campaign
- 100-unit production run
- Public launch

**Goal:** $30,000 raised

---

## How to Help Right Now

| Need | Urgency |
|------|---------|
| Hardware engineer (KiCad expert) | 🔴 HIGH |
| Discord server setup | 🔴 HIGH |
| Legal (open source licensing) | 🟡 MEDIUM |
| Grant writer (NLNet, NGI, Mozilla) | 🟡 MEDIUM |
| Anyone to share this repo | 🔴 HIGH |

**Comment on this roadmap** to claim a task.
