# Arbeitsaufträge

1. Verbindet euer Node Red mit dem OPC UA Server (Milo) mithilfe der node-red-contrib-opcua erweiterung.
- Example-Flow: https://flows.nodered.org/flow/81f1c936430d822621c8fcdcf0475ff9/in/gzu0bJiFfpEb
- opc.tcp://milo.digitalpetri.com:62541/milo (anonymous)
Sucht die Daten zu Demo.Alarms.Plant.PowerHouse.P-101.Vibration und gebt die Vibrationsdaten als Debug-Nachricht aus

Link zu einer Webbasierten Client Anwendung für OPC UA: https://opcua.twinedgeai.com/ dort lässt sich die Node Id zu den Vibrationsdaten auslesen.

2. Schickt die Vibrationsdaten über einen Websocket raus und zeigt die Daten in der Webapp da. (Ihr könne localhost.run als SSH-Tunnel für den Websocket nutzen)
3. Schickt die Daten auch über MQTT über den öffentlichen Broker broker.hivemq.com auf der Topic /bbk-lf7/<kistennummer>/power-house/vibration
  
3.1. "horcht" auch auf fremden Topics der anderen Gruppen, gibt es Unterschiede ?

4. Abonniert die Daten über MQTT in eurer APP und stellt sie als Text dar.
5. Speichert die Daten ein einer relationalen Datenbank und erstellt einen REST Endpunkt, der euch den Durchschnitt der letzten 5 Minuten zurückgibt
   
5.1. Notiert das/die Relationsschema

5.2. Notiert die SQL Query, um die Daten abzugreifen

7. Erstellt einen weiteren REST Endpunkt, der euch die Daten der letzten 5 Minuten liefert.
8. Zeigt die Historischen Daten in eurer Webapp an (zb. mit chart.js)
9. Welche Datenmengen fallen bei euch an einem Tag an Messwerten an ?

9.1. Wie lassen sich die Datenmengen reduzieren ?

10. Erstellt auch in Node Red ein Dashboard mit dem aktuellen Messwert mithilfe von FlowFuse Node-RED Dashboard 2.0
