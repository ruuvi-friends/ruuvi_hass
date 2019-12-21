# ruuvi_hass
RuuviTag sensor for hass.io

Copy the contents of `custom_components` in this repo to `<config folder>/custom_components` (e.g. `/home/homeassistant/.homeassistant/custom_components/`).

The configuration.yaml has to be edited like this
```
sensor:
  - platform: ruuvi-hass
    mac: 'MA:CA:DD:RE:SS:00'
    name: 'livingroom'
    
  - platform: ruuvi-hass
    mac: 'MA:CA:DD:RE:SS:01'
    name: 'bathroom'
```
