# llSPS-INT-1372-Smart-Agriculture-system-based-on-IoT

## Smart Agriculture system based on IoT
###### A Node-Red application for the farmer to know the weather and soil conditions of his/her farm and operate the irrigation system from a remote place.
### Installation
###### * Python IDLE should be installed.
###### * Node-Red should be installed locally.

### Services used:
###### * Node-red for creating flows,ui and integrating all the services used into the flow.
###### * IBM Watson IOT Platform to act as a MQTT broker for publish-subscribe model used for events and commands from remote devices.
###### * IBM Watson IOT simulator to simulate the remote sensors and send events in the form of json file.
### Running the application:
###### * Run the node-red by typing "node-red" in command prompt.
![Node-red](https://user-images.githubusercontent.com/35992360/84074720-95e0bc00-a9f0-11ea-945e-53fa3c844b37.jpg)
###### * Copy the URL on which node-red flow editor is running and paste it into your browser.
###### * Import the file named Smart_Agriculture_Flow.json in the node red flow editor and you will get the following two snapshots in your flow.
![Flow1](https://user-images.githubusercontent.com/35992360/84078166-0e964700-a9f6-11ea-8a3e-0dbbe25bbdb5.jpg)
![Flow2](https://user-images.githubusercontent.com/35992360/84078169-10600a80-a9f6-11ea-9d46-cdec062e26bf.jpg)
###### * Now,you have to open [watson-iot-sensor](http://watson-iot-sensor-simulator.mybluemix.net/) and put credentials as stored in [file](https://github.com/SmartPracticeschool/llSPS-INT-1372-Smart-Agriculture-system-based-on-IoT/blob/master/Iot_device_for_events_credentials.txt). Now, your IBM IOT device will be subscribed to the IOT sensor simulator as shown in the following image. 


