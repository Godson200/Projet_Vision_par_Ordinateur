# Contrôle Arduino avec Python et Vision par Ordinateur

Ce projet combine la **vision par ordinateur** et l'électronique embarquée pour contrôler des **LEDs** avec des gestes de la main détectés via une webcam. Grâce à **Python**, à la bibliothèque **cvzone**, et à une communication **série** avec **Arduino**, il est possible de créer une interaction simple et fluide entre logiciel et matériel.

## Fonctionnalités

- Détection des gestes de la main avec la webcam.
- Contrôle des LEDs en fonction des gestes détectés.
- Communication en temps réel entre **Python** et **Arduino** via le port série.

## Technologies Utilisées

- **cvzone** : Une bibliothèque de vision par ordinateur qui simplifie l'intégration de la détection des mains et des gestes. Plus d'infos sur [cvzone GitHub](https://github.com/cvzone/cvzone).
- **Arduino** : Utilisé pour piloter les LEDs selon les gestes détectés. Pour en savoir plus, visitez [Arduino GitHub](https://github.com/arduino).

## Installation

### Prérequis

- Une carte **Arduino** (ex. : Arduino Uno).
- LEDs et résistances.
- Python installé sur votre machine.
- Une webcam pour la détection des gestes.

### Étapes

1. Cloner ce dépôt :
   ```bash
   git clone https://github.com/Godson200/arduino_with_python_and_cv.git
   ```

2. Installer les dépendances Python :
   ```bash
   pip install cvzone opencv-python pyserial
   ```

3. Suivre les instructions du projet pour configurer l'Arduino et le code Python.

## Futurs Développements

- Intégration de commandes vocales pour contrôler les équipements électroniques.
- Ajout d'autres capteurs pour une maison intelligente encore plus interactive.

