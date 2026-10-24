# METAR LightWorks Map Gen 2 — development distribution

Private development scaffold. **No active OTA release. Hardware acceptance pending.**

Private source: `metarlightworks/metarlightworks-engineering`, branch `codex/map-gen2`.

Intended generic assets after approval:
- `METARLightworks_Map_Gen2_SafeMode_ESP32C3.bin`
- `METARLightworks_Map_Gen2_ESP32C3.bin`
- `SHA256SUMS.txt`
- `BUILD_MANIFEST.json`

This repository must never contain factory credentials or internal source/configuration. Factory firmware is built locally in Arduino IDE and is not distributed here. Lamp Gen 2 and legacy Map releases are separate and unchanged.

Drafts/prereleases are not selected by the firmware's `/releases/latest` endpoint. The private repository cannot be read anonymously by generic devices. Public availability and a release usable for the first authorized hardware test require explicit approval; do not promote this repository or its drafts automatically.
