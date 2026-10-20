# xrevive

### [**English**](../README.md) · [**Deutsch**](README.de.md) · **Français** · [**Español**](README.es.md) · [**Italiano**](README.it.md) · [**Português (Brasil)**](README.pt-BR.md) · [**Русский**](README.ru.md) · [**العربية**](README.ar.md) · [**日本語**](README.ja.md) · [**简体中文**](README.zh-CN.md)

Un lanceur de bureau pour les jeux de la première Xbox recompilés avec [Xrecomp](https://github.com/Teraflopping/Xrecomp), avec les services en ligne du revival du Xbox Live sur [xb.live](https://xb.live).

## Télécharger

[Télécharger pour Windows x64](https://github.com/Teraflopping/xrevive/releases/latest) · [Télécharger pour Linux (AppImage)](https://github.com/Teraflopping/xrevive/releases/latest) · [Tous les installateurs et notes de version](https://github.com/Teraflopping/xrevive/releases/latest)

Les exécutables de jeux hébergés prennent actuellement en charge **Windows x64**. Sous Linux, ils peuvent tourner via Wine ou Proton (expérimental). Les paquets macOS ne peuvent pas encore lancer de jeux.

## Fonctionnalités

- Ajoutez votre propre ISO ou dossier de jeu extrait, puis téléchargez l'exécutable correspondant. xrevive utilise la version Release d'un jeu quand elle existe, et demande avant d'installer une version Beta ou Alpha. Les dumps region-free, avec media patch, renommés ou re-signés d'un jeu pris en charge sont aussi reconnus. Un jeu installé depuis Beta ou Alpha passe à sa version Release par une mise à jour dès qu'il en existe une pour votre copie.
- Parcourez n'importe quel jeu Release, Beta ou Alpha avant de l'installer : activité, mises à jour, classements, succès, addons et nombre de joueurs et de lobbies en direct, avec **INSTALL** directement sur sa page.
- Vérification automatique des mises à jour des jeux et du lanceur. Les mises à jour de jeux suppriment les anciens exécutables qu'elles remplacent, et les téléchargements viennent d'un serveur proche de vous et reprennent si la connexion est coupée.
- Connectez-vous avec xb.live (en commençant par le jeu en ligne de Midnight Club 3), ajoutez des amis par gamertag et consultez les lobbies en direct, les événements de la communauté et les annonces XB Online. Si xb.live est indisponible, les jeux démarrent quand même hors ligne.
- Gérez les jeux installés : jouer, parcourir les fichiers locaux, désinstaller, et un onglet DLC/Addons où chaque mod a un interrupteur On/Off et les crédits de son créateur. **▶ PLAY** lance le jeu avec les mods activés, et les addons continuent de fonctionner après les mises à jour du jeu.
- Onglet Sauvegardes sur la page de chaque jeu avec sauvegarde, restauration, importation, **Déplacer…** vers un dossier de votre choix, conversion de sauvegardes PS2 (aucun profil Xbox requis) et éditeurs de sauvegardes pour Midnight Club 3 et NINJA GAIDEN Black.
- Les sauvegardes importées depuis xemu fonctionnent même si une autre console les a signées : celles de NINJA GAIDEN Black et d'autres au format connu sont re-signées pour ce PC et marquées comme non vérifiées.
- Bandes-son personnalisées : un écran Musique pour créer des bandes-son et ajouter des morceaux MP3, FLAC, Ogg, WAV, M4A ou AAC que chaque jeu compatible joue (Midnight Club 3 à partir de sa mise à jour 1.0.7).
- Les mises à jour de titre de XB Online et les DLC s'installent automatiquement quand le jeu est fermé, et la liste Add-ons de chaque jeu affiche sa mise à jour de titre avec un interrupteur. Le jeu en ligne nécessite la mise à jour de titre : si elle manque ou est désactivée, Play demande s'il faut la télécharger (ou la réactiver) ou jouer hors ligne cette fois.
- Un jeu qui a des DLC sur la boutique XB Online les liste dans son onglet DLC/Addons avec Télécharger et Supprimer, et le jeu les trouve à son prochain lancement.
- Réglages par jeu depuis le menu du jeu : plein écran, résolution, VSync, format d'image, luminosité, contraste, saturation, anticrénelage, limite de FPS, et DirectX 12, DirectX 11 ou Vulkan. Midnight Club 3 a aussi sa propre liste de langues, y compris les addons de traduction portugais, russe et arabe.
- Temps de jeu pour chaque jeu, et des EXE de jeu qui gardent le même nom d'une mise à jour à l'autre pour que les profils du Panneau de configuration NVIDIA restent appliqués.
- Dans les Paramètres, choisissez si fermer la fenêtre laisse xrevive tourner dans la zone de notification ou le quitte. Les jeux qui redémarrent sur leur mise à jour de titre restent affichés en cours de jeu, avec le temps de jeu et la session en ligne conservés.
- Paramètres > Inspecteur de disque lit le titre, l'ID de titre, la version et la région d'une image disque et copie un rapport prêt à coller dans un rapport de bug.
- Le cache de shaders reste avec le jeu, donc seul le premier lancement compile les shaders.
- Des messages d'erreur clairs qui expliquent ce qui s'est mal passé et comment le corriger, dont un bouton **Allow xrevive in Windows Security** quand l'Accès contrôlé aux dossiers bloque une installation.
- 10 langues au choix dans Paramètres > Langue : anglais, allemand, français, espagnol, italien, portugais du Brésil, russe, arabe, japonais et chinois simplifié. En arabe, toute la fenêtre s'affiche de droite à gauche.
- Ajoutez les jeux installés à Steam (depuis les Paramètres ou la bibliothèque), avec jaquettes et Steam Input sur le Deck.
- Personnalisez vos jeux : faites un clic droit sur un jeu et ouvrez Gérer pour choisir votre propre bannière et icône (PNG ou JPEG). Sinon, la liste des jeux affiche l'icône de sauvegarde de chaque jeu tirée de son default.xbe, et Ajouter à Steam utilise les mêmes images.
- Vérification du système pour Windows 8.1+ et Direct3D 11, avec l'option Jouer quand même.
- Les sauvegardes XB Online de l'ancien dossier `XBL-Hosted` sont copiées dans le dossier de sauvegardes habituel de chaque jeu quand vous appuyez sur Play. Les sauvegardes existantes ne sont jamais remplacées et rien n'est supprimé ; une fois vos sauvegardes vérifiées, vous pouvez supprimer `SaveData\XBL-Hosted` vous-même.

## Vous apportez les jeux

xrevive n'inclut aucune ISO ni aucun fichier de jeu. Utilisez vos propres fichiers de jeu. Cette version télécharge des exécutables publiés au lieu de compiler les jeux localement ; les jeux sans exécutable disponible peuvent être extraits pour plus tard.

Le lanceur et l'installateur Windows sont signés Authenticode. Les mises à jour du lanceur sont signées avec la clé de mise à jour de xrevive. Les paquets macOS ne sont pas notariés, des alertes de sécurité peuvent donc apparaître lors de la première installation sur macOS.

---

xrevive est un projet de fans. Il n'est ni affilié à Microsoft ni approuvé par Microsoft.
