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
1- Devices can't communicate with each other without server between them.
2- Applications communicate with server in the first layer and then server sends the request to
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

#### Connectivity Protocols

#### Thing-Platform Interaction Types

#### SDK 4 Things

#### Data Collection

#### Event Management

## Non-Functional Requirements

#### Security

#### Reliability
