Comment créer un projet Godot sur SteamVR et Quest 3 avec GitHub
https://youtu.be/NtxuV1WpRPc


Vocabulaire:
Steam, SteamVR, ALVR, Godot, Meta Software, Git , Meta Account, Steam Linq, Meta Store, scrcpy, adb, mode developer
Meta Quest Develoer Hub, User Account Control Setting, Git, Vim, Nodepad, Version Control, .py , python, 
,language interpreter, language compiler ,`scrcpy.exe` ,`adb.exe`, PATH , .bat, android webcam,
webcam gauch et droit du quest, pairing steam, Steam Home, purgatoire steam, Alyx, window .bat shortcut,
Open XR, yyyy_mm_dd, nomenclature, Forward+/Mobile, .tscn XROrigine3D,  XRNode3D, XRCamera3D

Local Floor, Stage, Bend mode Alpha, VR v AR, Hand Tracking, Rendering Environment Color, RGB, RGBA 
MeshInstance3D, Cube, Mesh,
DirectionLight3D ,📕RTFM, XRServer.find_interface, .gd , Node vs Node3D , _ready(), func 
XRController3D, XRNode3D > Tracker,
StandardMaterial3D, Albedo > Color, Shader Mode, per-pixel, unshaded 

Godot Xr Tools, AssetLib, Addons, Plugin, shader, VRCommonShaderCache,
VR Sickness , bouger, tourner, teleporter , Pick, Highlight, Hand position, Snap board
Itchio, APK, .exe ,  Drag and drop , console, terminal, adb install
Unkown source, Menu Developper App,
ALVR, BitRate, Compression d image, Wifi Stream
Virtual Desktop, Streamer App, Meta User Name, 
Pico vs Dream vs Google vs Viveport vs Android XR
Start With Window, shell:startup, OpenXR Runtime Selection,
Adb screenshot, 
SourceTree , Fork, GitHub Desktop , 
git config, user.name, user.email , git blame, -- global
git init, repertoire
git description, readme.md, .md , .gitignore
public vs private
extension de fichier, fichier cacher, .git/
.gitignore, *.cfg, gitignore.io
stage, unstage, add, commit 
25,50,100Mo WinDirStat, MB, Mb et MO, Bytes
stage, fetch, pull, push
cmd, folder path, status, add . , commit -m , pull push
extends Node, _ready, _process, func, pass vs return, void ,delfat:float
print(), ""
visual studio code, vs visual studio, vs JetBrain
@export, var, nom_variable_membre: type_variable ,=, valeur_par_default,
# , ## , RTFM, Godot Docs
LM Studio , Hugging Face Copilote
@export , inspector, level designer, integrateur
CheatSheet,
Oculus Setup, Meta Horizon Link App , Meta, Auth.methat.com
Horizon... ,
developers.meta.com, portal,
Google Auth, QR Code, Cle de recuperation
Organisation Meta,
Quest, Standalone, PC Link App,
Source Inconnue (meta),
Air Link Mode, USB Linq Mode
Cable usb C a 10$ vs 70$
Block, Open Brush, Gravity Sketch, VR Painting
Four Hourseman of the open source ; Krita, Blender, Audacity, Godot, OBS
Remove Background et opera GX
.jpg . png .krita
Sprite3D
Scene, Nested Scene, Prefab, Nested Prefab
.tscn
Suzanne
Vertex Color, Vertex Painting, Shader, Degrader de couleur
.glb, .fbx , .obj ?.openusb?, uv map
File System > instanciate ( android)
Transform Scale / Rotate / Position
Rotation: Direction, Euler, Quaternion , 
Position: Unity Axis vs Godot Axis
CTRL + D Duplicate
Editable Children ( voir prefab variante sur Unity)
Make Local
 Blender Edit Mode Object Mode
Blender > UV > Export UV Layout
UV Grids
Credit , Source 

SketchFab, Vertex, Triangle, Low Poly, Hight Poly
96 triangles, 4k 10k 50k 65k | 200k 2M...
Texture 1k 4k | 8K 16K?
3D Pivot
AudioListener2D  AudioStreamPlayer3D
.wav .mp4 .ogg
BlockBench Ink, Gimp
OBS: Window Capture ADB
Cubisme, Laser Dance
VRTK, MRTK, XRTK, Godot TK
Icosphere, 
Cross Cube UV vs 8 Face UV vs 1 face UV
?Mixamo?
Sphere Parfait avec Blender
Export Template
Exercice: Faire et peindre un dee de D7D
Fausse luniere, Unshaded
Build folder, ?Old Build Disk?
Import ETC2 ASTC Texture
Java JDK, SDK, Oracle, OpenJDK
Android Studio, Android SDK
OpenJDK17

https://youtu.be/NtxuV1WpRPc?t=6848 Placons la UV Grid
https://youtu.be/NtxuV1WpRPc?t=6865 Commens on utiliser la UV Grid ?
https://youtu.be/NtxuV1WpRPc?t=6916 Noter que dans Godot  4.7 on aura un outil de dessins 3D ;)

