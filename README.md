# AGRO
Bedienungshinweise für das Angela Great Robotic Observatory (AGRO)

Manueller remote Betrieb

Die Steuerungssoftware KStars/Ekos läuft auf dem Raspberry Pi, der auf dem AGRO Teleskop montiert ist. Es muss zunächst eine VNC Verbindung zum Raspberry Pi hergstellt werden. Anschließend sind folgende Schritte durchzuführen:

1. KStars starten
2. Ekos mit ctrl+k öffnen
3. Profil "AGRO UPB" starten
4. Unter "Pegasus UPB" -> Power die Montierung, die CCD Kamera und das Filterrad einschalten
5. Profil "AGRO UPB" disconnecten und auflegen.

Nun ist die Hardware (Montierung, CCD, Filterrad) eingeschaltet und das Profil zur Steuerung aller Hardwarekomponenten kann gestartet werden:

1. Profil "AGRO" starten
2. Unpark Dome
3. Unpark Telescope
4. Slew to target
5. Autofocus
6. Align (Plate solve) 
7. Start guiding
8. Start observation
