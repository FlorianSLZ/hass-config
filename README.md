My Blog: [scloud | All about Microsoft 365 & Enterprise Mobility + Security](https://scloud.work/)
# Home Assistant Configuration

[Hass.io](https://home-assistant.io/) installed on a Intel NUC, Acces via Amazon Fire HD 5, Lenovo M10 (with Dock), Mobile App (iOS) and Tesla. 
![dashboard.png](https://github.com/FlorianSLZ/hass-config/blob/main/dashboard.png?raw=true)
[Short Demo](https://www.reddit.com/r/homeassistant/comments/rg65o2/latest_take_on_my_ha_dashboard_for_tablets_in_the/)

## Hardware
|Type|Hardware|
|---|---|
|Host|Intel NUC|
|Zigbee|ConBee II|
|Cameras|Blink Sync Module 2, 2 cameras, local storage|
|Voice Assistant|Alexas & Homepod mini|
|Motion Sensors|Sonoff, Xiaomi, Aqara|
|Windows Sensor|Aqara, Xiaomi|
|Temperature Sensor|Aqara|
|WLAN|Unifi, AP Nano und Pro|
|Wall Switch (addon)|Shelly 1, 1L|
|Wall Switch|Aqara E1|
|Switches|Xiaomi, Aqara|
|Vacuum|Roborock 5|
|Light|Yeelight Stripe and Bulps|
|Car|Tesla Model 3|
|Music|Spotify|

## Integrations
### System
|Name|Description|Source|
|---|---|---|
|Blink|Cameras|default|
|HACS|more integrations from our community|https://hacs.xyz/docs/configuration/start|
|HomeKit|Connector to Homekit to use with Apple Home on iPhone and iPad|default|
|Mobile App|HA App|default|
|Shelly|Shelly Switch Integration|HACS: https://github.com/StyraHem/ShellyForHASS/blob/master/README.md|
|Spotify||default|
|Tesla|Control climate and doors|HACS: https://github.com/alandtse/tesla|
|Xiaomi Miio|Vacuum integration|default|
|Yeelight|Light control|default|
|ZHA|ConBee/Zigbee|default|

## Lovelace
|Name|Description|Source|
|---|---|---|
|bar-card||https://github.com/custom-cards/bar-card|
|Sidebar|Sidebar in my dashbiard, config in ui-ovelace.yaml|https://github.com/DBuit/sidebar-card|
|Button-card|better buttons with templates|https://github.com/custom-cards/button-card|
|card-mod|css for any card|https://github.com/thomasloven/lovelace-card-mod|
|mini-graph-card|lovely graph ui|https://github.com/kalkih/mini-graph-card|
|layout-card|control over the placement of lovelace cards|https://github.com/thomasloven/lovelace-layout-card|

