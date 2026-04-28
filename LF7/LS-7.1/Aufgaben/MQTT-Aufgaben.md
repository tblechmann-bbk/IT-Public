Auf dem Host pc401lehrer läuft ein MQTT Broker​

Mithilfe der Kommandozeilen-Tools `mosquitto_sub` und `mosquitto_pub` lassen sich Nachrichten schicken und empfangen.​

Recherchiere den Umgang mit dem Konsolentool und bearbeite die folgenden Aufgaben:

## Aufgabe 1 – Topics & Wildcards
Ziel: Topic-Strukturen verstehen und Wildcards sicher anwenden.

Aufgaben:
1. Wählt ein gemeinsames Topic-Schema.
2. Subscribed mit unterschiedlichen Clients und testet Wildcards mit verschiedenen Mustern.

Frage:
Wie werden `+` und `#` verwendet ?
Welche praktischen Beispiele fallen Ihnen für die Verwendung ein ?

---

## Aufgabe 2 – Retain
Ziel: Verstehen, wie retained Messages funktionieren und wie man sie löscht.

Aufgaben:
1. Publish eine retained Nachricht
2. Lest die Retained Nachricht mit einem neuen Subscriber
3. Löscht die retained Nachricht wieder

Frage:
Wozu kann Retained sinnvoll sein ?

---

## Augabe 3 – Last Will
Ziel: Last Will konfigurieren und das Verhalten bei unerwartetem Client-Ausfall beobachten.

Aufgaben:
1. Startet einen Subscriber mit gesetztem Last Will
2. Beobachtet mit einem anderen Subscriber das entsprechende Topic.
3. Löst den "Last Will" aus

Frage:
Wozu kann "Last Will" sinnvoll sein ?

---

## Aufgabe 4 – QoS (Quality of Service)
Ziel: Unterschiede zwischen QoS 0/1/2 kennenlernen.

Die QoS Level lassen sich leider schwierig praktisch testen.

Frage:
Welche Bedeutung haben die QoS Level 0/1/2 ?
Welche Einsatzzwecke gibt es für die verschiedenen Level ?

---
