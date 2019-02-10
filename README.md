## Home-Assistant Configuration by [@panosmz](https://github.com/panosmz)
:house: [Home Assistant](https://home-assistant.io/) home-automation configuration files.

Currently running on a [Raspberry Pi 3](https://www.raspberrypi.org/products/raspberry-pi-3-model-b/) via a :whale: [Docker Compose](https://docs.docker.com/compose/) script. Complete guide on my blog [here](https://blog.panosmazarakis.com/multi-purpose-raspberry-pi-3-home-server-docker-traefik-nextcloud-ddclient/).

**Linked Containers:**
* [Traefik](https://hub.docker.com/_/traefik) - Traefik Reverse Proxy
* [MariaDB](https://hub.docker.com/r/hypriot/rpi-mysql/) - MariaDB MySQL Database
* [Mosquitto](https://hub.docker.com/_/eclipse-mosquitto) - Eclipse Mosquitto MQTT Broker

**My Devices:**
* [Google Home Mini](https://store.google.com/gb/product/google_home_mini)
* Generic RGB Smart Lightbulbs, connected with [Tuya](https://en.tuya.com/)
* [ESP8266](https://www.espressif.com/en/products/hardware/esp8266ex/overview)-Based Air-Quality & Temperature-Humidity Sensor - _[Blog Post](https://blog.panosmazarakis.com/esp8266-air-quality-temperature-humidity-sensor/)_
* [Plug-IoT](https://github.com/panosmz/plug-iot/blob/master/esp8266-devices/schematics/onoffSwitch.png) - Custom On/Off Switches
* Various custom [Wemos D1 Mini](https://wiki.wemos.cc/products:d1:d1_mini)-based devices - _Alarm, RGB Led Strip Controller, Motion Detector, IR Controller_