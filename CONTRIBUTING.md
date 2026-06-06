# Contributing to Open Pleasure Labs

First off, thank you for considering contributing. This is how we break the internet together.

## Quick Start

1. **Join Discord** – `https://discord.gg/openpleasure` (create this)
2. **Read the Code of Conduct** – No exceptions
3. **Find an issue** tagged `good-first-issue`
4. **Comment** "I'm working on this"
5. **Submit a PR** within 14 days

## What We Need

| Skill Area | Specific Tasks |
|------------|----------------|
| **Hardware** | PCB routing, component selection, flex PCB design |
| **Firmware** | Zephyr drivers, I2C/SPI, bootloader, BLE |
| **ML** | TinyTransformer training, NPU quantization, on-device inference |
| **App** | Flutter UI, BLE integration, preset sharing |
| **Mechanical** | Fusion 360 CAD, injection molding design, silicone overmold |
| **Documentation** | Tutorials, API docs, expansion module guide |
| **Testing** | Beta testing, bug reports, usability feedback |

## How to Contribute (by type)

### 🛠 Code (Firmware / ML / App)

1. Fork the repo
2. Create a branch: `git checkout -b feature/your-feature-name`
3. Write code with comments
4. Add tests if applicable
5. Run `make format` (we use clang-format for firmware, black for Python)
6. Push and open a Pull Request to `main`
7. Wait for review (48h typical)

**PR Requirements:**
- One logical change per PR (no kitchen sinks)
- Update `README.md` if API changes
- Pass CI (we'll set up GitHub Actions soon)

### 🔧 Hardware (PCB / CAD)

1. Export files in open formats (KiCad `.kicad_pcb`, STEP `.step`)
2. Include BOM in CSV format
3. Add renders or screenshots to PR
4. Note any critical dimensions or tolerances

### 📖 Documentation

- Fix typos directly via PR
- For new guides, create a `.md` file in `/docs`
- Use clear, simple English (we have non-native speakers)
- Add diagrams (ASCII or uploaded images)

### 🐛 Bug Reports

Use the issue template:

```markdown
**Describe the bug**
[clear description]

**To Reproduce**
1. Go to...
2. Click on...

**Expected behavior**
[what should happen]

**Screenshots/Logs**
[if applicable]

**Device info**
[hardware version, firmware version, app version]
