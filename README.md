Dans le cadre d’un projet étudiant en binôme à l’ESEO Angers.

Développement d’un "TANK" : un petit robot à entraînement différentiel. Il sera commandé par Bluetooth via une application Android.
Pour l’utilisateur, l’objectif sera d’entrer en collision avec le TANK adverse. Chaque collision rapporte des points.

Détails techniques :
- Microcontrôleur STM32G431
- Module Bluetooth HC-05
- Négociation USB Power Delivery (STUSB4531)
- Chargeur et BMS pour batterie Li-ion (power management : BQ24800, équilibrage des cellules : BQ76905)
- Driver moteur LMD18200. Moteurs jusqu’à 55 V (théorique) et 3 A. On utilise ici des Maxon en 12 V.

À titre personnel, ce projet me permet surtout de tester la norme USB Power Delivery ainsi que la charge d’une batterie.
