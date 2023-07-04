# NeopoolHomeAssistant

WIP, Currently tested with Hayward Aquarite+ 

1- The helpers in homeassistant. Those are used to set values for pH, RedOX, ... (see configuration.yaml)
2- The helpers automation, when an helper is updated the automation is triggered to send helper value over mqtt (see Helpers_Automation)
3- Create the mqtt items (switch, select). Those are used to receive / send command to Tasmota over mqtt (see configuration.yaml)
4- Refresh the data in HA when Tasmota has refreshed values from the pool (see PoolRefresh)
5- Install your dashboard (smartpool_dashboard)

![image](https://github.com/fdebrus/NeopoolHomeAssistant/assets/33791533/fec0f629-3a00-4a97-9854-ce21e1164951)


**Dependencies**

Install and configure the Neopool for Tasmota, how to https://tasmota.github.io/docs/NeoPool/
Configure MQTT to connect the Tasmota module to HomeAssistant.

![image](https://github.com/fdebrus/NeopoolHomeAssistant/assets/33791533/5b1388a1-e8fa-41fa-bf44-a80831af3bb0)



