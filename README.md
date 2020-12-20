# virtuel109
Mise en place d'un monde virtuel multiplayer avec Unity 3D

1 Un jeu multiplayer

2 Un voice chat

3 Des événements live audiovisuel

4 Un atelier de créations d'avatar

5 Un atelier d'animation d'avatars pour la danse

6 Un shooter pour la création

Les ressources actuelles

Multiplayer avec serveur photon
https://assetstore.unity.com/packages/tools/network/pun-2-free-119922
Créer un compte photon
Intialiser l'idphoton dans l'asset Unity
Tester une demo

Voice chat avec serveur photon
https://assetstore.unity.com/packages/tools/audio/photon-voice-2-130518
ou
Pour la voice, sur secondlife(tm) et opensimulator, c'est vivox qui marche bien et j'ai appris qu'ils se concentrent maintenant sur unity :
https://unity.com/fr/products/vivox


Jeu third person avec avatar humain
https://assetstore.unity.com/packages/templates/systems/3rd-person-controller-fly-mode-28647

Live event 
Pas tester d'asset encore ...

Objectif 01 OK :
Fusionner ces assets pour obtenir un jeu multiplayer third person avec avatar humain, voice chat

Fusionner PUN 02 multiplayer et 3rd person shadow avatar ok ...

Fusioner shadow avatar multijoueur avec demos photon voice 02
Photon voice 02 signale beaucoup d'erreur et d'avertissement !
Utilisation de la demo DemoProximityVoiceChat avc photon voice 02 : Ca fonctionne bien et sans erreur ...
Utilisation de l'asset du player shadow avec photon multiplayer et chat voice : Ok
Impossible de compiler avec une plateforme WEBGL. Le micro en ligne n'est pas géré par Unity.
Build pour PC est ok
Par contre un bug entre unity 2020 et photon sur le load d'un préfab. Il faut modifier la scene et enregistrer pour qu'il trouve l'adresse du Gameobject
dans le dossier ressource !

Objectif 02 OK :
Live event transmettre un flux audio vidéo direct dans le monde virtuel
Echec avec cet assert : Problème de libvlc et libvlvcharp, de versions pour utiliser youtube eb steaming !
https://assetstore.unity.com/packages/tools/video/vlc-for-unity-windows-133979?_ga=2.207868946.1415717634.1608268456-584206554.1606133392

J'ai donc essayé une autre solution : Agora.io un serveur de chat vidéo !
https://assetstore.unity.com/packages/tools/video/agora-video-sdk-for-unity-134502
Excellent pour faite du direct !
Les demos fonctionnent et j'ai rapidement créer un compte agora pour vaoir un IB live stream.

Objectif 03 :
Pouvoir selectionner différents avatars
Atelier de fabrications d'avatars

