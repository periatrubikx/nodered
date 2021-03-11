# nodered

Installed Modules:

1. OPC UA
2. OPC DA
3. MQTT Broker
4. AWS IoT/Kenisis/S3/Dynamo etc..
5. Siemens S7 Controller
6. Siemens S7 MPI/PP/DP adapters
7. usb node

#Watchouts

If you run into issues for missing dependencies or compile issues due to packages not being installed locally, you can run the 'apk' command. 

for the libudev.h errors, install the following;

``apk add eudev-dev``



1. OPC UA Client - In order to connect to an OPC UA Endpoint, use host.docker.internal instead of the IP/hostname etc.
