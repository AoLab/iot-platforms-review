<h2>Platform specification</h2>
<div class="list-group">
  <div class="list-group-item">
    <h4 class="list-group-item-heading">Open Source</h4>
    <p class="list-group-item-text">
      Yes
      <a href="https://github.com/kaaproject/kaa"><i class="fa fa-github" aria-hidden="true"></i></a>
    </p>
  </div>
  <div class="list-group-item">
    <h4 class="list-group-item-heading">Cloud Based Service</h4>
    <p class="list-group-item-text">
      Yes
      <a href="https://www.kaaiot.io/"><i class="fa fa-cloud" aria-hidden="true"></i></a>
    </p>
  </div>
  <div class="list-group-item">
    <h4 class="list-group-item-heading">Applications</h4>
    <p class="list-group-item-text">
      Agriculture, Automotive, Consumer Electronics
      Healthcare, Industrial Automation, Logistics
      Smart City, Smart Energy, Smart Retail
      Sport and Fitness, Wearables, Telecom
    </p>
  </div>
  <div class="list-group-item">
    <h4 class="list-group-item-heading">Type</h4>
    <p class="list-group-item-text">
      Kaa offers a designated feature that enables messaging between devices. Each message has a user-defined structure.
      Messaging is enabled between devices belonging to the same “user”.
      <strong>BUT</strong> All messages are routed through the Kaa server.
    </p>
  </div>
</div>
<h2>General Information</h2>
<div class="list-group">
  <div class="list-group-item">
    <h4 class="list-group-item-heading">Architecture</h4>
    <p class="list-group-item-text">
      Flat Distribution
    </p>
  </div>
  <div class="list-group-item">
    <h4 class="list-group-item-heading">Database</h4>
    <p class="list-group-item-text">
      Some metadata is stored in an SQL database, but all of the endpoint-related data is stored in
      a NoSQL database. Kaa currently supports two options for NoSQL data storage:
      Cassandra and MongoDB. Kaa provides an abstraction layer for data storage,
      which means that you can develop and use plugins for other NoSQL databases.
    </p>
  </div>
  <div class="list-group-item">
    <h4 class="list-group-item-heading">Technology &amp; Language</h4>
    <p class="list-group-item-text">
      Java
    </p>
  </div>
  <div class="list-group-item">
    <h4 class="list-group-item-heading">Connectivity Protocols</h4>
    <p class="list-group-item-text">
      Kaa Protocol (KP) over MQTT, CoAP and TCP
    </p>
  </div>
  <div class="list-group-item">
    <h4 class="list-group-item-heading">Thing-Platform Interaction Types</h4>
    <p class="list-group-item-text">
      You can push data to your device by using either the Kaa configuration update or Kaa notifications.
      You can also group your devices by their
      profiles and then push updates to device groups instead of updating each device separately.
      You can push new configuration and/or notifications via either REST API or Web UI.
    </p>
  </div>
  <div class="list-group-item">
    <h4 class="list-group-item-heading">SDK 4 Things</h4>
    <p class="list-group-item-text">
      Kaa currently provides SDKs for C, C++, and Java.
    </p>
  </div>
  <div class="list-group-item">
    <h4 class="list-group-item-heading">Data Collection</h4>
    <p class="list-group-item-text">
      The data collection subsystem in Kaa is designed to collect records (logs) of pre-configured structure,
      store them in the client, transfer from the client to Operations service, persist on server for further processing,
      or submit to the immediate stream analysis.
    </p>
  </div>
  <div class="list-group-item">
    <h4 class="list-group-item-heading">Event Management</h4>
    <p class="list-group-item-text">
      The Kaa Events subsystem is designed to generate endpoint
      events in real time, send them to other endpoints of the
      same owner and to Kaa server for processing
    </p>
  </div>
</div>
