# Einrichtung Raspberry PI
## Ressourcen
- Raspberry PI 2
- MicroSD Karte
- Lan-Kabel
- Tastatur
- Maus
## Anforderungen zur Einrichtung
### Aktuelles Image nutzen
- Image: https://downloads.raspberrypi.com/raspios_armhf/images/raspios_armhf-2025-12-04/2025-12-04-raspios-trixie-armhf.img.xz
### Nutzernamen
- Username: piadmin
- Passwort: Klassenname in Kleinbuchstaben verwenden (z.b. 23-it3)
### Hostname
- Hostname: rpiXX (XX Koffernummer 01 bis 24)
### Benötigte Schnittstellen
- SSH, VNC, Eindraht-Bus (One-Wire)
### Benötigte Pakete
#### PiGpio
- Info: https://abyz.me.uk/rpi/pigpio/
- Pakete: pigpiod pigpio pigpio-tools
- Zusatz: Der pigpio Deamon soll immer automatisch gestartet werden
#### Mosquitto
- Info: https://mosquitto.org/
- Pakete: mosquitto mosquitto-clients
### Update des Systems
- System auf den aktuellen Stand bringen