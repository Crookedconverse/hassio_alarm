# Home Assistant - Custom Alarm Interface!

## Custom Alarm from "Gazos Calvertos" with Node Red, Unifi Cameras, TasmoAdmin, and Configurator.

This configuration uses the alarm system made by "Gazos Calvertos" with Node-Red which sends Unifi Video Stream Images via Slack and text message. The system will also call a phone number and using Google TTS deliver a message that the alarm has been triggered along with text messages with current images from Unifi Video cameras while also posting them in slack. 

### Features:
-Send Unifi Video Images via node red and email
-Call using Twilio with Google TTS
-Hassio WatchDog
-Posts Unifi Images to Slack via Node-Red and Drop Box
-Post Xiaomi Temperature sensor battery levels via Node-Red to Slack


### Make sure to set your own Local IPs on the following .yaml files.


### Contributor: 
- Gazos Calvertos
  - This config uses the NEW UI branch of his alarm system with node red and tasmoAdmin
  
- Follow Gazos Here: https://github.com/gazoscalvertos/Hass-Custom-Alarm/tree/newUI
