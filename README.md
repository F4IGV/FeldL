## Aperçu de FeldL

<img width="1078" height="915" alt="Capture d&#39;écran 2026-10-05 204828" src="https://github.com/user-attachments/assets/664885cf-91e2-410b-bef7-3de9437a296e" />

## 🇫🇷 Présentation

**FeldL** est un logiciel gratuit de communication **Hellschreiber pour Windows 10/11**, développé par **F4IGV**. Il permet d’émettre et de recevoir des messages avec un transceiver HF connecté à l’ordinateur par une interface audio.

Son interface associe des commandes modernes à une présentation inspirée des machines historiques : bande papier animée, rouleau d’impression, voyants RX/TX et affichage de la fréquence à tubes Nixie.

### Fonctionnalités principales

- **Sept modes d’émission et de réception :** Feld-Hell, Slow Hell, Feld-Hell X5, Feld-Hell X9, FSK-Hell 105, FSK-Hell 245 et Hell 80.
- **Police historique sur une grille de 7 × 14 demi-pixels**, utilisée pour l’émission dans tous les modes.
- **Deux présentations de réception :** double impression historique avec inclinaison naturelle, ou impression unique avec auto-alignement et correction progressive de la dérive verticale.
- **Historique papier défilant** des messages reçus et envoyés pendant la session, avec export en PNG.
- **Waterfall audio**, réglage de la tonalité, du seuil de réception et du contraste, avec accord automatique pour les modes à porteuse unique.
- **Macros personnalisables** et profil de station pour préparer les échanges.
- **Sélection des périphériques audio** et réglage du niveau d’émission.
- **Commande du PTT** en mode manuel/VOX, par RTS ou via Hamlib CAT.
- **Hamlib intégré** pour lire et modifier la fréquence du poste, selon les possibilités du modèle utilisé.
- **Export WAV et tests de réception depuis un fichier audio**, notamment pour les essais avec un câble audio virtuel.
- **Interface en français, anglais et allemand**, avec conservation des réglages et mise à jour intégrée.

FeldL restitue les caractères reçus sous forme d’image sur la bande papier : leur lecture reste visuelle, comme sur les machines Hellschreiber originales.

### Installation

La version installable fonctionne sans installation préalable de Python. Sélectionnez les périphériques audio et configurez la commande du poste dans **Réglages**, puis commencez vos essais avec un faible niveau audio d’émission.

Les versions sont disponibles dans la section [Releases](https://github.com/F4IGV/FeldL/releases).

### État du projet

FeldL est actuellement en **version alpha**, sous développement actif. Les essais locaux et les premiers contacts radio permettent d’améliorer progressivement le logiciel. La compatibilité avec d’autres logiciels et stations reste à vérifier pour l’ensemble des modes.

Les retours d’expérience, rapports de bugs et résultats d’essais sont les bienvenus dans les [Issues](https://github.com/F4IGV/FeldL/issues).

---

## 🇬🇧 Overview

**FeldL** is a free **Hellschreiber communication application for Windows 10/11**, developed by **F4IGV**. It allows you to transmit and receive messages using an HF transceiver connected to your computer through an audio interface.

Its interface combines modern controls with a display inspired by historical machines: animated paper tape, a printing roller, RX/TX status lamps, and a Nixie-style frequency display.

### Main Features

- **Seven transmission and reception modes:** Feld-Hell, Slow Hell, Feld-Hell X5, Feld-Hell X9, FSK-Hell 105, FSK-Hell 245, and Hell 80.
- **Historical character font using a 7 × 14 half-pixel grid**, used for transmission in all modes.
- **Two reception display options:** historical double printing with its natural slope, or a single print with automatic alignment and progressive vertical drift correction.
- **Scrolling paper history** of messages received and transmitted during the session, with PNG export.
- **Audio waterfall**, adjustable tone, reception threshold, and contrast, with automatic tone tracking for single-carrier modes.
- **Customizable macros** and a station profile to prepare exchanges.
- **Audio device selection** and adjustable transmit audio level.
- **PTT control** through manual operation/VOX, RTS, or Hamlib CAT.
- **Integrated Hamlib support** for reading and changing the radio frequency, depending on the capabilities of the selected model.
- **WAV export and reception tests from audio files**, including tests through a virtual audio cable.
- **French, English, and German interface**, with persistent settings and a built-in update feature.

FeldL reproduces received characters as an image on the paper tape: messages are read visually, just as on the original Hellschreiber machines.

### Installation

The installable version does not require a separate Python installation. Select your audio devices and configure radio control under **Settings**, then begin testing with a low transmit audio level.

Downloads are available in the [Releases](https://github.com/F4IGV/FeldL/releases) section.

### Project Status

FeldL is currently an **alpha release** under active development. Local testing and initial on-air contacts help improve the application. Compatibility with other applications and stations still needs to be checked across all supported modes.

Feedback, bug reports, and test results are welcome in the [Issues](https://github.com/F4IGV/FeldL/issues) section.

**73 de F4IGV**
