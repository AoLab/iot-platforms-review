## Platform specification
#### Open Source
[Yes](https://github.com/kaaproject/kaa)

#### Cloud Based Service
[Yes](https://www.kaaiot.io/)

#### Applications
Agriculture, Automotive, Consumer Electronics
Healthcare, Industrial Automation, Logistics
Smart City, Smart Energy, Smart Retail
Sport and Fitness, Wearables, Telecom

#### Type
Kaa offers a designated feature that enables messaging between devices. Each message has a user-defined structure.
Messaging is enabled between devices belonging to the same *user*.
**BUT** All messages are routed through the Kaa server.

## General Information

#### Architecture
Flat Distribution

#### Database
Some metadata is stored in an SQL database, but all of the endpoint-related data is stored in
a NoSQL database. Kaa currently supports two options for NoSQL data storage:
Cassandra and MongoDB. Kaa provides an abstraction layer for data storage,
which means that you can develop and use plugins for other NoSQL databases.

#### Technology & Language
Java

#### Connectivity Protocols
Kaa Protocol (KP) over MQTT, CoAP and TCP

#### Thing-Platform Interaction Types
You can push data to your device by using either the Kaa configuration update or Kaa notifications.
You can also group your devices by their
profiles and then push updates to device groups instead of updating each device separately.
You can push new configuration and/or notifications via either REST API or Web UI.

#### SDK 4 Things
Kaa currently provides SDKs for C, C++, and Java.

#### Data Collection
The data collection subsystem in Kaa is designed to collect records (logs) of pre-configured structure,
store them in the client, transfer from the client to Operations service, persist on server for further processing,
or submit to the immediate stream analysis.
  
#### Event Management
The Kaa Events subsystem is designed to generate endpoint
events in real time, send them to other endpoints of the
same owner and to Kaa server for processing.
