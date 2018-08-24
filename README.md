# ruuvi_hass
RuuviTag sensor for hass.io

Copy ruuvi-hass.py to <config folder>/custom_components/sensor/ (e.g. /home/homeassistant/.homeassistant/custom_components/sensor/ruuvi-hass.py)

Add the following to "sensor" in your configuration.yaml
  - platform: ruuvi-hass
    mac: 'MA:CA:DD:RE:SS:00'
    name: 'livingroom'
