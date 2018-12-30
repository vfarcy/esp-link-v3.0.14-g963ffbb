# esp-link-v3.0.14-g963ffbb

Bridge Wifi / RS232 

- Bien vérifier que les adresses des flashage soient les bons (Cf Images jointes)
- réduire la vitesse de flashage à 115200

Branchements (Arduino Uno     /                 Esp8266            /          PC USB)

RX   ----------------------------  TX

TX   ----------------------------  RX

3V3  ---------------------------- 3V3

GND  ---------------------------- GND

USB  -------------------------------------------------------USB (com éumulé) (**PAS OBLIGATOIRE : le montage peut être alimeté directement depuis le port alimentation de l'arduino UNO. Le montage est dans ce cas "autonome", et accessible en wifi via telnet**).



Application avec l'émulateur KIM-1 (carte de développement pour 6502) pour arduino Uno (voir dossier KIMUNO) => connextion Telnet (port 23), sur l'adresse 192.x.x.x. Attention, la connexion série entre l'arduino Uno et l'esp8266 doit être paramétrée à 9600 bauds.


Références :
- https://github.com/jeelabs/esp-link/releases (au 20 12 2018, j'utilise la 3.0.14, non alpha) 
- https://projectaweek.com/2017/09/15/wireless-rs-232-with-esp-link-and-an-esp8266/
- http://obsolescence.wixsite.com/obsolescence/kim-uno-summary-c1uuh

