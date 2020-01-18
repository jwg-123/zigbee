---
model: 8087-16
vendor: Paul Neuhaus 
title: Q-Flag LED Panel 
category: light
supports: on/off, brightness, colortemp, colorxy
image: /assets/images/devices/100.110.39.jpg
zigbeemodel: ['NLG-RGBW light ']
compatible: z2m
mlink: https://www.paul-neuhaus.de/shop/de/led-panel-smart-home-alexa-tauglich-100-110-39.html
link: https://www.amazon.de/dp/B0154L54VY
link2: https://www.conrad.com/p/paul-neuhaus-q-led-wall-and-ceiling-light-q-flag-built-in-led-30-w-warm-white-rgb-1389103
link3: https://www.idealo.de/preisvergleich/OffersOfProduct/5533400_-q-flag-led-panel-30w-100-110-39-paul-neuhaus.html
---
Article #: 100.110.39 
### Device type specific configuration
*[How to use device type specific configuration](https://www.zigbee2mqtt.io/information/configuration)*

`transition`   
Controls the transition time (in seconds) of brightness, colortemp (if applicable) and color (if applicable) changes. Defaults to `0` (no transition).
Note that this value is overridden if a `transition` value is present in the MQTT command payload. 