# Home Assistant + ESPHome config (public copy)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)
[![Home Assistant](https://img.shields.io/badge/Home%20Assistant-Reference-2EA8E5?logo=home-assistant&logoColor=white)](https://www.home-assistant.io/)
[![ESPHome](https://img.shields.io/badge/ESPHome-Device%20Configs-F47C21?logo=esphome&logoColor=white)](https://esphome.io/)

This repository is a public copy of my personal [Home Assistant](https://home-assistant.io) and [ESPHome](https://esphome.io/) configuration, though mostly focused on the latter. It's intended as an example/inspiration — feel free to explore, fork, and adapt device configs or automation blueprints, but note this is not a collab project.

What you'll find here is a living config. Hope one day you'll find something of a worth for You in:
- [esphome/](./esphome/) — ESPHome device YAMLs and related files (search here for device-specific configs).
- [blueprints/](./blueprints/) — Home Assistant automation blueprints I use.

Some cloud-cutted, reflashed Tuya devices will hopefully appear here and I hope they will google well 🙃

This will be obviously growing over time, but as of a late 2025, don't expect a lot of fanciness 🤣

### Security & privacy
- I have intentionally omitted secrets (secrets.yaml, API keys, passwords) — do not expect them to be present 😜
- Friendly reminder: do not commit secrets if you fork, adapt and republish these configs for your needs. Use Home Assistant's [secrets.yaml](https://www.home-assistant.io/docs/configuration/secrets/)!

### Usage notes
- Browse the files under the links above and copy device or blueprint files into your own Home Assistant / ESPHome setup. 
- Update GPIO pins and entity names to match your likings and hardware before deploying.
- It's a living personal config and may change over time.

### Support & contributions
- This repo is maintained by a single person. If you want help adapting a config for a specific device, open an issue or create a discussion in your fork - or contact me directly.
- If you found some issue and are willing to fix them at source, please fork and submit PRs from your fork - or just message me.
