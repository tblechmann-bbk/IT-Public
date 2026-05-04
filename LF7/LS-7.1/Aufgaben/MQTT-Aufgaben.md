Auf dem Host pc401lehrer läuft ein MQTT Broker​

Mithilfe der Kommandozeilen-Tools `mosquitto_sub` und `mosquitto_pub` auf den Schueler-PCS lassen sich Nachrichten schicken und empfangen.​

Recherchiere den Umgang mit dem Konsolentool und bearbeite die folgenden Aufgaben:

## Aufgabe 1 – Topics & Wildcards
Ziel: Topic-Strukturen verstehen und Wildcards sicher anwenden.

Aufgaben:
1. Wählt ein gemeinsames Topic-Schema.
2. Subscribed auf einem Gerät auf dem Topic
3. Published eine Nachricht auf der Topic auf einem anderen Gerät
4. Testet die Wildcards `+` und `#` mit verschiedenen Mustern.
5. Entwickle ein sinnvolles Szenario, in dem "Retained Messages" verwendet werden sollten.

---

## Aufgabe 2 – Retain
Ziel: Verstehen, wie retained Messages funktionieren und wie man sie löscht.

Arbeitsaufträge:
1. Publish eine retained Nachricht
2. Lest die Retained Nachricht mit einem neuen Subscriber
3. Löscht die retained Nachricht wieder
4. Entwickle ein sinnvolles Szenario, in dem "Retained Messages" verwendet werden sollten.

---

## Aufgabe 3 – Last Will
Ziel: Last Will konfigurieren und das Verhalten bei unerwartetem Client-Ausfall beobachten.

Arbeitsaufträge:
1. Startet einen Subscriber mit gesetztem Last Will
2. Beobachtet mit einem anderen Subscriber das entsprechende Topic.
3. Löst den "Last Will" aus
4. Entwickle ein sinnvolles Szenario, in dem "Last Will" verwendet werden sollte.
 
---

## Aufgabe 4 – QoS (Quality of Service)
Ziel: Unterschiede zwischen QoS 0/1/2 kennenlernen.

Die QoS Level lassen sich leider schwierig praktisch testen.

Arbeitsaufträge:
1. Benenne die die Bedeutung der unterschiedlichen QoS Level 0/1/2.
2. Entwickle ein oder mehrere Szenarien, in dem die unterschiedlichen QoS Level benutzt werden sollten.

---
