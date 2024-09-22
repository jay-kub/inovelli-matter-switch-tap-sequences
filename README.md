# Inovelli Matter Switch Tap Sequences (Dev)
[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fjay-kub%2Finovelli-matter-switch-tap-sequences%2Fblob%2Fdev%2Finovelli-matter-switch-tap-sequences-dev.yaml)
### This blueprint will create an automation to:
- Perform predefined actions when a button on an Inovelli switch is tapped or held
- Bind the Inovelli Switches Light Entity to a Target Light
### Light Binding
 Light binding will sync the on/off state and brightness from the Inovelli Switch to a Target Light.
 Adjust the device settings as follows to make transitions more fluid:
 - Slow down the dimming speed on the Inovelli Switch to account for lag
 - Transition speed should be set to 0 for all devices
 - Default brightness when turned on should match for all devices
 - If the target light already has a device setting for minimum brightness, then leave the blueprint minimum brightness at 1
### Supported Models
- VTM31-SN (White Dimmer Switch)
- VTM35-SN (White Fan Switch)
- VTM36 (White Fan/Light Canopy Module)
Version 0.2
