# [Northern Harvest Brewing Company](https://www.northernharvest.beer) - [github.io](northernharvestbrewing.github.io] page
The home of basic early stage brewery apps, prior to being moved to the private git repo. This is the place to quickly build out a rough design and share it with internal parties, prior to moving forward with development.
## Current Item - Fermentation Temperature Dashboard
Fermentation temperature is critical to the end product. With that, we desire to be able to monitor that temperature remotely, and receive email, text, and or push alerts if that temperature goes outside of a set range.
This will be done using a small collection of Raspberry Pis connected to temperature probes installed in fermenter thermowells. These Raspberry Pi's should communicate back to the centralized cloud service without the need for any major networking or firewall changes, and have a config that can be cloned and quickly imaged onto multiple PIs for quick replacement and rollout.
This portion of the project is the endpoint dashboard that will provide easy access from mobile devices on multiple platforms via simple web login. This dashboard will subscribe to the MQTT topic hosted by a centralized cloud server, and display the output of that topic in a succinct and easy to read fashion.

## Dashboard Framework
The dashboard front-end will be based upon the ever popular [Bootstrap](https://github.com/twbs/bootstrap) framework, together with ready made bootstrap dashboard layout [Gentelella](https://github.com/puikinsh/gentelella). 

