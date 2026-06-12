# No Longer Evil

Control your No Longer Evil smart thermostat from Home Assistant.

This HACS package is maintained from the `jvannoyx4` fork and includes the
`1.1.2` thermostat display fix for cooling/heating modes where the Nest API
omits the active target temperature.

## Features

- Full climate control (temperature, mode, fan)
- Temperature sensors
- HVAC status binary sensors
- Away mode switch
- Support for heat-cool (auto) mode with temperature ranges
- Multiple thermostat support
- Fix for stale Nest mode data causing active cooling to display as heat

## Requirements

- A No Longer Evil account with at least one registered thermostat and an API
  key from your No Longer Evil account settings
- Or a self-hosted No Longer Evil Control API server reachable from Home
  Assistant

## Setup

1. Add the custom repository in HACS:
   `https://github.com/jvannoyx4/NoLongerEvil-HomeAssistant`
2. Install the integration and restart Home Assistant
3. Add the integration from **Settings** > **Devices & Services**
4. Choose **No Longer Evil Cloud** and enter your API key, or choose
   **Self-Hosted Server** and enter your Control API URL

For detailed instructions, see the [README](https://github.com/jvannoyx4/NoLongerEvil-HomeAssistant#readme).
