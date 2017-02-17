# Northern Harvest Brewing Company - github.io page
The home of basic early stage brewery apps, prior to being moved to the private git repo. 
This is the place to quikcly build out a rough design and share it with internal parties, poior to moving forward with development. 

## Current Item - Fermentation Temprature Dashboard
Fermentation temprature is critical to the end product. 
With that, we desire to be able to monitor that temprature remotely, and recieve alerts if that temprature goes outside of a set range. 

This will be done using a small collection of Raspberry Pis connected to temprature probes installed in fermenter thermowells. 
These Raspberry Pi's should communicate back to the centralized cloud service without the need for any major networking or firewall changes, and have a config that can be cloned and quickly imaged onto multiple PIs for quick replacement and rollout. 

This portion of the project is the enpoint dashboard that will provide easy access from mobile devices on multiple platforms via simple web login. 
This dashboard will subscribe to the MQTT topic hosted by a centralized cloud server, and display the output of that topic in a sysicnt and easy to read fassion. 
