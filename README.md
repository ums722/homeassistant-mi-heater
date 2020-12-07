# homeassistant-mi-heater for zhimi.heater.mc2 (tested) and zhimi.heater.zb1 (not tested)
- Modified component what was not correctly worked in HASS new version.
- Tested on zhimi.heater.mc2
- Not tested on zhimi.heater.zb1


xiaomi Smart Space Heater S（zhimi.heater.mc2） component for home-assistant
![p](https://cdn.weasy.io/users/xiaomi/catalog/mi_smart_space_heater_s.jpg)


### Install
place all files except README.md to your ````<home-assistant-config-path>/custom_components/miheater/````  path
### Configuration.yaml

````
climate:
  - platform: miheater
    host: <your device ip address>
    token: <your device miio token>
    name: xiaomi_heater
````


### Features

* supporting power on/off
* supporting setting temperature
* supporting read temperature from device

![xx](https://bbs.hassbian.com/data/attachment/forum/201812/25/003901jd82efz3hkgh639v.png)

### Notice
token must got from APP miio2.db, not from "miio discover" on PC
