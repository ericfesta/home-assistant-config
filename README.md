# Home Assistant Configuration

Here's my [Home Assistant](https://www.home-assistant.io) configuration. I have installed HA on an [Intel NUC8i5BEH](https://www.amazon.it/dp/B07JCF1LCL) with [16GB RAM](https://www.amazon.it/dp/B019FRBHZ0) and [500GB SSD](https://www.amazon.it/gp/product/B078WQT6S6). I am currently running [Proxmox VE](https://www.proxmox.com/en/proxmox-ve) on the NUC and used the [Home Assistant OS](https://www.home-assistant.io/hassio/installation) approach to install HA.

# Things that I run on my NUC
- [Home Assistant](https://www.home-assistant.io) in a Proxmox VE [VM](https://pve.proxmox.com/wiki/Qemu/KVM_Virtual_Machines)
- [Plex media server](https://www.plex.tv/media-server-downloads) in a [LXC](https://linuxcontainers.org/lxc/introduction/) container
- [Ubiquiti Unifi Network Controller](https://ui.com) in a [LXC](https://linuxcontainers.org/lxc/introduction/) container
- [Pi-Hole](https://pi-hole.net) in a [LXC](https://linuxcontainers.org/lxc/introduction/) container

# Some of the devices and services that I use with HA
- Networking
    - [Ubiquiti UniFi AP AC NanoHD](https://www.amazon.it/dp/B07FFNTLJD)
    - [Netgear GS108Ev3 Smart Managed Plus Switch](https://www.amazon.it/dp/B00MYYTP3S)
    - [Netgear GS105Ev2 Smart Managed Plus Switch](https://www.amazon.it/dp/B00GWKN1Q2)
- Sensors (Zigbee)
    - [Aqara Temperature, Humidity and Pressure Sensor](https://www.aqara.com/us/temperature_humidity_sensor.html)
    - [Aqara Door and Window Sensor](https://www.aqara.com/us/door_and_window_sensor.html)
    - [Aqara Motion Sensor](https://www.aqara.com/us/motion_sensor.html)
    - [Aqara Water Leak Sensor](https://www.aqara.com/us/water_leak_sensor.html)
    - [Conbee II USB Zigbee Gateway](https://www.amazon.it/dp/B07PZ7ZHG5)
- Sensors (WiFi)
    - [Shelly EM](https://shelly.cloud/products/shelly-em-smart-home-automation-device/)
- Lights
    - [Philips Hue White](https://www.amazon.it/dp/B016H0R7SE)
    - [Philips Hue Lightstrip](https://www.amazon.it/dp/B015LZ0PC6)
    - [Philips Hue Wellness Lamp](https://www.amazon.it/dp/B01L99HIHI)
    - [Shelly Dimmer](https://shelly.cloud/products/shelly-dimmer-2-smart-home-light-controller)
- Switches
    - [Shelly 1PM](https://shelly.cloud/products/shelly-1pm-smart-home-automation-relay)
    - [Gosund Smart WiFi Plug SP111v2](https://www.gosund.store/products/wi-fi-smart-plug-sp111-only-for-europe)
    - [Broadlink RM Mini 3](https://www.amazon.it/dp/B01FK2SDOC)
- Voice Interaction
    - Google Home with the Google Assistant
    - [Amazon Echo Dot](https://www.amazon.it/dp/B07PDHSPYD)
    - [Amazon Echo Plus](https://www.amazon.it/dp/B0794XQK5S/)
- Media
    - [Sonos Play:1](https://www.sonos.com)
- Notifications:
    - Telegram
    - TTS with the Amazon Echos