https://youtu.be/NtxuV1WpRPc?t=6970 Importons un glb depuis SketchFab pour voir
https://youtu.be/NtxuV1WpRPc?t=7056 Sourcer votre telechargment
https://youtu.be/NtxuV1WpRPc?t=7068 Verifier la license
https://youtu.be/NtxuV1WpRPc?t=7129 Un pivot mal placer... 
https://youtu.be/NtxuV1WpRPc?t=7172 L import GLB de godot est manifiquement automatiser
https://youtu.be/NtxuV1WpRPc?t=7179 Ajoutons un emetteur de son dans notre radio 3D
https://youtu.be/NtxuV1WpRPc?t=7251 Ils nous faudrait donc un son. Allons chercher Audacity
https://youtu.be/NtxuV1WpRPc?t=7270 Sans MuseHub
https://youtu.be/NtxuV1WpRPc?t=7303 Allons telecharger un bruitage ou une musique
https://youtu.be/NtxuV1WpRPc?t=7357 Retirons le blanc au debut du son
https://youtu.be/NtxuV1WpRPc?t=7364 Creeons un FadeOut sur la fin du son 
https://youtu.be/NtxuV1WpRPc?t=7409 Exportons en ogg
https://youtu.be/NtxuV1WpRPc?t=7433 Ajouter sur AudioStreamer la music et ajoutons un auto play.
https://youtu.be/NtxuV1WpRPc?t=7458 Pour entre le son, il nous faut un ecouteur sur le camera AudioListener3D
https://youtu.be/NtxuV1WpRPc?t=7461 Attention, il vous faut celui de godot XR Tool pour un audio spacialiser
https://youtu.be/NtxuV1WpRPc?t=7532 D autres logiciels Open source ?  BlockBench Grimp Ink 
https://youtu.be/NtxuV1WpRPc?t=7586 Pour votre culture generale et la fin des gamejams, regardons a OBS
https://youtu.be/NtxuV1WpRPc?t=7626 Lancons l install  
https://youtu.be/NtxuV1WpRPc?t=7644 Allons retrouver notre dossier scrcpy installer plus tot.
https://youtu.be/NtxuV1WpRPc?t=7708 Capturer une fenetre a enregistrer dans OBS
https://youtu.be/NtxuV1WpRPc?t=7814 Cubisme et Laser Dance ;)
https://youtu.be/NtxuV1WpRPc?t=7864 Essayons d exporter notre projet pour le passer a un ami
https://youtu.be/NtxuV1WpRPc?t=7901 Ajoutons Window et constatons qu il nous manque quelque chose.
https://youtu.be/NtxuV1WpRPc?t=7903 Telechargons et installons Export Template
https://youtu.be/NtxuV1WpRPc?t=7955 Bon avant d exporter... Ajoutons un petit icosphere pour le plaisir d apprendre a utiliser blender
https://youtu.be/NtxuV1WpRPc?t=7971 Exportons un cube avec son UV en croix pour voir
https://youtu.be/NtxuV1WpRPc?t=8026 Creons une icosphere pour voir le prince des forme de blender
https://youtu.be/NtxuV1WpRPc?t=8081 Ajoutons notre cube a la scene avec une instance classique 
https://youtu.be/NtxuV1WpRPc?t=8111 Ajoutons lui ca texture
https://youtu.be/NtxuV1WpRPc?t=8131 Ajoutons notre icosphere en soleil du jeu
https://youtu.be/NtxuV1WpRPc?t=8148 D abord fictivement avec unshaded
https://youtu.be/NtxuV1WpRPc?t=8172 Remplacons le directional light par un OmniLight3D dans notre soleil
https://youtu.be/NtxuV1WpRPc?t=8237 Allons exporter notre projet pour de vrai
https://youtu.be/NtxuV1WpRPc?t=8244 Creaons un build folder.
https://youtu.be/NtxuV1WpRPc?t=8291 Tadaaam on a un exe godot XR 😎
https://youtu.be/NtxuV1WpRPc?t=8369 Essayons de l exporter pour Android XR...
https://youtu.be/NtxuV1WpRPc?t=8376 Une option de texture a cocher ETC2
https://youtu.be/NtxuV1WpRPc?t=8389 Petit probleme, un app android c est du java.
https://youtu.be/NtxuV1WpRPc?t=8393 Telechargons donc un JDK Java developer Kit et SDK (Oracle)
https://youtu.be/NtxuV1WpRPc?t=8507 On sait parler Java ;) Apprenons a parler Android
https://youtu.be/NtxuV1WpRPc?t=8518 telechargons Android Studio
https://youtu.be/NtxuV1WpRPc?t=8548 En lisant la doc... IL y a un autre version de java disponible OpenJDK17






































































 








JE SUIS ICI.






https://youtu.be/NtxuV1WpRPc?t=1359 Utilisons Blend Mode > Alpha pour faire de la realiter augmenter plus tard.

Node3D


- [ ] Avoir un compte GMail ?
  - [ ] Avoir Google Auth sur votre telephone ?
  - [ ] Avoir une double authentification ?
  - [ ] Avoir ajouter votre compte Gmail a Google Auth
  - [ ] 

