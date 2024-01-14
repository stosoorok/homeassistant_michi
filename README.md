# Rotel component for Home Assistant
Custom components for Home Assistant

**Forked from**: [elric91/homeassistant_rotel](https://github.com/elric91/homeassistant_rotel)

A media_player platform that can be used through HASS to :
- turn on and off the amplifier
- adjust volume
- change source
- check status

## Installation 

1. Create a directory `roteltcp` in the `custom_components` directory of your Home Assistant configuration folder. 
   I.e:  `/home/user/.homeassistant/custom_components/roteltcp`
2. Copy the contents of this repository in the `roteltcp` directory.
    * Or at least `manifest.json`, `__init__.py` and `media_player.py`

## Configuration
Example minimal config (in configuration.yaml, dummy IP to be updated) :
```
media_player:
  - platform: roteltcp
    host: 192.168.1.12
```
