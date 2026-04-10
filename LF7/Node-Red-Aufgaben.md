# Aufgabe 1 - Co2 Level

## Anforderung

1 Textfeld soll folgenden Text zeigen, wenn das Co2 entsprechend gemessen wird:​
​
- Wert <= 1000 : "Co2 Level: Gut"​
- 1000 < Wert <=1500  : "Co2 Level: OK"​
- 1500 < Wert        : "Co2 Level: Schlecht"​

## Bonus

Die Farbe des Textfelds soll sich entsprechend dem  Level auf grün, orange, rot ändern.​

## Mögliche Node-Red Knoten

Switch, Change

# Aufgabe 2 - Fenster öffnen bei voller Klasse
​
## Anforderung

Wenn das Co2 Level auf über 1500 ppm steigt und gleichzeitig mehr als 20 Schüler anwesend sind, soll ein Text: "Co2 kritisch – Sofort lüften!" erscheinen ansonsten zeigt der Text: "Alles ok!"​

## Mögliche Node-Red Knoten

Join, Function

# Aufgabe 3 - REST API für alle Sensorwerte

## Anforderung

Es soll eine API Schnittstelle /api/rooms/401 geben, die alle aktuellen Sensorwerte des Raums 401 zurückgibt, um diese in anderen Services zu verarbeiten.

## Mögliche Node-Red Knoten

HTTP In, HTTP Response, Function
​

​