https://youtu.be/NtxuV1WpRPc?t=3 Introduction
https://youtu.be/NtxuV1WpRPc?t=102 On y va ;)
https://youtu.be/NtxuV1WpRPc?t=120 Installer Grave et se connecter avec Gmail.
https://youtu.be/NtxuV1WpRPc?t=141 se connecter avec une double authentification
https://youtu.be/NtxuV1WpRPc?t=150 Telecharger Godot
https://youtu.be/NtxuV1WpRPc?t=164 Creer un dossier C:/exe/godot et y mettre Godot
https://youtu.be/NtxuV1WpRPc?t=178 Godot est une application portable (pas besoin d installer)
https://youtu.be/NtxuV1WpRPc?t=182 Godot est une application du web, authoriser a etre executer sur votre PC sur Window
https://youtu.be/NtxuV1WpRPc?t=198 Telecharger Steam pour installer Steam VR
https://youtu.be/NtxuV1WpRPc?t=222 Steam Guard et la double authentification 
https://youtu.be/NtxuV1WpRPc?t=244 Telecharger Steam VR depuis le store.
https://youtu.be/NtxuV1WpRPc?t=271 C est quoi Steam Linq et ou le trouver 
https://youtu.be/NtxuV1WpRPc?t=280 Histoire de pouvoir vous montrer l ecran de mon Quest, allons chercher Screen copy
https://youtu.be/NtxuV1WpRPc?t=299 Telecharger et extraire screen copy dans C:/exe/scrcpy/ 
https://youtu.be/NtxuV1WpRPc?t=329 Pour utiliser scrcpy, il vous faut un android en developer mode (telephone ou Quest)
https://youtu.be/NtxuV1WpRPc?t=350 Authorizer le pc a communiquer avec votre quest (USB Debugging) (accepter pour toujurs)
https://youtu.be/NtxuV1WpRPc?t=369 Si le message apparait pas, debrancher rebrancher, redemarrer les casques, changer de cables...
https://youtu.be/NtxuV1WpRPc?t=382 Tadaaam, vous voyez l ecran de mon casque ;)
https://youtu.be/NtxuV1WpRPc?t=384 Avec un belle grosse latence car la resolution est de 4000 pixel
https://youtu.be/NtxuV1WpRPc?t=388 Et outil clignote a cause de meta qui veut afficher et l ecran et le menu
https://youtu.be/NtxuV1WpRPc?t=408 Esseyons de telercharger Meta Quest Developer Hub pour debugger le casque
https://youtu.be/NtxuV1WpRPc?t=429 Telecharger le, on l utilisera plus tard. Moi il ne fonctionnait pas/plus avec Window 10.
https://youtu.be/NtxuV1WpRPc?t=448 Si vous avez le meme bug Developer Hub, ca ressemble a ca. Un gros ecran gris
https://youtu.be/NtxuV1WpRPc?t=463 Optionel: Retirer les firewalls et les securiters window
https://youtu.be/NtxuV1WpRPc?t=485 Retirons les notifications de droit administrateur pour pas accepter toutes les 5 minutes.
https://youtu.be/NtxuV1WpRPc?t=516 Pour continuer, il vous faux un compte GitHub. Je vous invite a en creer un
https://youtu.be/NtxuV1WpRPc?t=526 Allons chercher un boite a outil pour utiliser scrcpy et adb plus facilement
https://youtu.be/NtxuV1WpRPc?t=548 Comme votre PC n a pas Git de base. Allons l installer 
https://youtu.be/NtxuV1WpRPc?t=564 Next next next sauf pour l editeur de text histoire de pas utiliser vim
https://youtu.be/NtxuV1WpRPc?t=615 Vous avez maintenant un outil de "version control"
https://youtu.be/NtxuV1WpRPc?t=622 Clonons le projet python apk broadcaster sur votre ordinateur.
https://youtu.be/NtxuV1WpRPc?t=632 Cherchons le lien Git Hub sur le bouton vert de GitHub en HTTPS
https://youtu.be/NtxuV1WpRPc?t=638 Utilisons `cmd` dans le dossier de scrcpy pour ouvrir le terminal
https://youtu.be/NtxuV1WpRPc?t=646 Utilisons votre premier `git clone https://github.com/EloiStree/2025_01_12_pyhton_build_run_apk_broadcaster.git toolbox`
https://youtu.be/NtxuV1WpRPc?t=662 Notons les deux executables : `scrcpy.exe` et `adb.exe`
https://youtu.be/NtxuV1WpRPc?t=675 Utiliser des `.py` pour python, allons l installer sur votre ordinateur
https://youtu.be/NtxuV1WpRPc?t=683 Telecharger Python depuis le site web pour Window
https://youtu.be/NtxuV1WpRPc?t=695 Clicker pas trop vite. Utilisez le droit administrateur
https://youtu.be/NtxuV1WpRPc?t=695 Utiliser the Window PATH
https://youtu.be/NtxuV1WpRPc?t=712 Custom install (installer tout les utilisateurs)
https://youtu.be/NtxuV1WpRPc?t=737 Disable la taille des chemains de fichier.
https://youtu.be/NtxuV1WpRPc?t=757 Allons voir un peu ce que je vous offre avec les boites a outils
https://youtu.be/NtxuV1WpRPc?t=767 .bat pour voir la camera 1 du Quest... Qui est un avatar meta xD
https://youtu.be/NtxuV1WpRPc?t=782 .bat pour voir les camera gauche droite 50 51 du Quest
https://youtu.be/NtxuV1WpRPc?t=800 C est quoi la resolution des webcam (1280x1280 max)
https://youtu.be/NtxuV1WpRPc?t=826 Nous ce que l on veut la un oeil avec une resolution plus base
https://youtu.be/NtxuV1WpRPc?t=840 Du coup, ca ressemble a quoi un ligne de commande scrcpy ?
https://youtu.be/NtxuV1WpRPc?t=869 Comment on install Steam  Linq sur le store du coup ?
https://youtu.be/NtxuV1WpRPc?t=903 Steam Linq Scan le reseau local pour trouver vos PC 
https://youtu.be/NtxuV1WpRPc?t=920 Utiliser une Steam Deck pour faire de la VR ?
https://youtu.be/NtxuV1WpRPc?t=929 Pairons le Quest et Steam Linq a votre PC avec Steam VR
https://youtu.be/NtxuV1WpRPc?t=980 "Did you Try to turn it on and off ?"
https://youtu.be/NtxuV1WpRPc?t=990 Votre premier fois dans le Steam Home ;)
https://youtu.be/NtxuV1WpRPc?t=995 Et le purgatoire de Steam 
https://youtu.be/NtxuV1WpRPc?t=1033 C est quoi Alyx ?
https://youtu.be/NtxuV1WpRPc?t=1048 Creeons un petit shortcut vers les .bat de l oeil gauch en resolution minimum
https://youtu.be/NtxuV1WpRPc?t=1058 Allons jeter un coup d oeil au menu de Steam VR et les options disponibles
https://youtu.be/NtxuV1WpRPc?t=1085 Verifions que Steam VR est en OpenXR 
https://youtu.be/NtxuV1WpRPc?t=1102 18 Minutes, allons faire un peu de godot ;)
https://youtu.be/NtxuV1WpRPc?t=1105 Creeons un project HelloSteamVR
https://youtu.be/NtxuV1WpRPc?t=1107 Dans une dossier C:/git/to_git_later/
https://youtu.be/NtxuV1WpRPc?t=1131 pas de `-` car on veut que de l alpha numeric 09Az_
https://youtu.be/NtxuV1WpRPc?t=1143 Window a un probleme de longeur de chemain d access (128-256 char max)
https://youtu.be/NtxuV1WpRPc?t=1187 Nomenclature personne pour ranger les dossiers sur le disque plus facilement
https://youtu.be/NtxuV1WpRPc?t=1193 yyyy_mm_dd_type_nom_project
https://youtu.be/NtxuV1WpRPc?t=1207 laissons les parameters de Godot par defaut (Git Forward+)
https://youtu.be/NtxuV1WpRPc?t=1228 Creeons les bases d un project XR en Godot.
https://youtu.be/NtxuV1WpRPc?t=1231 Creer une scene Node3D
https://youtu.be/NtxuV1WpRPc?t=1254 Enregistrons la scene en .tscn
https://youtu.be/NtxuV1WpRPc?t=1267 Ajoutons un XRNode3D de type XROrigine3D
https://youtu.be/NtxuV1WpRPc?t=1285 C'est quoi une origin , un guardian ?
https://youtu.be/NtxuV1WpRPc?t=1305 Ajoutons une XRCamera3D.
https://youtu.be/NtxuV1WpRPc?t=1310 Godot nous averti que notre projet est pas en XR allons changer cela.
https://youtu.be/NtxuV1WpRPc?t=1312 Proejct > Setting> General > XR > OpenXR > Enable True
https://youtu.be/NtxuV1WpRPc?t=1315 Proejct > Setting> General > XR > Shader > Enable True
https://youtu.be/NtxuV1WpRPc?t=1342 Utilisons Local Floor pour la camera 
https://youtu.be/NtxuV1WpRPc?t=1359 Utilisons Blend Mode > Alpha pour faire de la realiter augmenter plus tard.
https://youtu.be/NtxuV1WpRPc?t=1376 Demandons d utiliser les mains du jouer en XR Hand Tracking
https://youtu.be/NtxuV1WpRPc?t=1381 Et passons un peu ce que c est que le spacial anchor pour le moment.
https://youtu.be/NtxuV1WpRPc?t=1399 Pour faire de l'AR il nous faut un background noir transparent.
https://youtu.be/NtxuV1WpRPc?t=1402 Rendering Environement > Color > RGBA Noir transparent
https://youtu.be/NtxuV1WpRPc?t=1410 Votre premiere color picker Godot 😉
https://youtu.be/NtxuV1WpRPc?t=1443 On verifie que Steam VR tourne que lon est pret a faire play.
https://youtu.be/NtxuV1WpRPc?t=1451 Mais on y vera rien... Deja car on a pas de cube.
https://youtu.be/NtxuV1WpRPc?t=1457 Ajoutons un MeshInstance3D
https://youtu.be/NtxuV1WpRPc?t=1471 Allons dire que ce Mesh est un cube.
https://youtu.be/NtxuV1WpRPc?t=1481 Toujours rien car on a pas de luniere... 
https://youtu.be/NtxuV1WpRPc?t=1489 Mais aussi car l on a pas dit a Godot de lancer les codes de OpenXR
https://youtu.be/NtxuV1WpRPc?t=1512 Ajoutons le DirectionLight3D avant d oublier
https://youtu.be/NtxuV1WpRPc?t=1517 Allons lire le manuel 📕RTFM
https://youtu.be/NtxuV1WpRPc?t=1523 Pas le doc de Godot 3... On est sur Godot 4.6.1
https://youtu.be/NtxuV1WpRPc?t=1544 La documentation officiel de la XR (le tutorial)
https://youtu.be/NtxuV1WpRPc?t=1550 Le code GDScript pour lancer la XR XRServer.find_interface
https://youtu.be/NtxuV1WpRPc?t=1556 Creeons un petit script avec cde code dans notre projet
https://youtu.be/NtxuV1WpRPc?t=1563 Creeons un point vide pour faire exister le script dans la scene
https://youtu.be/NtxuV1WpRPc?t=1585 Comment on fait encore pour deposer un script sur un Node ?
https://youtu.be/NtxuV1WpRPc?t=1593 Au debut du script fait... _ready()
https://youtu.be/NtxuV1WpRPc?t=1610 Alors ca fonction maintenant ?
https://youtu.be/NtxuV1WpRPc?t=1625 Tadaam ;) Un Cube
https://youtu.be/NtxuV1WpRPc?t=1631 Alors, ajoutons peut etre les mains ?
https://youtu.be/NtxuV1WpRPc?t=1636 Ajoutons un XRController3D
https://youtu.be/NtxuV1WpRPc?t=1649 Main gauche, droite et la tete
https://youtu.be/NtxuV1WpRPc?t=1656 On va dire le type d object dans XRNode3D > Tracker
https://youtu.be/NtxuV1WpRPc?t=1660 Sauf que pour voir nos mains, il nous faudrait un petit cube de 2cm
https://youtu.be/NtxuV1WpRPc?t=1660 Comme on en a deux, creeons un scene (prefab pour les devs Unity)
https://youtu.be/NtxuV1WpRPc?t=1681 CTRL + D pour dupliquer en Godot un object
https://youtu.be/NtxuV1WpRPc?t=1721 Changeons le tracker que j ai pas changer plus tot.
https://youtu.be/NtxuV1WpRPc?t=1727 C est quoi les autres trackers disponible ?
https://youtu.be/NtxuV1WpRPc?t=1756 Notons que les XRController3D doivent etre dans XROrigine3D
https://youtu.be/NtxuV1WpRPc?t=1774 Editons notre cube pour lui donner une petit couleur jaune
https://youtu.be/NtxuV1WpRPc?t=1777 Creer un StandardMaterial3D sur MeshInstance3D
https://youtu.be/NtxuV1WpRPc?t=1780 Albedo Color > Jaune
https://youtu.be/NtxuV1WpRPc?t=1790 Retirons les ombres avec Shader Mode: unshaded 
https://youtu.be/NtxuV1WpRPc?t=1827 Allons regarder a ce qu est Godot Xr Tools
https://youtu.be/NtxuV1WpRPc?t=1836 Telechargable depuis GitHub Release...
https://youtu.be/NtxuV1WpRPc?t=1843 Mais pour savoir comment, vaut mieux aller lire le tutorial officiel
https://youtu.be/NtxuV1WpRPc?t=1878 Noter que je ne l ai jamais utiliser. C est justement pour cela que j installer Steam VR sur un de mes PC
https://youtu.be/NtxuV1WpRPc?t=1888 Bon, cets plus simple de l installer depui le "store" AssetLib de Godot
https://youtu.be/NtxuV1WpRPc?t=1897 Cherchons Godot XR Tools 4
https://youtu.be/NtxuV1WpRPc?t=1905 Accepter de telecharger dans le project l'addons
https://youtu.be/NtxuV1WpRPc?t=1937 Et allons considerer ces fichiers comme un plugin
https://youtu.be/NtxuV1WpRPc?t=1942 Project > Setting>Plugins> Godot Xr Tools > On  true
https://youtu.be/NtxuV1WpRPc?t=1961 Notez que Godot est un language interpreter.
https://youtu.be/NtxuV1WpRPc?t=1964 On peut force Godot a charger ses shader avec VRCommonShaderCache
https://youtu.be/NtxuV1WpRPc?t=1989 VR Sickness et chargement de shader en Godot ?
https://youtu.be/NtxuV1WpRPc?t=2001 Alors comme je suis debutant, j ai fuit les bugs 😋 pendant l enregsitrement
https://youtu.be/NtxuV1WpRPc?t=2041 Bon Bah du coup, ou etudier Godot XR Tools ?
https://youtu.be/NtxuV1WpRPc?t=2053 Godot XR Tool Indroduction Part 1 : Install, bouger, tourner, teleporter
https://youtu.be/NtxuV1WpRPc?t=2076 GXR, Part 2: Picking object: Pick, Highligh, Hand position
https://youtu.be/NtxuV1WpRPc?t=2137 GXR, Part 3: Snaper un objet 
https://youtu.be/NtxuV1WpRPc?t=2177 Pour comprendre il faut jouer ;)
https://youtu.be/NtxuV1WpRPc?t=2181 Telechargeons depuis Itchio l apk et la version PC
https://youtu.be/NtxuV1WpRPc?t=2221 Installons l'APK avec Screen Copy et son installeur ADB 
https://youtu.be/NtxuV1WpRPc?t=2255 Drag and drop l'apk sur la fenetre de screen copy
https://youtu.be/NtxuV1WpRPc?t=2273 adb install chemain.apk
https://youtu.be/NtxuV1WpRPc?t=2286 Allons chercher notre application inconnue du Quest store.
https://youtu.be/NtxuV1WpRPc?t=2289 Meta nous cache sous le tapis dans Menu Quest unkown source 
https://youtu.be/NtxuV1WpRPc?t=2314 Chercher Godot XR tool demo
https://youtu.be/NtxuV1WpRPc?t=2331 Hormis les clignotements, ca ressemble a ca
https://youtu.be/NtxuV1WpRPc?t=2352 Lancons la version Steam VR de la demo (avec un authorisation Window)
https://youtu.be/NtxuV1WpRPc?t=2381 Oublier pas de lancer Steam VR 😋
https://youtu.be/NtxuV1WpRPc?t=2398 Attraper des cubes
https://youtu.be/NtxuV1WpRPc?t=2410 Charger un pistolet
https://youtu.be/NtxuV1WpRPc?t=2436 Se teleporter 
https://youtu.be/NtxuV1WpRPc?t=2443 Attraper des objets a distance
https://youtu.be/NtxuV1WpRPc?t=2446 Lancer les objets
https://youtu.be/NtxuV1WpRPc?t=2454 On a un arc a fleche 🏹
https://youtu.be/NtxuV1WpRPc?t=2501 Un meilleur controlle sur Steam VR avec ALVR ?
https://youtu.be/NtxuV1WpRPc?t=2551 Le top du top: Virtual Desktop
https://youtu.be/NtxuV1WpRPc?t=2562 Telegarons le Streamer App
https://youtu.be/NtxuV1WpRPc?t=2578 Virtual Desktop fonction a distance ! 
https://youtu.be/NtxuV1WpRPc?t=2597 Bon faut achter l application 25$ sur le Quest 
https://youtu.be/NtxuV1WpRPc?t=2683 Ajoutons votre nom de compte Meta a Virtual Desktop Streamer
https://youtu.be/NtxuV1WpRPc?t=2709 Lancer le Streamer au demarrage si ca vous interesse
https://youtu.be/NtxuV1WpRPc?t=2726 Selectionnons le OpenXR Runtime specifiquement pour SteamVR
https://youtu.be/NtxuV1WpRPc?t=2760 Installer Virtual Desktop depuis le store
https://youtu.be/NtxuV1WpRPc?t=2791 Le menu et mon ordinateur disponible dans l'app virtual desktop
https://youtu.be/NtxuV1WpRPc?t=2829 Connectons nous sur mon PC ;)
https://youtu.be/NtxuV1WpRPc?t=2835 Never Gonna Give you up, let's you down ...
https://youtu.be/NtxuV1WpRPc?t=2849 Utilisons scrcpy pour prendre une photo du l ecran du casque 📸
https://youtu.be/NtxuV1WpRPc?t=2860 toolbox > take a screenshot . py
https://youtu.be/NtxuV1WpRPc?t=2867 Virtual desktop avec un clavier virtuelle dans mon casque
https://youtu.be/NtxuV1WpRPc?t=2900 Virtual Desktop > Steam VR API > Open XR > Godot
https://youtu.be/NtxuV1WpRPc?t=2942 Fin du tutorial sur Steam VR ( en soit)
https://youtu.be/NtxuV1WpRPc?t=2959 La suite ? Taper Godot VR XR 4.6.1 Guide sur Youtube 😉
https://youtu.be/NtxuV1WpRPc?t=2991 Vous etes toujours la ;)
https://youtu.be/NtxuV1WpRPc?t=2993 Allons telecharger deux trois outils git. En commancant par SourceTree
https://youtu.be/NtxuV1WpRPc?t=3036 Avec mes collegues et les etudiants ont utilise plutot Fork
https://youtu.be/NtxuV1WpRPc?t=3070 Mais comme vous etes debutant... Installons aussi GitHub Desktop
https://youtu.be/NtxuV1WpRPc?t=3087 Alors pour fonctionner Git a besoin du nom et d un email
https://youtu.be/NtxuV1WpRPc?t=3095 Y a pas de verification, cest plus pour les archives et les git blame
https://youtu.be/NtxuV1WpRPc?t=3110 Car git permet le travail en equipe
https://youtu.be/NtxuV1WpRPc?t=3157 C est quoi la difference entre git, github, et github desktop ?
https://youtu.be/NtxuV1WpRPc?t=3178 SignIn avec un compte GitHub via navigateur et se logger avec la double auth
https://youtu.be/NtxuV1WpRPc?t=3221 Le site demande de contact l application pour lui donner les authorizations
https://youtu.be/NtxuV1WpRPc?t=3248 Allons apprendre a creer un repertoire github depuis un projet sur mon PC.
https://youtu.be/NtxuV1WpRPc?t=3261 Create from an existing folder
https://youtu.be/NtxuV1WpRPc?t=3274 Donnons lui un nom (meme que au depart yyyy_mm_dd_type_nom )
https://youtu.be/NtxuV1WpRPc?t=3289 Une petite description et un readme.md
https://youtu.be/NtxuV1WpRPc?t=3313 Ajoutons un git ignore 
https://youtu.be/NtxuV1WpRPc?t=3330 Choisir si il est priver ou publier avant de valider
https://youtu.be/NtxuV1WpRPc?t=3336 Creer ou cloner demande un dosier vide... Deplacons le contenu.
https://youtu.be/NtxuV1WpRPc?t=3353 Affichons les extensions de fichier
https://youtu.be/NtxuV1WpRPc?t=3367 Affichons les fichiers cachers
https://youtu.be/NtxuV1WpRPc?t=3372 On vois notre dossier .git cacher avec vos future sauvegarde.
https://youtu.be/NtxuV1WpRPc?t=3386 Deplacons cela dans le projet
https://youtu.be/NtxuV1WpRPc?t=3396 C est quoi un .gitignore ?
https://youtu.be/NtxuV1WpRPc?t=3401 /dossier/ vs .cfg vs build/
https://youtu.be/NtxuV1WpRPc?t=3422 On dit a GitHub Desktop que l'on a deplacer notre git
https://youtu.be/NtxuV1WpRPc?t=3443 Allons sauver en "stageant" des fichiers dans la prochaine sauvegard.
https://youtu.be/NtxuV1WpRPc?t=3447 Ajoutons un nom a la sauvegarde et sauvons (commit)
https://youtu.be/NtxuV1WpRPc?t=3466 Toujours verifier la taille des fichiers dans le projet avant...
https://youtu.be/NtxuV1WpRPc?t=3473 Allons installer un vieux logiciel WinDirStat
https://youtu.be/NtxuV1WpRPc?t=3536 Scannons notre projet Godot
https://youtu.be/NtxuV1WpRPc?t=3569 Bon bah on est bon pour cette fois-ci... For-shadowing
https://youtu.be/NtxuV1WpRPc?t=3580 Un gros fichier local, sauvable... en ligne.. Aie
https://youtu.be/NtxuV1WpRPc?t=3605 Allons pousser notre repertoire en ligne ;)
https://youtu.be/NtxuV1WpRPc?t=3654 Et... C est en ligne et sauvegarder.
https://youtu.be/NtxuV1WpRPc?t=3682 GitHub permet d editer en ligne. Par example des cours
https://youtu.be/NtxuV1WpRPc?t=3733 Allons voir dans Fork la signification du mot Fetch de git
https://youtu.be/NtxuV1WpRPc?t=3767 Mettons nous a jour sur le projet avec un pull
https://youtu.be/NtxuV1WpRPc?t=3791 Habituions nous a fork en sauvant un modifiaction de fichier.
https://youtu.be/NtxuV1WpRPc?t=3800 Ajoutons (stage) le changement la prochaine sauvegarde
https://youtu.be/NtxuV1WpRPc?t=3806 Commentons la sauvegarde local avec un commit
https://youtu.be/NtxuV1WpRPc?t=3815 Un petit pull pour prendre l habitude de se mettre a jour
https://youtu.be/NtxuV1WpRPc?t=3821 Un petit push pour envoyer la sauvegarde local en ligne
https://youtu.be/NtxuV1WpRPc?t=3840 Ok, GithDesktop et Fork c est chouette mais en ligne de commande ?



