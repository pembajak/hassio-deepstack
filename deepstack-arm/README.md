# Home assistant add-on: DeepStack CPU - Server

Using a Deep Stack with a processor. The Deep Stack CPU version is slower than the GPU version.

### Installation
Install and run the DeepStack addon(server). You don't need to make any settings. After launching the DeepStack addon(server), click on the web interface. If the DeepStack(server) home page has opened, then DeepStack(server) is running and ready to work. It remains to install DeepStack Trainer(client) for DeepStack training (server) and face and object recognition testing.

DeepStack(server) is available on port 7000. You can access it by clicking on the web interface button

4 options have been added to DeepStack(server) and they are enabled by default:
* VISION-FACE - face recognition
* VISION-DETECTION - object recognition
* VISION-SCENE - scene recognition
* MODELSTORE-DETECTION - recognition of user models


### Sources

[Deep Stack Documentation](https://docs.deepstack.cc)

[Download images](https://registry.hub.docker.com/r/deepquestai/deepstack/tags)


### Integration into Home assistant
[HASS-DeepStack-Face](https://github.com/robmarkcole/HASS-Deepstack-face): face recognition, registration and recognition

[HASS-DeepStack-Object](https://github.com/robmarkcole/HASS-Deepstack-object): discovery of shared and custom objects

[HASS-DeepStack-Scene](https://github.com/robmarkcole/HASS-Deepstack-scene): scene recognition

