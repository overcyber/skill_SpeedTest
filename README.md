# Speedtest

[![Continous Integration](https://gitlab.com/project-alice-assistant/skills/skill_Speedtest/badges/master/pipeline.svg)](https://gitlab.com/project-alice-assistant/skills/skill_Speedtest/pipelines/latest)

run internet speed test

This skill uses the speedtest-cli (https://github.com/sivel/speedtest-cli) which runs an internet bandwidth test using speedtest.net.

Be aware that this speedtest relies on the capability of the network-adapter of your main device.

Examples for Raspberry Pi:
- Raspberry Pi 3 B  onboard WiFi: max. ~40 Mbit/s, onboard LAN: max. ~100 Mbit/s
- Raspberry Pi 3 B+ onboard WiFi: max. ~100 Mbit/s, onboard LAN: max. ~225 Mbit/s

If a Raspberry Pi 3 B - connected to WiFi - runs Alice you won't get more than 40 Mbit/s from the speedtest despite your internet connection may have more bandwith.

- Author: maxbachmann
- Maintainers: Psycho
- Alice minimum Version: 1.0.0-a5
- Languages:
  - en
  - de
  - fr
  - online
