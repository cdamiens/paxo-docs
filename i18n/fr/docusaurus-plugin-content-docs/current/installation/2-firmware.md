# Flash du firmware

Instructions pour installer le firmware sur l'ESP.

## Méthode via le navigateur (Recommandée)

### Pré-requis

- Paxophone monté.
- Câble USB-C vers USB-A ou USB-C (selon le port disponible sur le PC)
- Navigateur Chrome ou Edge. Note: Test KO sur Chromium.

### Sur le navigateur

Se rendre sur le [site du Paxo](https://www.paxo.fr/flash).  
Dans le menu en haut à gauche, cliquer sur "Flasher".
![Screenshot1](/img/screenshots/Firmware-1.png)

### Brancher le paxophone

A cette étape, brancher le Paxophone sous tension au port USB de votre ordinateur.  
Cliquer sur le bouton "Connecter & installer PaxOS-9".  
Choisir le port sur lequel est branché le Paxophone (contient généralement "USB" dans son nom).  
Cliquer sur le bouton "Connexion".
![Screenshot4](/img/screenshots/Firmware-4.png)

### Lancer l'installation

Si le Paxophone est bien reconnu sur le port, une fenêtre proposant l'installation du système PaxOS s'affiche.  
Cliquer sur "Install PaxOS9 Alpha".
![Screenshot5](/img/screenshots/Firmware-5.png)

Une fenêtre vous propose d'effacer votre appareil.  
Laisser la case décochée et cliquer sur "Next".
![Screenshot6](/img/screenshots/Firmware-6.png)

Une fenêtre de confirmation s'affiche.  
Cliquer sur "Install".
![Screenshot7](/img/screenshots/Firmware-7.png)

L'installation s'effectue et la progression s'affiche.  
Environ 2 minutes sont nécessaires pour terminer cette étape.
![Screenshot8](/img/screenshots/Firmware-8.png)

## Fin de la procédure

L'installation est maintenant terminée.  
Cliquer sur "Next".  
Débrancher le Paxophone.
![Screenshot9](/img/screenshots/Firmware-9.png)

## Méthode manuelle

Il est possible de compiler le système depuis les sources et de flasher le Paxophone grâce à PlatformIO.  
Les instructions sont détaillées directement dans le [GitHub du PaxOS](https://github.com/paxo-phone/PaxOS-9/#getting-started).
