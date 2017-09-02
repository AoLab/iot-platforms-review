<p align = "center">
  <img src="https://thingsboard.io/images/thingsboard_logo.png" width=500 alt="thingsboard-logo">
</p>

## Platform specification

| Open source | Cloud based service | Purpose |
|:-----------:|:--------------------:|:-------:|
| [Yes](https://github.com/thingsboard/thingsboard) | No | General |

#### Applications
General purpose platform. Examples: bus tracking, energy monitoring.
Adding new functionality is easy with customizable widgets, rule engine and plugin system.

#### Type
1. Devices can't communicate with each other without server between them.
2. Applications communicate with server in the first layer and then server sends the request to
devices. There is no direct way.

## General Information

#### Scalability
Thingsboard is designed to distribute workload between multiple nodes without
single point of failure.

#### Database
Thingsboard uses Cassandra NoSQL database.
This database is optimized for storage of
timeseries data. Cassandra takes care of data
replication and provides scalable, reliable
and fault-tolerant storage.

#### Technology & Language
Java, Scala

- Akka - for actor system implementation
- Zookeeper - for services coordination
- gRPC - for high-performance RPC
- Cassandra - as a scalable and reliable database

#### Connectivity Protocols
- CoAP
- HTTP
- MQTT

#### Thing-Platform Interaction Types
- Events and Alarams
- ThingsBoard provides the ability to assign custom attributes to your entities and manage these attributes.
- ThingsBoard allows you to send remote procedure calls (RPC) from server side applications to devices and vice versa.

#### SDK 4 Things
The ThingsBoard IoT Gateway will help you to integrate devices
that are connected to legacy and third-party systems with ThingsBoard IoT platform.

#### Data Collection
Collect and store telemetry data in reliable way,
surviving network and hardware failures.
Access collected data using customizable web
dashboards or server-side APIs.

#### Event Management
ThingsBoard provides the ability to create and manage alarms related to your entities: devices, assets, customers, etc.

## Non-Functional Requirements

#### Security
- MQTT over SSL
- Device authentication
- Access Token based authentication
- X.509 Certificate based authentication

#### Reliability
ThingsBoard adopts consistent hashing to ensure scalability and availability.
Message from Device A that is received on a particular node may be
forwarded to the other node based on the hash of the device ID.
Although this introduces certain networking overhead,
it allows to process all messages from a particular device using corresponding device actor on a determined server