https://youtu.be/NtxuV1WpRPc?t=3849 CMD dans window path pour ouvrir le terminal la ou on est
https://youtu.be/NtxuV1WpRPc?t=3861 Utilisons Git Status pour voir ou on en est dans la sauvegarde du projet
https://youtu.be/NtxuV1WpRPc?t=3869 Ajoutons a la sauvegarde les fichiers avec git add .
https://youtu.be/NtxuV1WpRPc?t=3874 Verifions que ca a marcher avec git status
https://youtu.be/NtxuV1WpRPc?t=3878 Git Commit -m pour sauver avec un commentaitre
https://youtu.be/NtxuV1WpRPc?t=3899 Mettons nous a jour au cas ou avec un git pull
https://youtu.be/NtxuV1WpRPc?t=3902 On est a jour un petit git push pour sauver notre avancement en ligne
https://youtu.be/NtxuV1WpRPc?t=3950 Creation un `_Project` ou simplement `_` pour rassembler nos affaire
https://youtu.be/NtxuV1WpRPc?t=3952 Creeons des dossiers: script, scene, assets ...
https://youtu.be/NtxuV1WpRPc?t=3968 Creeons un petit hello world
https://youtu.be/NtxuV1WpRPc?t=3990 C est quoi extends Node et _ready ?
https://youtu.be/NtxuV1WpRPc?t=4000 Le premier Hello World de la video avec print()
https://youtu.be/NtxuV1WpRPc?t=4009 Creeons un Node vide pour "heberger" les script
https://youtu.be/NtxuV1WpRPc?t=4039 L editeur de Godot est bien. Mais vous pouvez en utiliser d autres
https://youtu.be/NtxuV1WpRPc?t=4059 telercharons Visual Studio Code 
https://youtu.be/NtxuV1WpRPc?t=4078 Vous pouvez aller voir pour JetBrains si vous voulez.
https://youtu.be/NtxuV1WpRPc?t=4108 VS est un outils tres puissant, leger et surtout modulaire.
https://youtu.be/NtxuV1WpRPc?t=4141 Ouvrons votre projet
https://youtu.be/NtxuV1WpRPc?t=4164 Ajoutons un module pour Godot dans VS Code
https://youtu.be/NtxuV1WpRPc?t=4204 Donnons a VS Code le chemain de l executabe Godot pour qu il communique
https://youtu.be/NtxuV1WpRPc?t=4257 Tadaaam on a un jolie code de couleur
https://youtu.be/NtxuV1WpRPc?t=4272 Ajoutons un compteur de frame pour le fun 
https://youtu.be/NtxuV1WpRPc?t=4277 @export var nom_variable_membre: type = valeur_par_default
https://youtu.be/NtxuV1WpRPc?t=4315 Incrementer un variable avec += 1 
https://youtu.be/NtxuV1WpRPc?t=4339 Commenter pour la documentation avec ##
https://youtu.be/NtxuV1WpRPc?t=4390 Comment on fait pour faire tourner un Cube ?
https://youtu.be/NtxuV1WpRPc?t=4395 D abord on demande a un moteur de recherche
https://youtu.be/NtxuV1WpRPc?t=4402 On lit deux trois forums
https://youtu.be/NtxuV1WpRPc?t=4429 RTFM, on va lire le manual et le doc
https://youtu.be/NtxuV1WpRPc?t=4454 Godot Doc est tres bien entretenu par la communauter sur GitHub
https://youtu.be/NtxuV1WpRPc?t=4486 Dans les AI il y a les hors ligne avec LM Studio et Hugging Face
https://youtu.be/NtxuV1WpRPc?t=4521 Mais moi, j utilise Copilot payant sur VS Code par faciliter
https://youtu.be/NtxuV1WpRPc?t=4578 Allons installer le module de Copilot
https://youtu.be/NtxuV1WpRPc?t=4623 Demander de laide a copilot CTRL+i Help ou CTRL+SHIT+I pour le Chat
https://youtu.be/NtxuV1WpRPc?t=4632 Ce loger avec votre compte GitHub
https://youtu.be/NtxuV1WpRPc?t=4648 Avec copilot, vous pouvez choisir l AI utiliser par Microsoft pour vous aider.
https://youtu.be/NtxuV1WpRPc?t=4675 Les AI dans visual studio utilise le context envionant
https://youtu.be/NtxuV1WpRPc?t=4708 Ajoutons un @export pour le game designer dans l inspecteur
https://youtu.be/NtxuV1WpRPc?t=4715 Les Ai sont tres bonne a documenter et vous aidez a comprendre
https://youtu.be/NtxuV1WpRPc?t=4727 Copier coller du code sans comprendre.... Pas bien
https://youtu.be/NtxuV1WpRPc?t=4759 Demander a l AI de vous faire des CheatSheet (brouillons de triche
https://youtu.be/NtxuV1WpRPc?t=4790 On a vu git en console et en UI... Vous avez git directement dans VS Code ;)
https://youtu.be/NtxuV1WpRPc?t=4856 Alors  c est bien Steam VR... Mais si vous avez un Quest. Il faut un peu voir ce que Meta propose
https://youtu.be/NtxuV1WpRPc?t=4859 Telechargeons l Oculus Setup ici appelez Meta Horizon Link App
https://youtu.be/NtxuV1WpRPc?t=4892 C est du next next avec un bon gros Giga a telecharger
https://youtu.be/NtxuV1WpRPc?t=4900 Bon pour ce logger il vous faut un compte
https://youtu.be/NtxuV1WpRPc?t=4909 La petite annecdote de Facebook qui se renomme Meta...
https://youtu.be/NtxuV1WpRPc?t=4960 Creeons un compte ensemble pour devenir developper
https://youtu.be/NtxuV1WpRPc?t=5022 Confirmer votre mail via le code envoyer
https://youtu.be/NtxuV1WpRPc?t=5060 Meta essie de vous forcer a utiliser Horizon...
https://youtu.be/NtxuV1WpRPc?t=5087 Toujours authorizer le navigateur a communiquer avec l application meta
https://youtu.be/NtxuV1WpRPc?t=5098 Ajouter un pin d administrateur pour votre casque et les future achats possible
https://youtu.be/NtxuV1WpRPc?t=5121 On a un compte allons le passer en developpeur sur developers portal
https://youtu.be/NtxuV1WpRPc?t=5131 Ajouter un double authentification sur votre compte develper est obligatoire
https://youtu.be/NtxuV1WpRPc?t=5171 Ils vous faut donc telecharger Google Auth et ajouter le QR Code pour la cle de validation
https://youtu.be/NtxuV1WpRPc?t=5259 Maitnenant, il vous faut creer un organisation (team)
https://youtu.be/NtxuV1WpRPc?t=5291 Creeons une application Quest et une application PC VR
https://youtu.be/NtxuV1WpRPc?t=5313 Et vous voila en possition du dashboard de developer sur Meta Store
https://youtu.be/NtxuV1WpRPc?t=5360 Retournons dans logiciel Meta et acceptions les sources inconnue
https://youtu.be/NtxuV1WpRPc?t=5363 Et changons le Open XR par default a Meta Linq
https://youtu.be/NtxuV1WpRPc?t=5396 Petit particulariter, il a vallu aller metre le case en air link pour l ajouter
https://youtu.be/NtxuV1WpRPc?t=5404 Pairons le Air Link a notre ordinateur
https://youtu.be/NtxuV1WpRPc?t=5420 Testons notre connection par Cable 
https://youtu.be/NtxuV1WpRPc?t=5446 Oublier pas de lancer Quest Linq... Et de brancher le cable 😋
https://youtu.be/NtxuV1WpRPc?t=5468 Menu de configuration du casque sur PC 
https://youtu.be/NtxuV1WpRPc?t=5483 Noter que publier une application en priver sur Meta permet de le tester un peu partout
https://youtu.be/NtxuV1WpRPc?t=5494 Allonrs un peu regarder a des applications de production 3D VR
https://youtu.be/NtxuV1WpRPc?t=5496 Telechargons Open Blocks sur votre casque pour du low poly
https://youtu.be/NtxuV1WpRPc?t=5527 Telechargons Open Brush sur votre casque pour des measure
https://youtu.be/NtxuV1WpRPc?t=5551 Telechargons Gravity Sketch pour des formes et prototypage
https://youtu.be/NtxuV1WpRPc?t=5604 Bah c est bon, on peut utiliser Oculus Linq Avec Godot 😉
https://youtu.be/NtxuV1WpRPc?t=5647 Allons nous donner plus de droit en tant que developpeurs
https://youtu.be/NtxuV1WpRPc?t=5659 Le passthrough ( la camera par dessus le fond noir)
https://youtu.be/NtxuV1WpRPc?t=5672 A l espace 3d de la piece si vous utilisez SDK native de meta.
https://youtu.be/NtxuV1WpRPc?t=5702 On est pret pour travailler... Mais ils nous faudrait des outils pour travailler
https://youtu.be/NtxuV1WpRPc?t=5712 Telechargeons Krita 
https://youtu.be/NtxuV1WpRPc?t=5728 Telechargons Blender
https://youtu.be/NtxuV1WpRPc?t=5749 Installons Krita et apprennons a l utiliser
https://youtu.be/NtxuV1WpRPc?t=5769 Shift + Window + S pour prendre une capture d ecran
https://youtu.be/NtxuV1WpRPc?t=5778 Utilisons le site Remove Background pour le fun sous opera GX
https://youtu.be/NtxuV1WpRPc?t=5807 Savoir creer un page Krita pour decouvrier
https://youtu.be/NtxuV1WpRPc?t=5856 Croppons la selection
https://youtu.be/NtxuV1WpRPc?t=5872 Changer la taille de travail en multiple de 2
https://youtu.be/NtxuV1WpRPc?t=5907 On reajsute et on export dans godot/_/assets/2d
https://youtu.be/NtxuV1WpRPc?t=5981 Creer vos propre convention mais essayer de garder de l ordre dans votre projet
https://youtu.be/NtxuV1WpRPc?t=5997 Utilisons un Sprite3D pour afficher notre image
https://youtu.be/NtxuV1WpRPc?t=6043 Creeons un Node Vide pour stocker et ajuste notre sprite histoire d en faire un scene
https://youtu.be/NtxuV1WpRPc?t=6125 Installons Blender 
https://youtu.be/NtxuV1WpRPc?t=6161 On retire la lumiere et la camera pour pas l exporter plus tard
https://youtu.be/NtxuV1WpRPc?t=6166 On ajoute Suzanne, la mascotte de blender
https://youtu.be/NtxuV1WpRPc?t=6184 Colorions les points 3D de lobject avec du Vertex Color
https://youtu.be/NtxuV1WpRPc?t=6261 Allons plutot regarder ce que c est une texture et un depliage UV
https://youtu.be/NtxuV1WpRPc?t=6290 Exprotons notre Suzanne en .GLB
https://youtu.be/NtxuV1WpRPc?t=6383 Ajoutons notre Suzanne dans notre jeu ;) avec instanciate
https://youtu.be/NtxuV1WpRPc?t=6450 Changeons ca taille avec  Transform Scale
https://youtu.be/NtxuV1WpRPc?t=6453 Duplicons notre suzanne avec CTRL+D
https://youtu.be/NtxuV1WpRPc?t=6473 Utilisons Editable Children pour personnaliser notre object
https://youtu.be/NtxuV1WpRPc?t=6503 Comme il me laisse pas l editer la ou j ai besoin rendons la local
https://youtu.be/NtxuV1WpRPc?t=6519 Make Local
https://youtu.be/NtxuV1WpRPc?t=6528 Creeons un material Standard
https://youtu.be/NtxuV1WpRPc?t=6571 Ils nous faudrait sont UV allons le exporter depuis blender
https://youtu.be/NtxuV1WpRPc?t=6577 Passone en Blender Edit Mode
https://youtu.be/NtxuV1WpRPc?t=6614 Tadaaam, votre premier UV sur un object 3D
https://youtu.be/NtxuV1WpRPc?t=6634 Nous on veut le colorier pour le fun
https://youtu.be/NtxuV1WpRPc?t=6720 On recommencer avec notre nouvelle texture
https://youtu.be/NtxuV1WpRPc?t=6747 Comment ca fonction en fait un UV ? Essayons de dessiner la marque de Simba
https://youtu.be/NtxuV1WpRPc?t=6757 Depliage est pas la pour vous rendre la tache facile
https://youtu.be/NtxuV1WpRPc?t=6800 Explorons ce qu est un UV Grid pour mieux comprendre notre object
https://youtu.be/NtxuV1WpRPc?t=6827 "from_the_web" oublier pas de sourcer tout ce que vous utiliser sur votre projet





















 























 



































