# xrevive

### [**English**](../README.md) · [**Deutsch**](README.de.md) · **Français** · [**Español**](README.es.md) · [**Italiano**](README.it.md) · [**Português (Brasil)**](README.pt-BR.md) · [**Русский**](README.ru.md) · [**العربية**](README.ar.md) · [**日本語**](README.ja.md) · [**简体中文**](README.zh-CN.md)

Un lanceur de bureau pour les jeux de la première Xbox recompilés avec [Xrecomp](https://github.com/Teraflopping/Xrecomp), avec les services en ligne du revival du Xbox Live sur [xb.live](https://xb.live).

## Télécharger la v0.1.14

[Télécharger pour Windows x64](https://github.com/Teraflopping/xrevive/releases/download/v0.1.14/xrevive_0.1.14_x64-setup.exe) · [Télécharger pour Linux (AppImage)](https://github.com/Teraflopping/xrevive/releases/download/v0.1.14/xrevive_0.1.14_amd64.AppImage) · [Tous les installateurs et notes de version](https://github.com/Teraflopping/xrevive/releases/latest)

Les exécutables de jeux hébergés prennent actuellement en charge **Windows x64**. Sous Linux, ils peuvent tourner via Wine ou Proton (expérimental). Les paquets macOS ne peuvent pas encore lancer de jeux.

## Fonctionnalités

- Ajoutez votre propre ISO ou dossier de jeu extrait, puis téléchargez l'exécutable correspondant. xrevive utilise la version Release d'un jeu quand elle existe, et demande avant d'installer une version Beta ou Alpha. Les dumps region-free, avec media patch, renommés ou re-signés d'un jeu pris en charge sont aussi reconnus.
- Parcourez n'importe quel jeu Release, Beta ou Alpha avant de l'installer : activité, mises à jour, classements, succès, addons et nombre de joueurs et de lobbies en direct, avec **INSTALL** directement sur sa page.
- Vérification automatique des mises à jour des jeux et du lanceur. Les mises à jour de jeux suppriment les anciens exécutables qu'elles remplacent, et les téléchargements viennent d'un serveur proche de vous et reprennent si la connexion est coupée.
- Connectez-vous avec xb.live (en commençant par le jeu en ligne de Midnight Club 3) et consultez vos amis, les lobbies en direct, les événements de la communauté et les classements. Si xb.live est indisponible, les jeux démarrent quand même hors ligne.
- Gérez les jeux installés : jouer, parcourir les fichiers locaux, désinstaller, et un onglet DLC/Addons où chaque mod a un interrupteur On/Off et les crédits de son créateur. **▶ PLAY** lance le jeu avec les mods activés, et les addons continuent de fonctionner après les mises à jour du jeu.
- Onglet Sauvegardes avec sauvegarde, restauration, importation, conversion de sauvegardes PS2 et éditeurs de sauvegardes pour Midnight Club 3 et NINJA GAIDEN Black.
- Le cache de shaders reste avec le jeu, donc seul le premier lancement compile les shaders.
- Des messages d'erreur clairs qui expliquent ce qui s'est mal passé et comment le corriger, dont un bouton **Allow xrevive in Windows Security** quand l'Accès contrôlé aux dossiers bloque une installation.
- L'espagnol, l'italien et l'arabe sont disponibles dans Paramètres > Langue ; en arabe, toute la fenêtre s'affiche de droite à gauche.
- Ajoutez les jeux installés à Steam (depuis les Paramètres ou la bibliothèque), avec jaquettes et Steam Input sur le Deck.
- Vérification du système pour Windows 8.1+ et Direct3D 11, avec l'option Jouer quand même.
- Les sauvegardes XB Online de l'ancien dossier `XBL-Hosted` sont copiées dans le dossier de sauvegardes habituel de chaque jeu quand vous appuyez sur Play. Les sauvegardes existantes ne sont jamais remplacées et rien n'est supprimé ; une fois vos sauvegardes vérifiées, vous pouvez supprimer `SaveData\XBL-Hosted` vous-même.

## Vous apportez les jeux

xrevive n'inclut aucune ISO ni aucun fichier de jeu. Utilisez vos propres fichiers de jeu. Cette version télécharge des exécutables publiés au lieu de compiler les jeux localement ; les jeux sans exécutable disponible peuvent être extraits pour plus tard.

Le lanceur et l'installateur Windows sont signés Authenticode. Les mises à jour du lanceur sont signées avec la clé de mise à jour de xrevive. Les paquets macOS ne sont pas notariés, des alertes de sécurité peuvent donc apparaître lors de la première installation sur macOS.

---

xrevive est un projet de fans. Il n'est ni affilié à Microsoft ni approuvé par Microsoft.
