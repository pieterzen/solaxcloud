# SolaxCloud integration for Home Assistant.

## Installation
- Place this solaxcloud directory under the custom_components directory.
- Add the sensor to your configuration.yaml:
    ```
    sensor:
    - platform: solaxcloud
      token: TOKENID
    ```
- To obtain your token. Login to solaxcloud.com and click on Service > API in the left menu.
- Verify that the custom entities are available in home assistant.


## Documentation

Solax has made their API public, with documentation located in your Solax Cloud site (Services > API).
https://www.eu.solaxcloud.com:9443/proxy/api/getRealtimeInfo.do&sn=
