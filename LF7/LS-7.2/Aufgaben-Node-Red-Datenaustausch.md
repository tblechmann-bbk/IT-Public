# Arbeitsaufträge

1. Verbindet euer Node Red mit dem OPC UA Server (Milo) mithilfe der node-red-contrib-opcua erweiterung.
- Example-Flow: https://flows.nodered.org/flow/81f1c936430d822621c8fcdcf0475ff9/in/gzu0bJiFfpEb
- opc.tcp://milo.digitalpetri.com:62541/milo (anonymous)
Sucht die Daten zu Demo.Alarms.Plant.PowerHouse.P-101.Vibration und gebt die Vibrationsdaten als Debug-Nachricht aus

2. Schickt die Vibrationsdaten über einen Websocket raus und zeigt die Daten in der Webapp da. (Ihr könne localhost.run als SSH-Tunnel für den Websocket nutzen)

3. Schickt die Daten auch über MQTT über den öffentlichen Broker 
broker.hivemq.com auf einer für euch passenden Topic
4. Stellt die Daten in eurer App mithilfe von MQTT da

5. Speichert die Daten ein einer Datenbank und erstellt einen REST Endpunkt, der euch die letzten 5 Minuten der Daten liefert.
6. Zeigt die Historischen Daten in eurer Webapp an
