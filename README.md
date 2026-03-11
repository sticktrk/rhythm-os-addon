# Rhythm Lighting Add-on for Home Assistant

[![HA Add-on](https://img.shields.io/badge/HA-Add--on-41BDF5.svg)](https://www.home-assistant.io/addons/)

Adaptive lighting that follows the sun. Automatically adjusts brightness and color temperature throughout the day.

## Installation

1. Open Home Assistant
2. Go to **Settings** → **Add-ons** → **Add-on Store**
3. Click the three dots menu → **Repositories**
4. Add: `https://github.com/sticktrk/rhythm-lighting-addon`
5. Find **Rhythm Lighting** and click **Install**
6. Start the add-on and check **Show in sidebar**

## Features

- Adaptive lighting curves driven by solar position
- Built-in Light Designer UI (accessible via sidebar)
- Room-based control with per-room settings
- Switch integration via ZHA events and Rhythm Lighting services
- Works with ZigBee, Z-Wave, WiFi, and Matter lights

## Configuration

The add-on auto-configures from Home Assistant (location, timezone, API token). Use the Light Designer UI for curve and room settings.

## Custom Integration

For service-based control in automations, also install the [Rhythm Lighting Integration](https://github.com/sticktrk/rhythm-lighting-integration) via HACS.

## More Info

- [Main repository](https://github.com/sticktrk/rhythm-lighting)
- [Integration repository](https://github.com/sticktrk/rhythm-lighting-integration)
