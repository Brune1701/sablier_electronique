# sablier_electronique


## Présentation

J'ai choisi de construire un minuteur, sablier, qui lance un compte à rebours de 60 sec. 
Le système s'actualise et recommence lorsqu'il est tourné, tel un sablier mécanique.


## Fonctionnement et Composants : 

- Détection de l'orientation avec le LIS3DH
- Microcontrôleur ATmega328P-AU
- 12 LEDs  pour représenter le sable qui s'écoule
- Compte à rebours de 60 secondes
- Buzzer en fin de minuterie
- Batterie rechargeable par USB-C

## Schéma électronique

![Schéma électronique](images/schema.png)

## PCB

![PCB](images/pcb.png)

## Vue 3D

![Vue 3D](images/3d.png)


## Tests

Le PCB sera soudé puis testé afin de vérifier :
- la détection de l'orientation ;
- le fonctionnement des LEDs ;
- le décompte de 60 secondes ;
- le fonctionnement du buzzer ;
- la recharge de la batterie.
