# Home Assistant Add-on TTLock

> This is a **WORK IN PROGRESS**. Help with testing and report bugs [here](https://github.com/z-jack/ttlock-hass-addons/issues).

## Requirements
- Bluetooth adapter compatible with [@abandonware/noble](https://github.com/abandonware/noble)
- MQTT broker (optional but recommended if you want to report lock status in HA and use it for automations)

## Features
- Ingress Web UI for
  - Pair new lock
  - Unpair lock
  - Lock / unlock
  - Manage auto-lock time
  - Manage sound on/off
  - Add / edit PIN codes
  - Add / remove IC Cards
  - Add / remove fingerprints
  - View operations log
  - Get updates about lock / unlock status
- (optional) HA reporting and controling via `lock` domain device using MQTT discovery
  - Signal level
  - Battery level
  - Lock/unlock status

## Screenshots

### Lock list  
![Lock list](https://raw.githubusercontent.com/z-jack/ttlock-hass-addons/master/ttlock-hass-integration/img/frontend1.png)  

### Credentials  
![Credentials](https://raw.githubusercontent.com/z-jack/ttlock-hass-addons/master/ttlock-hass-integration/img/frontend2.png)  

### Add fingerprint  
![Add fingerprint](https://raw.githubusercontent.com/z-jack/ttlock-hass-addons/master/ttlock-hass-integration/img/frontend3.png)  

### HA device
![HA device](https://raw.githubusercontent.com/z-jack/ttlock-hass-addons/master/ttlock-hass-integration/img/ha1.png)  

