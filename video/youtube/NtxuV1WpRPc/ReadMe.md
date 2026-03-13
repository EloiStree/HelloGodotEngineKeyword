Comment créer un projet Godot sur SteamVR et Quest 3 avec GitHub
https://youtu.be/NtxuV1WpRPc


Selling point of this tutorial:
https://youtu.be/NtxuV1WpRPc?t=10235

Vocabulaire:
Steam, SteamVR, ALVR, Godot, Meta Software, Git , Meta Account, Steam Linq, Sketchfab  
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
`#` , `##` , RTFM, Godot Docs    
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
ASMenu :SDK Manager   
Google USB Driver   
Google Web Driver  
Java SDK Path  
Android SDK Path  
20% Fun vs 80% Bloquer   
Syndrome de l imposteur   
arm64 vs x86 et x86_64  
android package name    
XR Mode Regular?     
Webcam permission    
Internet permission    
read/write ,external storage, permission   
Request, HTTP, HTTPS, UDP, Websocket  
Wifi USB Debugging ( voir adb )   
adb devices     
adb -s  
  


Rappel:
LinkedIn, GitHub, Google, Google Auth, Protfolio, Itch.io account, Meta Account,    
GitHub Main Page, GitHub Page, Gravity Sketch , ShareXR*  
WinDirStat et git LFS   
android/   
/[Bb]uild/   
Meta Developer Hub: ADB over Wi-fi    
Meta Developer Hub: Cast Device   

EloiTeaching  
EloiStree Raw  

Termux,Termuc, FDroid   
  
SideQuest PC, SideQuest Android  
~ , ~/storage/shared/document ,~/storage/shared/  
rm -r path/    
git clone    
cd ..  , cd + tab  
zoomer dans termux     
copy past in termux  
 
create project , import project, edit project   
recenter scene,   
blocks color panel  

rappel: status add commit pull push branch checkout switch   
  
Fossify File Manager  
?.tmaterial?  

   
Challenger: faire passer les mains par devant les objest 3D en godot  
Savoir:  
- Detecter un scene recentrer  
- Detecter quand le joueur est dans les menu Quest  
  




































































 








JE SUIS ICI.






https://youtu.be/NtxuV1WpRPc?t=1359 Utilisons Blend Mode > Alpha pour faire de la realiter augmenter plus tard.

Node3D


- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3) Introduction
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=102) On y va ;)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=120) Installer Grave et se connecter avec Gmail.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=141) Se connecter avec une double authentification
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=150) Télécharger Godot
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=164) Créer un dossier C:/exe/godot et y mettre Godot
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=178) Godot est une application portable (pas besoin d'installer)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=182) Godot est une application du web, autoriser à être exécuter sur votre PC sur Windows
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=198) Télécharger Steam pour installer Steam VR
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=222) Steam Guard et la double authentification
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=244) Télécharger Steam VR depuis le store.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=271) C'est quoi Steam Link et où le trouver
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=280) Histoire de pouvoir vous montrer l'écran de mon Quest, allons chercher Scrcpy
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=299) Télécharger et extraire scrcpy dans C:/exe/scrcpy/
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=329) Pour utiliser scrcpy, il vous faut un Android en developer mode (téléphone ou Quest)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=350) Autoriser le PC à communiquer avec votre Quest (USB Debugging) (accepter pour toujours)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=369) Si le message n'apparaît pas, débrancher, rebrancher, redémarrer les casques, changer de câbles...
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=382) Tadaaam, vous voyez l'écran de mon casque ;)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=384) Avec une belle grosse latence car la résolution est de 4000 pixels
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=388) Et l'outil clignote à cause de Meta qui veut afficher et l'écran et le menu
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=408) Essayons de télécharger Meta Quest Developer Hub pour déboguer le casque
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=429) Téléchargez-le, on l'utilisera plus tard. Moi il ne fonctionnait pas/plus avec Windows 10.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=448) Si vous avez le même bug Developer Hub, ça ressemble à ça. Un gros écran gris
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=463) Optionnel : Retirer les firewalls et les sécurités Windows
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=485) Retirons les notifications de droit administrateur pour ne pas accepter toutes les 5 minutes.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=516) Pour continuer, il vous faut un compte GitHub. Je vous invite à en créer un
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=526) Allons chercher une boîte à outils pour utiliser scrcpy et adb plus facilement
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=548) Comme votre PC n'a pas Git de base. Allons l'installer
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=564) Next next next sauf pour l'éditeur de texte histoire de ne pas utiliser vim
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=615) Vous avez maintenant un outil de "version control"
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=622) Clonons le projet Python APK broadcaster sur votre ordinateur.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=632) Cherchons le lien GitHub sur le bouton vert de GitHub en HTTPS
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=638) Utilisons `cmd` dans le dossier de scrcpy pour ouvrir le terminal
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=646) Utilisons votre premier `git clone https://github.com/EloiStree/2025_01_12_pyhton_build_run_apk_broadcaster.git toolbox`
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=662) Notons les deux exécutables : `scrcpy.exe` et `adb.exe`
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=675) Utiliser des `.py` pour Python, allons l'installer sur votre ordinateur
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=683) Télécharger Python depuis le site web pour Windows
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=695) Cliquez pas trop vite. Utilisez le droit administrateur
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=695) Utiliser the Windows PATH
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=712) Custom install (installer pour tous les utilisateurs)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=737) Désactivez la taille des chemins de fichier.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=757) Allons voir un peu ce que je vous offre avec les boîtes à outils
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=767) .bat pour voir la caméra 1 du Quest... Qui est un avatar Meta xD
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=782) .bat pour voir les caméras gauche droite 50 51 du Quest
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=800) C'est quoi la résolution des webcams (1280x1280 max)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=826) Nous ce que l'on veut là un œil avec une résolution plus basse
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=840) Du coup, ça ressemble à quoi une ligne de commande scrcpy ?
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=869) Comment on installe Steam Link sur le store du coup ?
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=903) Steam Link scan le réseau local pour trouver vos PC
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=920) Utiliser une Steam Deck pour faire de la VR ?
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=929) Pairons le Quest et Steam Link à votre PC avec Steam VR
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=980) "Did you Try to turn it on and off ?"
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=990) Votre premier fois dans le Steam Home ;)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=995) Et le purgatoire de Steam
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1033) C'est quoi Alyx ?
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1048) Créons un petit shortcut vers les .bat de l'œil gauche en résolution minimum
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1058) Allons jeter un coup d'œil au menu de Steam VR et les options disponibles
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1085) Vérifions que Steam VR est en OpenXR
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1102) 18 Minutes, allons faire un peu de Godot ;)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1105) Créons un projet HelloSteamVR
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1107) Dans un dossier C:/git/to_git_later/
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1131) pas de `-` car on veut que de l'alphanumérique 09Az_
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1143) Windows a un problème de longueur de chemin d'accès (128-256 char max)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1187) Nomenclature personnelle pour ranger les dossiers sur le disque plus facilement
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1193) yyyy_mm_dd_type_nom_project
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1207) Laissons les paramètres de Godot par défaut (Forward+)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1228) Créons les bases d'un projet XR en Godot.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1231) Créer une scène Node3D
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1254) Enregistrons la scène en .tscn
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1267) Ajoutons un XRNode3D de type XROrigine3D
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1285) C'est quoi une origin, un guardian ?
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1305) Ajoutons une XRCamera3D.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1310) Godot nous avertit que notre projet n'est pas en XR, allons changer cela.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1312) Projet > Settings > General > XR > OpenXR > Enable True
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1315) Projet > Settings > General > XR > Shader > Enable True
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1342) Utilisons Local Floor pour la caméra
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1359) Utilisons Blend Mode > Alpha pour faire de la réalité augmentée plus tard.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1376) Demandons d'utiliser les mains du joueur en XR Hand Tracking
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1381) Et passons un peu ce que c'est que le spatial anchor pour le moment.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1399) Pour faire de l'AR il nous faut un background noir transparent.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1402) Rendering Environment > Color > RGBA Noir transparent
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1410) Votre première color picker Godot 😉
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1443) On vérifie que Steam VR tourne que l'on est prêt à faire play.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1451) Mais on n'y verra rien... Déjà car on n'a pas de cube.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1457) Ajoutons un MeshInstance3D
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1471) Allons dire que ce Mesh est un cube.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1481) Toujours rien car on n'a pas de lumière...
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1489) Mais aussi car l'on n'a pas dit à Godot de lancer les codes de OpenXR
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1512) Ajoutons le DirectionalLight3D avant d'oublier
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1517) Allons lire le manuel 📕RTFM
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1523) Pas le doc de Godot 3... On est sur Godot 4.6.1
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1544) La documentation officielle de la XR (le tutoriel)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1550) Le code GDScript pour lancer la XR XRServer.find_interface
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1556) Créons un petit script avec ce code dans notre projet
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1563) Créons un point vide pour faire exister le script dans la scène
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1585) Comment on fait encore pour déposer un script sur un Node ?
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1593) Au début du script fait... _ready()
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1610) Alors ça fonctionne maintenant ?
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1625) Tadaaam ;) Un Cube
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1631) Alors, ajoutons peut-être les mains ?
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1636) Ajoutons un XRController3D
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1649) Main gauche, droite et la tête
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1656) On va dire le type d'objet dans XRNode3D > Tracker
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1660) Sauf que pour voir nos mains, il nous faudrait un petit cube de 2cm
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1660) Comme on en a deux, créons une scène (prefab pour les devs Unity)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1681) CTRL + D pour dupliquer en Godot un objet
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1721) Changeons le tracker que je n'ai pas changé plus tôt.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1727) C'est quoi les autres trackers disponibles ?
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1756) Notons que les XRController3D doivent être dans XROrigine3D
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1774) Éditons notre cube pour lui donner une petite couleur jaune
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1777) Créer un StandardMaterial3D sur MeshInstance3D
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1780) Albedo Color > Jaune
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1790) Retirons les ombres avec Shader Mode: unshaded
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1827) Allons regarder à ce qu'est Godot XR Tools
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1836) Téléchargeable depuis GitHub Release...
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1843) Mais pour savoir comment, vaut mieux aller lire le tutoriel officiel
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1878) Notez que je ne l'ai jamais utilisé. C'est justement pour cela que j'ai installé Steam VR sur un de mes PC
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1888) Bon, c'est plus simple de l'installer depuis le "store" AssetLib de Godot
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1897) Cherchons Godot XR Tools 4
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1905) Accepter de télécharger dans le projet l'addon
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1937) Et allons considérer ces fichiers comme un plugin
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1942) Projet > Settings > Plugins > Godot XR Tools > On true
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1961) Notez que Godot est un langage interprété.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1964) On peut forcer Godot à charger ses shaders avec VRCommonShaderCache
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=1989) VR Sickness et chargement de shader en Godot ?
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2001) Alors comme je suis débutant, j'ai fui les bugs 😋 pendant l'enregistrement
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2041) Bon bah du coup, où étudier Godot XR Tools ?
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2053) Godot XR Tools Introduction Part 1 : Install, bouger, tourner, téléporter
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2076) GXR, Part 2: Picking object: Pick, Highlight, Hand position
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2137) GXR, Part 3: Snapper un objet
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2177) Pour comprendre il faut jouer ;)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2181) Téléchargeons depuis Itch.io l'APK et la version PC
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2221) Installons l'APK avec Scrcpy et son installateur ADB
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2255) Drag and drop l'APK sur la fenêtre de scrcpy
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2273) adb install chemin.apk
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2286) Allons chercher notre application inconnue du Quest store.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2289) Meta nous cache sous le tapis dans Menu Quest unknown sources
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2314) Chercher Godot XR Tools demo
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2331) Hormis les clignotements, ça ressemble à ça
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2352) Lançons la version Steam VR de la démo (avec une autorisation Windows)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2381) N'oubliez pas de lancer Steam VR 😋
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2398) Attraper des cubes
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2410) Charger un pistolet
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2436) Se téléporter
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2443) Attraper des objets à distance
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2446) Lancer les objets
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2454) On a un arc à flèche 🏹
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2501) Un meilleur contrôle sur Steam VR avec ALVR ?
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2551) Le top du top: Virtual Desktop
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2562) Téléchargeons le Streamer App
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2578) Virtual Desktop fonctionne à distance !
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2597) Bon faut acheter l'application 25$ sur le Quest
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2683) Ajoutons votre nom de compte Meta à Virtual Desktop Streamer
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2709) Lancer le Streamer au démarrage si ça vous intéresse
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2726) Sélectionnons le OpenXR Runtime spécifiquement pour SteamVR
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2760) Installer Virtual Desktop depuis le store
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2791) Le menu et mon ordinateur disponible dans l'app Virtual Desktop
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2829) Connectons-nous sur mon PC ;)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2835) Never Gonna Give you up, let's you down ...
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2849) Utilisons scrcpy pour prendre une photo de l'écran du casque 📸
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2860) toolbox > take a screenshot .py
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2867) Virtual Desktop avec un clavier virtuel dans mon casque
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2900) Virtual Desktop > Steam VR API > Open XR > Godot
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2942) Fin du tutoriel sur Steam VR (en soi)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2959) La suite ? Tapez Godot VR XR 4.6.1 Guide sur YouTube 😉
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2991) Vous êtes toujours là ;)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=2993) Allons télécharger deux trois outils Git. En commençant par SourceTree
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3036) Avec mes collègues et les étudiants, on utilise plutôt Fork
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3070) Mais comme vous êtes débutant... Installons aussi GitHub Desktop
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3087) Alors pour fonctionner, Git a besoin du nom et d'un email
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3095) Y a pas de vérification, c'est plus pour les archives et les git blame
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3110) Car Git permet le travail en équipe
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3157) C'est quoi la différence entre Git, GitHub et GitHub Desktop ?
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3178) Sign in avec un compte GitHub via navigateur et se logger avec la double auth
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3221) Le site demande de contacter l'application pour lui donner les autorisations
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3248) Allons apprendre à créer un répertoire GitHub depuis un projet sur mon PC.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3261) Create from an existing folder
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3274) Donnons-lui un nom (même que au départ yyyy_mm_dd_type_nom )
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3289) Une petite description et un readme.md
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3313) Ajoutons un .gitignore
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3330) Choisir s'il est privé ou public avant de valider
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3336) Créer ou cloner demande un dossier vide... Déplaçons le contenu.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3353) Affichons les extensions de fichier
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3367) Affichons les fichiers cachés
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3372) On voit notre dossier .git caché avec vos futures sauvegardes.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3386) Déplaçons cela dans le projet
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3396) C'est quoi un .gitignore ?
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3401) /dossier/ vs .cfg vs build/
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3422) On dit à GitHub Desktop que l'on a déplacé notre Git
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3443) Allons sauver en "stageant" des fichiers dans la prochaine sauvegarde.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3447) Ajoutons un nom à la sauvegarde et sauvons (commit)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3466) Toujours vérifier la taille des fichiers dans le projet avant...
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3473) Allons installer un vieux logiciel WinDirStat
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3536) Scannons notre projet Godot
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3569) Bon bah on est bon pour cette fois-ci... Foreshadowing
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3580) Un gros fichier local, sauvable... en ligne.. Aïe
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3605) Allons pousser notre répertoire en ligne ;)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3654) Et... C'est en ligne et sauvegardé.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3682) GitHub permet d'éditer en ligne. Par exemple des cours
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3733) Allons voir dans Fork la signification du mot Fetch de Git
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3767) Mettons-nous à jour sur le projet avec un pull
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3791) Habituons-nous à fork en sauvant une modification de fichier.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3800) Ajoutons (stage) le changement à la prochaine sauvegarde
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3806) Commentons la sauvegarde locale avec un commit
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3815) Un petit pull pour prendre l'habitude de se mettre à jour
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3821) Un petit push pour envoyer la sauvegarde locale en ligne
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3840) Ok, GitHub Desktop et Fork c'est chouette mais en ligne de commande ?
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3849) CMD dans Windows Path pour ouvrir le terminal là où on est
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3861) Utilisons Git Status pour voir où on en est dans la sauvegarde du projet
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3869) Ajoutons à la sauvegarde les fichiers avec git add .
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3874) Vérifions que ça a marché avec git status
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3878) Git Commit -m pour sauver avec un commentaire
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3899) Mettons-nous à jour au cas où avec un git pull
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3902) On est à jour, un petit git push pour sauver notre avancement en ligne
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3950) Création un `_Project` ou simplement `_` pour rassembler nos affaires
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3952) Créons des dossiers : script, scène, assets ...
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3968) Créons un petit hello world
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=3990) C'est quoi extends Node et _ready ?
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4000) Le premier Hello World de la vidéo avec print()
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4009) Créons un Node vide pour "héberger" les scripts
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4039) L'éditeur de Godot est bien. Mais vous pouvez en utiliser d'autres
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4059) Téléchargeons Visual Studio Code
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4078) Vous pouvez aller voir pour JetBrains si vous voulez.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4108) VS est un outil très puissant, léger et surtout modulaire.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4141) Ouvrons votre projet
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4164) Ajoutons un module pour Godot dans VS Code
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4204) Donnons à VS Code le chemin de l'exécutable Godot pour qu'il communique
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4257) Tadaaam on a un joli code de couleur
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4272) Ajoutons un compteur de frame pour le fun
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4277) @export var nom_variable_membre: type = valeur_par_default
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4315) Incrémenter une variable avec += 1
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4339) Commenter pour la documentation avec ##
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4390) Comment on fait pour faire tourner un Cube ?
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4395) D'abord on demande à un moteur de recherche
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4402) On lit deux trois forums
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4429) RTFM, on va lire le manuel et le doc
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4454) Godot Doc est très bien entretenu par la communauté sur GitHub
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4486) Dans les IA il y a les hors ligne avec LM Studio et Hugging Face
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4521) Mais moi, j'utilise Copilot payant sur VS Code par facilité
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4578) Allons installer le module de Copilot
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4623) Demander de l'aide à Copilot CTRL+I Help ou CTRL+SHIFT+I pour le Chat
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4632) Se logger avec votre compte GitHub
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4648) Avec Copilot, vous pouvez choisir l'IA utilisée par Microsoft pour vous aider.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4675) Les IA dans Visual Studio utilisent le contexte environnant
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4708) Ajoutons un @export pour le game designer dans l'inspecteur
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4715) Les IA sont très bonnes à documenter et vous aident à comprendre
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4727) Copier-coller du code sans comprendre.... Pas bien
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4759) Demander à l'IA de vous faire des Cheat Sheets (brouillons de triche
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4790) On a vu Git en console et en UI... Vous avez Git directement dans VS Code ;)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4856) Alors c'est bien Steam VR... Mais si vous avez un Quest. Il faut un peu voir ce que Meta propose
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4859) Téléchargeons l'Oculus Setup ici appelé Meta Horizon Link App
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4892) C'est du next next avec un bon gros Giga à télécharger
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4900) Bon pour se logger il vous faut un compte
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4909) La petite anecdote de Facebook qui se renomme Meta...
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=4960) Créons un compte ensemble pour devenir développeur
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5022) Confirmez votre mail via le code envoyé
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5060) Meta essaie de vous forcer à utiliser Horizon...
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5087) Toujours autoriser le navigateur à communiquer avec l'application Meta
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5098) Ajouter un PIN d'administrateur pour votre casque et les futurs achats possibles
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5121) On a un compte, allons le passer en développeur sur developers portal
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5131) Ajouter une double authentification sur votre compte développeur est obligatoire
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5171) Il vous faut donc télécharger Google Auth et ajouter le QR Code pour la clé de validation
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5259) Maintenant, il vous faut créer une organisation (team)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5291) Créons une application Quest et une application PC VR
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5313) Et vous voilà en position du dashboard de developer sur Meta Store
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5360) Retournons dans le logiciel Meta et acceptons les sources inconnues
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5363) Et changeons le OpenXR par défaut à Meta Link
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5396) Petite particularité, il a fallu aller mettre le casque en Air Link pour l'ajouter
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5404) Pairons le Air Link à notre ordinateur
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5420) Testons notre connexion par câble
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5446) N'oubliez pas de lancer Quest Link... Et de brancher le câble 😋
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5468) Menu de configuration du casque sur PC
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5483) Notez que publier une application en privé sur Meta permet de le tester un peu partout
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5494) Allons un peu regarder à des applications de production 3D VR
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5496) Téléchargeons Open Blocks sur votre casque pour du low poly
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5527) Téléchargeons Open Brush sur votre casque pour des mesures
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5551) Téléchargeons Gravity Sketch pour des formes et prototypage
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5604) Bah c'est bon, on peut utiliser Oculus Link avec Godot 😉
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5647) Allons nous donner plus de droits en tant que développeurs
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5659) Le passthrough (la caméra par-dessus le fond noir)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5672) À l'espace 3D de la pièce si vous utilisez SDK native de Meta.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5702) On est prêt pour travailler... Mais il nous faudrait des outils pour travailler
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5712) Téléchargeons Krita
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5728) Téléchargeons Blender
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5749) Installons Krita et apprenons à l'utiliser
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5769) Shift + Windows + S pour prendre une capture d'écran
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5778) Utilisons le site Remove Background pour le fun sous Opera GX
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5807) Savoir créer une page Krita pour découvrir
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5856) Croppons la sélection
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5872) Changer la taille de travail en multiple de 2
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5907) On réajuste et on exporte dans godot/_/assets/2d
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5981) Créez vos propres conventions mais essayez de garder de l'ordre dans votre projet
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=5997) Utilisons un Sprite3D pour afficher notre image
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6043) Créons un Node vide pour stocker et ajuster notre sprite histoire d'en faire une scène
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6125) Installons Blender
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6161) On retire la lumière et la caméra pour ne pas l'exporter plus tard
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6166) On ajoute Suzanne, la mascotte de Blender
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6184) Colorions les points 3D de l'objet avec du Vertex Color
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6261) Allons plutôt regarder ce que c'est une texture et un dépliage UV
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6290) Exportons notre Suzanne en .GLB
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6383) Ajoutons notre Suzanne dans notre jeu ;) avec instanciate
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6450) Changeons sa taille avec Transform Scale
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6453) Dupliquons notre Suzanne avec CTRL+D
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6473) Utilisons Editable Children pour personnaliser notre objet
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6503) Comme il ne me laisse pas l'éditer là où j'ai besoin, rendons-la locale
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6519) Make Local
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6528) Créons un matériau Standard
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6571) Il nous faudrait son UV, allons l'exporter depuis Blender
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6577) Passons en Blender Edit Mode
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6614) Tadaaam, votre premier UV sur un objet 3D
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6634) Nous on veut le colorier pour le fun
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6720) On recommence avec notre nouvelle texture
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6747) Comment ça fonctionne en fait un UV ? Essayons de dessiner la marque de Simba
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6757) Dépliage n'est pas là pour vous rendre la tâche facile
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6800) Explorons ce qu'est un UV Grid pour mieux comprendre notre objet
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6827) "from_the_web" n'oubliez pas de sourcer tout ce que vous utilisez sur votre projet
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6848) Plaçons la UV Grid
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6865) Comment on utilise la UV Grid ?
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6916) Notez que dans Godot 4.7 on aura un outil de dessins 3D ;)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=6970) Importons un GLB depuis Sketchfab pour voir
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7056) Sourcer votre téléchargement
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7068) Vérifier la licence
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7129) Un pivot mal placé...
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7172) L'import GLB de Godot est magnifiquement automatisé
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7179) Ajoutons un émetteur de son dans notre radio 3D
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7251) Il nous faudrait donc un son. Allons chercher Audacity
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7270) Sans MuseHub
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7303) Allons télécharger un bruitage ou une musique
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7357) Retirons le blanc au début du son
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7364) Créons un Fade Out sur la fin du son
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7409) Exportons en OGG
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7433) Ajouter sur AudioStreamPlayer la musique et ajoutons un autoplay.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7458) Pour entrer le son, il nous faut un écouteur sur la caméra AudioListener3D
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7461) Attention, il vous faut celui de Godot XR Tools pour un audio spatialisé
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7532) D'autres logiciels Open source ? Blockbench, GIMP, Inkscape
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7586) Pour votre culture générale et la fin des gamejams, regardons à OBS
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7626) Lançons l'install
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7644) Allons retrouver notre dossier scrcpy installé plus tôt.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7708) Capturer une fenêtre à enregistrer dans OBS
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7814) Cubisme et Laser Dance ;)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7864) Essayons d'exporter notre projet pour le passer à un ami
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7901) Ajoutons Windows et constatons qu'il nous manque quelque chose.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7903) Téléchargeons et installons Export Template
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7955) Bon avant d'exporter... Ajoutons un petit icosphère pour le plaisir d'apprendre à utiliser Blender
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=7971) Exportons un cube avec son UV en croix pour voir
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8026) Créons une icosphère pour voir le prince des formes de Blender
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8081) Ajoutons notre cube à la scène avec une instance classique
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8111) Ajoutons-lui sa texture
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8131) Ajoutons notre icosphère en soleil du jeu
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8148) D'abord fictivement avec unshaded
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8172) Remplaçons le DirectionalLight par un OmniLight3D dans notre soleil
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8237) Allons exporter notre projet pour de vrai
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8244) Créons un build folder.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8291) Tadaaam on a un exe Godot XR 😎
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8369) Essayons de l'exporter pour Android XR...
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8376) Une option de texture à cocher ETC2
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8389) Petit problème, une app Android c'est du Java.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8393) Téléchargeons donc un JDK Java Developer Kit et SDK (Oracle)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8507) On sait parler Java ;) Apprenons à parler Android
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8518) Téléchargeons Android Studio
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8548) En lisant la doc... Il y a une autre version de Java disponible : OpenJDK 17
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8618) Pour Android Studio on n'a pas besoin de l'émulateur
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8665) Android Studio est installé, allons dire bonjour au SDK Manager
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8691) Ajoutons un Google USB driver tant que l'on est là.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8739) Allons dire à Godot où se trouve notre JDK et Android SDK
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8814) Développeur : C'est juste savoir lire de la documentation et appliquer.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8849) Le Quest il est en arm64 bits
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8865) Changeons le nom unique de notre application Android
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8873) pays.company.application
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8909) On veut du OpenXR ou du XR du constructeur ?
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8951) Ajoutons deux trois permissions que j'utilise souvent
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8974) On veut la caméra (webcam)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8980) Internet pour des requests, UDP et WebSocket
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=8993) Read external storage pour aller chercher des fichiers
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9001) Write external storage pour générer des fichiers pour le joueur
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9037) On a une jolie APK pour installer
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9049) Alors dans la théorie on est bon... dans la pratique il me manque une connaissance.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9073) Comme je n'avais plus de batterie. Allons voir comment utiliser ADB par le Wi-Fi
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9131) Allons voir le résultat avec adb devices
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9218) Bon, sauvons un coup notre projet avec GitHub Desktop 😋 Avant d'aller plus profond 😅
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9226) ET BOUM, FORESHADOWING... J'ai des gros fichiers dans mon commit
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9272) D'ailleurs j'avais mal fait mon .gitignore avec /Android/ présent dans le projet
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9345) On push sans nos gros fichiers ;)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9381) VOUS N'ÊTES PAS PRÊT 🗡️🔪... allons travailler dans le casque directement
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9403) J'ai changé de PC, allons voir Meta Developer Hub
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9438) Allons utiliser ADB over Wi-Fi
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9463) Castons le casque ;)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9511) Travaillons en XR 😎
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9548) Lançons Termux (Installation dans une autre vidéo)
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9563) Allez sur EloiTeaching pour trouver les vidéos d'installation de Termux
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9619) Allons dans Documents
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9685) Clonons le projet sur le casque dans Documents
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9721) un petit cd pour rentrer dans le projet et status pour check
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9761) Installer Godot depuis le store puis importons le projet
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9796) Tadaaam, notre projet dans le casque
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9857) Pincher rapidement pour sortir du jeu
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9863) Laisser enfoncé pour recentrer la scène
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9901) Travaillez en live entre l'éditeur et le jeu 😃😍
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=9950) Comment on sauve nos changements en Termux dans le Quest ?
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=10050) Allons voir le résultat sur PC 😉
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=10096) Allons on le refait pour voir de PC à Quest
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=10166) Note: Fermer et relancer Godot pour le forcer à recharger les fichiers
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=10271) Tadaaam on a chargé depuis le PC un objet à voir en XR
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=10300) Alors c'est fun d'importer... Mais ne pourrait-on pas créer sur le Quest 😁
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=10307) Allons dessiner et exporter un sketch de Open Brush
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=10368) Comment on l'exporte notre brush ?
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=10450) Allons créer des œuvres d'arts en low poly avec Blocks
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=10561) Comment sauver et exporter Blocks ?
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=10598) Allons récupérer les fichiers à partir de F-Droid
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=10638) Ouvrons Fossify File Manager pour déplacer nos fichiers
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=10679) Bougeons notre création Blocks dans Godot
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=10772) Blocks crée des OBJs, il nous faut donc un MeshInstance3D
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=10844) Bougeons notre création Open Brush
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=10902) C'est un GLB, ça s'importe facilement avec une instance
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=10962) Allons un peu voir Gravity Sketch ;) C'est fou
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=11095) Exportons notre création
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=11104) Mais pour ça il nous faut un compte
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=11122) En attendant de créer le compte allons peindre 🖼️🖌️
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=11124) Ouvrons VR Paint
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=11284) Exportons notre tableau en format .png
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=11320) Déplaçons-le dans Godot en Sprite3D
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=11473) Sauvons tout cela 😋 vous connaissez la routine maintenant.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=11534) Bon bah du coup, comment on va chercher notre Gravity Sketch si on a un compte
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=11613) C'est un Zip... Mais par chance Fossify est un dézippeur
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=11677) On l'a exporté en .CM... Ajustons dans Godot.
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=11759) Notre objet est composé de 3 matériaux... Créez un commun
- [ ] [🎥](https://youtu.be/NtxuV1WpRPc?t=11885) Je n'avais pas pu vous montrer Virtual Desktop. Une petite visite avant de stopper ?



 














-----------------------





00:00:03 Introduction
00:01:42 On y va ;)
00:02:00 Installer Grave et se connecter avec Gmail.
00:02:21 Se connecter avec une double authentification
00:02:30 Télécharger Godot
00:02:44 Créer un dossier C:/exe/godot et y mettre Godot
00:02:58 Godot est une application portable (pas besoin d'installer)
00:03:02 Godot est une application du web, autoriser à être exécuter sur votre PC sur Windows
00:03:18 Télécharger Steam pour installer Steam VR
00:03:42 Steam Guard et la double authentification
00:04:04 Télécharger Steam VR depuis le store.
00:04:31 C'est quoi Steam Link et où le trouver
00:04:40 Histoire de pouvoir vous montrer l'écran de mon Quest, allons chercher Scrcpy
00:04:59 Télécharger et extraire scrcpy dans C:/exe/scrcpy/
00:05:29 Pour utiliser scrcpy, il vous faut un Android en developer mode (téléphone ou Quest)
00:05:50 Autoriser le PC à communiquer avec votre Quest (USB Debugging) (accepter pour toujours)
00:06:09 Si le message n'apparaît pas, débrancher, rebrancher, redémarrer les casques, changer de câbles...
00:06:22 Tadaaam, vous voyez l'écran de mon casque ;)
00:06:24 Avec une belle grosse latence car la résolution est de 4000 pixels
00:06:28 Et l'outil clignote à cause de Meta qui veut afficher et l'écran et le menu
00:06:48 Essayons de télécharger Meta Quest Developer Hub pour déboguer le casque
00:07:09 Téléchargez-le, on l'utilisera plus tard. Moi il ne fonctionnait pas/plus avec Windows 10.
00:07:28 Si vous avez le même bug Developer Hub, ça ressemble à ça. Un gros écran gris
00:07:43 Optionnel : Retirer les firewalls et les sécurités Windows
00:08:05 Retirons les notifications de droit administrateur pour ne pas accepter toutes les 5 minutes.
00:08:36 Pour continuer, il vous faut un compte GitHub. Je vous invite à en créer un
00:08:46 Allons chercher une boîte à outils pour utiliser scrcpy et adb plus facilement
00:09:08 Comme votre PC n'a pas Git de base. Allons l'installer
00:09:24 Next next next sauf pour l'éditeur de texte histoire de ne pas utiliser vim
00:10:15 Vous avez maintenant un outil de "version control"
00:10:22 Clonons le projet Python APK broadcaster sur votre ordinateur.
00:10:32 Cherchons le lien GitHub sur le bouton vert de GitHub en HTTPS
00:10:38 Utilisons `cmd` dans le dossier de scrcpy pour ouvrir le terminal
00:10:46 Utilisons votre premier `git clone https://github.com/EloiStree/2025_01_12_pyhton_build_run_apk_broadcaster.git toolbox`
00:11:02 Notons les deux exécutables : `scrcpy.exe` et `adb.exe`
00:11:15 Utiliser des `.py` pour Python, allons l'installer sur votre ordinateur
00:11:23 Télécharger Python depuis le site web pour Windows
00:11:35 Cliquez pas trop vite. Utilisez le droit administrateur
00:11:35 Utiliser the Windows PATH
00:11:52 Custom install (installer pour tous les utilisateurs)
00:12:17 Désactivez la taille des chemins de fichier.
00:12:37 Allons voir un peu ce que je vous offre avec les boîtes à outils
00:12:47 .bat pour voir la caméra 1 du Quest... Qui est un avatar Meta xD
00:13:02 .bat pour voir les caméras gauche droite 50 51 du Quest
00:13:20 C'est quoi la résolution des webcams (1280x1280 max)
00:13:46 Nous ce que l'on veut là un œil avec une résolution plus basse
00:14:00 Du coup, ça ressemble à quoi une ligne de commande scrcpy ?
00:14:29 Comment on installe Steam Link sur le store du coup ?
00:15:03 Steam Link scan le réseau local pour trouver vos PC
00:15:20 Utiliser une Steam Deck pour faire de la VR ?
00:15:29 Pairons le Quest et Steam Link à votre PC avec Steam VR
00:16:20 "Did you Try to turn it on and off ?"
00:16:30 Votre premier fois dans le Steam Home ;)
00:16:35 Et le purgatoire de Steam
00:17:13 C'est quoi Alyx ?
00:17:28 Créons un petit shortcut vers les .bat de l'œil gauche en résolution minimum
00:17:38 Allons jeter un coup d'œil au menu de Steam VR et les options disponibles
00:18:05 Vérifions que Steam VR est en OpenXR
00:18:22 18 Minutes, allons faire un peu de Godot ;)
00:18:25 Créons un projet HelloSteamVR
00:18:27 Dans un dossier C:/git/to_git_later/
00:18:51 pas de `-` car on veut que de l'alphanumérique 09Az_
00:19:03 Windows a un problème de longueur de chemin d'accès (128-256 char max)
00:19:47 Nomenclature personnelle pour ranger les dossiers sur le disque plus facilement
00:19:53 yyyy_mm_dd_type_nom_project
00:20:07 Laissons les paramètres de Godot par défaut (Forward+)
00:20:28 Créons les bases d'un projet XR en Godot.
00:20:31 Créer une scène Node3D
00:20:54 Enregistrons la scène en .tscn
00:21:07 Ajoutons un XRNode3D de type XROrigine3D
00:21:25 C'est quoi une origin, un guardian ?
00:21:45 Ajoutons une XRCamera3D.
00:21:50 Godot nous avertit que notre projet n'est pas en XR, allons changer cela.
00:21:52 Projet > Settings > General > XR > OpenXR > Enable True
00:21:55 Projet > Settings > General > XR > Shader > Enable True
00:22:22 Utilisons Local Floor pour la caméra
00:22:39 Utilisons Blend Mode > Alpha pour faire de la réalité augmentée plus tard.
00:22:56 Demandons d'utiliser les mains du joueur en XR Hand Tracking
00:23:01 Et passons un peu ce que c'est que le spatial anchor pour le moment.
00:23:19 Pour faire de l'AR il nous faut un background noir transparent.
00:23:22 Rendering Environment > Color > RGBA Noir transparent
00:23:30 Votre première color picker Godot 😉
00:24:03 On vérifie que Steam VR tourne que l'on est prêt à faire play.
00:24:11 Mais on n'y verra rien... Déjà car on n'a pas de cube.
00:24:17 Ajoutons un MeshInstance3D
00:24:31 Allons dire que ce Mesh est un cube.
00:24:41 Toujours rien car on n'a pas de lumière...
00:24:49 Mais aussi car l'on n'a pas dit à Godot de lancer les codes de OpenXR
00:25:12 Ajoutons le DirectionalLight3D avant d'oublier
00:25:17 Allons lire le manuel 📕RTFM
00:25:23 Pas le doc de Godot 3... On est sur Godot 4.6.1
00:25:44 La documentation officielle de la XR (le tutoriel)
00:25:50 Le code GDScript pour lancer la XR XRServer.find_interface
00:25:56 Créons un petit script avec ce code dans notre projet
00:26:03 Créons un point vide pour faire exister le script dans la scène
00:26:25 Comment on fait encore pour déposer un script sur un Node ?
00:26:33 Au début du script fait... _ready()
00:26:50 Alors ça fonctionne maintenant ?
00:27:05 Tadaaam ;) Un Cube
00:27:11 Alors, ajoutons peut-être les mains ?
00:27:16 Ajoutons un XRController3D
00:27:29 Main gauche, droite et la tête
00:27:36 On va dire le type d'objet dans XRNode3D > Tracker
00:27:40 Sauf que pour voir nos mains, il nous faudrait un petit cube de 2cm
00:27:40 Comme on en a deux, créons une scène (prefab pour les devs Unity)
00:28:01 CTRL + D pour dupliquer en Godot un objet
00:28:41 Changeons le tracker que je n'ai pas changé plus tôt.
00:28:47 C'est quoi les autres trackers disponibles ?
00:29:16 Notons que les XRController3D doivent être dans XROrigine3D
00:29:34 Éditons notre cube pour lui donner une petite couleur jaune
00:29:37 Créer un StandardMaterial3D sur MeshInstance3D
00:29:40 Albedo Color > Jaune
00:29:50 Retirons les ombres avec Shader Mode: unshaded
00:30:27 Allons regarder à ce qu'est Godot XR Tools
00:30:36 Téléchargeable depuis GitHub Release...
00:30:43 Mais pour savoir comment, vaut mieux aller lire le tutoriel officiel
00:31:18 Notez que je ne l'ai jamais utilisé. C'est justement pour cela que j'ai installé Steam VR sur un de mes PC
00:31:28 Bon, c'est plus simple de l'installer depuis le "store" AssetLib de Godot
00:31:37 Cherchons Godot XR Tools 4
00:31:45 Accepter de télécharger dans le projet l'addon
00:32:17 Et allons considérer ces fichiers comme un plugin
00:32:22 Projet > Settings > Plugins > Godot XR Tools > On true
00:32:41 Notez que Godot est un langage interprété.
00:32:44 On peut forcer Godot à charger ses shaders avec VRCommonShaderCache
00:33:09 VR Sickness et chargement de shader en Godot ?
00:33:21 Alors comme je suis débutant, j'ai fui les bugs 😋 pendant l'enregistrement
00:34:01 Bon bah du coup, où étudier Godot XR Tools ?
00:34:13 Godot XR Tools Introduction Part 1 : Install, bouger, tourner, téléporter
00:34:36 GXR, Part 2: Picking object: Pick, Highlight, Hand position
00:35:37 GXR, Part 3: Snapper un objet
00:36:17 Pour comprendre il faut jouer ;)
00:36:21 Téléchargeons depuis Itch.io l'APK et la version PC
00:37:01 Installons l'APK avec Scrcpy et son installateur ADB
00:37:35 Drag and drop l'APK sur la fenêtre de scrcpy
00:37:53 adb install chemin.apk
00:38:06 Allons chercher notre application inconnue du Quest store.
00:38:09 Meta nous cache sous le tapis dans Menu Quest unknown sources
00:38:34 Chercher Godot XR Tools demo
00:38:51 Hormis les clignotements, ça ressemble à ça
00:39:12 Lançons la version Steam VR de la démo (avec une autorisation Windows)
00:39:41 N'oubliez pas de lancer Steam VR 😋
00:39:58 Attraper des cubes
00:40:10 Charger un pistolet
00:40:36 Se téléporter
00:40:43 Attraper des objets à distance
00:40:46 Lancer les objets
00:40:54 On a un arc à flèche 🏹
00:41:41 Un meilleur contrôle sur Steam VR avec ALVR ?
00:42:31 Le top du top: Virtual Desktop
00:42:42 Téléchargeons le Streamer App
00:42:58 Virtual Desktop fonctionne à distance !
00:43:17 Bon faut acheter l'application 25$ sur le Quest
00:44:43 Ajoutons votre nom de compte Meta à Virtual Desktop Streamer
00:45:09 Lancer le Streamer au démarrage si ça vous intéresse
00:45:26 Sélectionnons le OpenXR Runtime spécifiquement pour SteamVR
00:46:00 Installer Virtual Desktop depuis le store
00:46:31 Le menu et mon ordinateur disponible dans l'app Virtual Desktop
00:47:09 Connectons-nous sur mon PC ;)
00:47:15 Never Gonna Give you up, let's you down ...
00:47:29 Utilisons scrcpy pour prendre une photo de l'écran du casque 📸
00:47:40 toolbox > take a screenshot .py
00:47:47 Virtual Desktop avec un clavier virtuel dans mon casque
00:48:20 Virtual Desktop > Steam VR API > Open XR > Godot
00:49:02 Fin du tutoriel sur Steam VR (en soi)
00:49:19 La suite ? Tapez Godot VR XR 4.6.1 Guide sur YouTube 😉
00:49:51 Vous êtes toujours là ;)
00:49:53 Allons télécharger deux trois outils Git. En commençant par SourceTree
00:50:36 Avec mes collègues et les étudiants, on utilise plutôt Fork
00:51:10 Mais comme vous êtes débutant... Installons aussi GitHub Desktop
00:51:27 Alors pour fonctionner, Git a besoin du nom et d'un email
00:51:35 Y a pas de vérification, c'est plus pour les archives et les git blame
00:51:50 Car Git permet le travail en équipe
00:52:37 C'est quoi la différence entre Git, GitHub et GitHub Desktop ?
00:52:58 Sign in avec un compte GitHub via navigateur et se logger avec la double auth
00:53:41 Le site demande de contacter l'application pour lui donner les autorisations
00:54:08 Allons apprendre à créer un répertoire GitHub depuis un projet sur mon PC.
00:54:21 Create from an existing folder
00:54:34 Donnons-lui un nom (même que au départ yyyy_mm_dd_type_nom )
00:54:49 Une petite description et un readme.md
00:55:13 Ajoutons un .gitignore
00:55:30 Choisir s'il est privé ou public avant de valider
00:55:36 Créer ou cloner demande un dossier vide... Déplaçons le contenu.
00:55:53 Affichons les extensions de fichier
00:56:07 Affichons les fichiers cachés
00:56:12 On voit notre dossier .git caché avec vos futures sauvegardes.
00:56:26 Déplaçons cela dans le projet
00:56:36 C'est quoi un .gitignore ?
00:56:41 /dossier/ vs .cfg vs build/
00:57:02 On dit à GitHub Desktop que l'on a déplacé notre Git
00:57:23 Allons sauver en "stageant" des fichiers dans la prochaine sauvegarde.
00:57:27 Ajoutons un nom à la sauvegarde et sauvons (commit)
00:57:46 Toujours vérifier la taille des fichiers dans le projet avant...
00:57:53 Allons installer un vieux logiciel WinDirStat
00:58:56 Scannons notre projet Godot
00:59:29 Bon bah on est bon pour cette fois-ci... Foreshadowing
00:59:40 Un gros fichier local, sauvable... en ligne.. Aïe
01:00:05 Allons pousser notre répertoire en ligne ;)
01:00:54 Et... C'est en ligne et sauvegardé.
01:01:22 GitHub permet d'éditer en ligne. Par exemple des cours
01:02:13 Allons voir dans Fork la signification du mot Fetch de Git
01:02:47 Mettons-nous à jour sur le projet avec un pull
01:03:11 Habituons-nous à fork en sauvant une modification de fichier.
01:03:20 Ajoutons (stage) le changement à la prochaine sauvegarde
01:03:26 Commentons la sauvegarde locale avec un commit
01:03:35 Un petit pull pour prendre l'habitude de se mettre à jour
01:03:41 Un petit push pour envoyer la sauvegarde locale en ligne
01:04:00 Ok, GitHub Desktop et Fork c'est chouette mais en ligne de commande ?
01:04:09 CMD dans Windows Path pour ouvrir le terminal là où on est
01:04:21 Utilisons Git Status pour voir où on en est dans la sauvegarde du projet
01:04:29 Ajoutons à la sauvegarde les fichiers avec git add .
01:04:34 Vérifions que ça a marché avec git status
01:04:38 Git Commit -m pour sauver avec un commentaire
01:04:59 Mettons-nous à jour au cas où avec un git pull
01:05:02 On est à jour, un petit git push pour sauver notre avancement en ligne
01:05:50 Création un `_Project` ou simplement `_` pour rassembler nos affaires
01:05:52 Créons des dossiers : script, scène, assets ...
01:06:08 Créons un petit hello world
01:06:30 C'est quoi extends Node et *ready ?
01:06:40 Le premier Hello World de la vidéo avec print()
01:06:49 Créons un Node vide pour "héberger" les scripts
01:07:19 L'éditeur de Godot est bien. Mais vous pouvez en utiliser d'autres
01:07:39 Téléchargeons Visual Studio Code
01:07:58 Vous pouvez aller voir pour JetBrains si vous voulez.
01:08:28 VS est un outil très puissant, léger et surtout modulaire.
01:09:01 Ouvrons votre projet
01:09:24 Ajoutons un module pour Godot dans VS Code
01:10:04 Donnons à VS Code le chemin de l'exécutable Godot pour qu'il communique
01:10:57 Tadaaam on a un joli code de couleur
01:11:12 Ajoutons un compteur de frame pour le fun
01:11:17 @export var nom_variable_membre: type = valeur_par_default
01:11:55 Incrémenter une variable avec += 1
01:12:19 Commenter pour la documentation avec ##
01:13:10 Comment on fait pour faire tourner un Cube ?
01:13:15 D'abord on demande à un moteur de recherche
01:13:22 On lit deux trois forums
01:13:49 RTFM, on va lire le manuel et le doc
01:14:14 Godot Doc est très bien entretenu par la communauté sur GitHub
01:14:46 Dans les IA il y a les hors ligne avec LM Studio et Hugging Face
01:15:21 Mais moi, j'utilise Copilot payant sur VS Code par facilité
01:16:18 Allons installer le module de Copilot
01:16:63 Demander de l'aide à Copilot CTRL+I Help ou CTRL+SHIFT+I pour le Chat
01:17:12 Se logger avec votre compte GitHub
01:17:28 Avec Copilot, vous pouvez choisir l'IA utilisée par Microsoft pour vous aider.
01:17:55 Les IA dans Visual Studio utilisent le contexte environnant
01:18:28 Ajoutons un @export pour le game designer dans l'inspecteur
01:18:35 Les IA sont très bonnes à documenter et vous aident à comprendre
01:18:47 Copier-coller du code sans comprendre.... Pas bien
01:19:19 Demander à l'IA de vous faire des Cheat Sheets (brouillons de triche
01:19:50 On a vu Git en console et en UI... Vous avez Git directement dans VS Code ;)
01:20:56 Alors c'est bien Steam VR... Mais si vous avez un Quest. Il faut un peu voir ce que Meta propose
01:20:59 Téléchargeons l'Oculus Setup ici appelé Meta Horizon Link App
01:21:32 C'est du next next avec un bon gros Giga à télécharger
01:21:40 Bon pour se logger il vous faut un compte
01:21:49 La petite anecdote de Facebook qui se renomme Meta...
01:22:40 Créons un compte ensemble pour devenir développeur
01:23:42 Confirmez votre mail via le code envoyé
01:24:20 Meta essaie de vous forcer à utiliser Horizon...
01:24:47 Toujours autoriser le navigateur à communiquer avec l'application Meta
01:24:58 Ajouter un PIN d'administrateur pour votre casque et les futurs achats possibles
01:25:21 On a un compte, allons le passer en développeur sur developers portal
01:25:31 Ajouter une double authentification sur votre compte développeur est obligatoire
01:26:11 Il vous faut donc télécharger Google Auth et ajouter le QR Code pour la clé de validation
01:27:39 Maintenant, il vous faut créer une organisation (team)
01:28:11 Créons une application Quest et une application PC VR
01:28:33 Et vous voilà en position du dashboard de developer sur Meta Store
01:29:20 Retournons dans le logiciel Meta et acceptons les sources inconnues
01:29:23 Et changeons le OpenXR par défaut à Meta Link
01:29:56 Petite particularité, il a fallu aller mettre le casque en Air Link pour l'ajouter
01:30:04 Pairons le Air Link à notre ordinateur
01:30:20 Testons notre connexion par câble
01:30:46 N'oubliez pas de lancer Quest Link... Et de brancher le câble 😋
01:31:08 Menu de configuration du casque sur PC
01:31:23 Notez que publier une application en privé sur Meta permet de le tester un peu partout
01:31:34 Allons un peu regarder à des applications de production 3D VR
01:31:36 Téléchargeons Open Blocks sur votre casque pour du low poly
01:32:07 Téléchargeons Open Brush sur votre casque pour des mesures
01:32:31 Téléchargeons Gravity Sketch pour des formes et prototypage
01:33:24 Bah c'est bon, on peut utiliser Oculus Link avec Godot 😉
01:34:07 Allons nous donner plus de droits en tant que développeurs
01:34:19 Le passthrough (la caméra par-dessus le fond noir)
01:34:32 À l'espace 3D de la pièce si vous utilisez SDK native de Meta.
01:35:02 On est prêt pour travailler... Mais il nous faudrait des outils pour travailler
01:35:12 Téléchargeons Krita
01:35:28 Téléchargeons Blender
01:35:49 Installons Krita et apprenons à l'utiliser
01:36:09 Shift + Windows + S pour prendre une capture d'écran
01:36:18 Utilisons le site Remove Background pour le fun sous Opera GX
01:36:47 Savoir créer une page Krita pour découvrir
01:37:36 Croppons la sélection
01:37:52 Changer la taille de travail en multiple de 2
01:38:27 On réajuste et on exporte dans godot/*/assets/2d
01:39:41 Créez vos propres conventions mais essayez de garder de l'ordre dans votre projet
01:39:57 Utilisons un Sprite3D pour afficher notre image
01:40:43 Créons un Node vide pour stocker et ajuster notre sprite histoire d'en faire une scène
01:42:05 Installons Blender
01:42:41 On retire la lumière et la caméra pour ne pas l'exporter plus tard
01:42:46 On ajoute Suzanne, la mascotte de Blender
01:43:04 Colorions les points 3D de l'objet avec du Vertex Color
01:44:21 Allons plutôt regarder ce que c'est une texture et un dépliage UV
01:44:50 Exportons notre Suzanne en .GLB
01:46:23 Ajoutons notre Suzanne dans notre jeu ;) avec instanciate
01:47:30 Changeons sa taille avec Transform Scale
01:47:33 Dupliquons notre Suzanne avec CTRL+D
01:47:53 Utilisons Editable Children pour personnaliser notre objet
01:48:23 Comme il ne me laisse pas l'éditer là où j'ai besoin, rendons-la locale
01:48:39 Make Local
01:48:48 Créons un matériau Standard
01:49:31 Il nous faudrait son UV, allons l'exporter depuis Blender
01:49:37 Passons en Blender Edit Mode
01:50:14 Tadaaam, votre premier UV sur un objet 3D
01:50:34 Nous on veut le colorier pour le fun
01:52:00 On recommence avec notre nouvelle texture
01:52:27 Comment ça fonctionne en fait un UV ? Essayons de dessiner la marque de Simba
01:52:37 Dépliage n'est pas là pour vous rendre la tâche facile
01:53:20 Explorons ce qu'est un UV Grid pour mieux comprendre notre objet
01:53:47 "from_the_web" n'oubliez pas de sourcer tout ce que vous utilisez sur votre projet
01:54:08 Plaçons la UV Grid
01:54:25 Comment on utilise la UV Grid ?
01:55:16 Notez que dans Godot 4.7 on aura un outil de dessins 3D ;)
01:56:10 Importons un GLB depuis Sketchfab
01:57:36 Sourcer votre téléchargement
01:57:48 Vérifier la licence
01:58:49 Un pivot mal placé...
01:59:32 L'import GLB de Godot est magnifiquement automatisé
01:59:39 Ajoutons un émetteur de son dans notre radio 3D
02:00:51 Il nous faudrait donc un son. Allons chercher Audacity
02:01:10 Sans MuseHub
02:01:43 Allons télécharger un bruitage ou une musique
02:02:37 Retirons le blanc au début du son
02:02:44 Créons un Fade Out sur la fin du son
02:03:29 Exportons en OGG
02:03:53 Ajouter sur AudioStreamPlayer la musique et ajoutons un autoplay.
02:04:18 Pour entrer le son, il nous faut un écouteur sur la caméra AudioListener3D
02:04:21 Attention, il vous faut celui de Godot XR Tools pour un audio spatialisé
02:05:32 D'autres logiciels Open source ? Blockbench, GIMP, Inkscape
02:06:26 Pour votre culture générale et la fin des gamejams, regardons à OBS
02:07:06 Lançons l'install
02:07:24 Allons retrouver notre dossier scrcpy installé plus tôt.
02:08:28 Capturer une fenêtre à enregistrer dans OBS
02:10:14 Cubisme et Laser Dance ;)
02:11:04 Essayons d'exporter notre projet pour le passer à un ami
02:11:41 Ajoutons Windows et constatons qu'il nous manque quelque chose.
02:11:43 Téléchargeons et installons Export Template
02:12:35 Bon avant d'exporter... Ajoutons un petit icosphère pour le plaisir d'apprendre à utiliser Blender
02:12:51 Exportons un cube avec son UV en croix pour voir
02:13:46 Créons une icosphère pour voir le prince des formes de Blender
02:14:41 Ajoutons notre cube à la scène avec une instance classique
02:15:11 Ajoutons-lui sa texture
02:15:31 Ajoutons notre icosphère en soleil du jeu
02:15:48 D'abord fictivement avec unshaded
02:16:12 Remplaçons le DirectionalLight par un OmniLight3D dans notre soleil
02:17:17 Allons exporter notre projet pour de vrai
02:17:24 Créons un build folder.
02:18:11 Tadaaam on a un exe Godot XR 😎
02:19:29 Essayons de l'exporter pour Android XR...
02:19:36 Une option de texture à cocher ETC2
02:19:49 Petit problème, une app Android c'est du Java.
02:19:53 Téléchargeons donc un JDK Java Developer Kit et SDK (Oracle)
02:21:47 On sait parler Java ;) Apprenons à parler Android
02:21:58 Téléchargeons Android Studio
02:22:28 En lisant la doc... Il y a une autre version de Java disponible : OpenJDK 17
02:23:38 Pour Android Studio on n'a pas besoin de l'émulateur
02:24:25 Android Studio est installé, allons dire bonjour au SDK Manager
02:24:51 Ajoutons un Google USB driver tant que l'on est là.
02:25:39 Allons dire à Godot où se trouve notre JDK et Android SDK
02:26:54 Développeur : C'est juste savoir lire de la documentation et appliquer.
02:27:29 Le Quest il est en arm64 bits
02:27:45 Changeons le nom unique de notre application Android
02:27:53 pays.company.application
02:28:29 On veut du OpenXR ou du XR du constructeur ?
02:29:11 Ajoutons deux trois permissions que j'utilise souvent
02:29:34 On veut la caméra (webcam)
02:29:40 Internet pour des requests, UDP et WebSocket
02:29:53 Read external storage pour aller chercher des fichiers
02:30:01 Write external storage pour générer des fichiers pour le joueur
02:30:37 On a une jolie APK pour installer
02:30:49 Alors dans la théorie on est bon... dans la pratique il me manque une connaissance.
02:31:13 Comme je n'avais plus de batterie. Allons voir comment utiliser ADB par le Wi-Fi
02:32:11 Allons voir le résultat avec adb devices
02:33:38 Bon, sauvons un coup notre projet avec GitHub Desktop 😋 Avant d'aller plus profond 😅
02:33:46 ET BOUM, FORESHADOWING... J'ai des gros fichiers dans mon commit
02:34:32 D'ailleurs j'avais mal fait mon .gitignore avec /Android/ présent dans le projet
02:35:45 On push sans nos gros fichiers ;)
02:36:21 VOUS N'ÊTES PAS PRÊT 🗡️🔪... allons travailler dans le casque directement
02:36:43 J'ai changé de PC, allons voir Meta Developer Hub
02:37:18 Allons utiliser ADB over Wi-Fi
02:37:43 Castons le casque ;)
02:38:31 Travaillons en XR 😎
02:39:08 Lançons Termux (Installation dans une autre vidéo)
02:39:23 Allez sur EloiTeaching pour trouver les vidéos d'installation de Termux
02:40:19 Allons dans Documents
02:41:25 Clonons le projet sur le casque dans Documents
02:42:01 un petit cd pour rentrer dans le projet et status pour check
02:42:41 Installer Godot depuis le store puis importons le projet
02:43:16 Tadaaam, notre projet dans le casque
02:44:17 Pincher rapidement pour sortir du jeu
02:44:23 Laisser enfoncé pour recentrer la scène
02:45:01 Travaillez en live entre l'éditeur et le jeu 😃😍
02:45:50 Comment on sauve nos changements en Termux dans le Quest ?
02:47:30 Allons voir le résultat sur PC 😉
02:48:16 Allons on le refait pour voir de PC à Quest
02:49:26 Note: Fermer et relancer Godot pour le forcer à recharger les fichiers
02:51:11 Tadaaam on a chargé depuis le PC un objet à voir en XR
02:51:40 Alors c'est fun d'importer... Mais ne pourrait-on pas créer sur le Quest 😁
02:51:47 Allons dessiner et exporter un sketch de Open Brush
02:52:48 Comment on l'exporte notre brush ?
02:54:10 Allons créer des œuvres d'arts en low poly avec Blocks
02:56:01 Comment sauver et exporter Blocks ?
02:56:38 Allons récupérer les fichiers à partir de F-Droid
02:57:18 Ouvrons Fossify File Manager pour déplacer nos fichiers
02:57:59 Bougeons notre création Blocks dans Godot
02:59:32 Blocks crée des OBJs, il nous faut donc un MeshInstance3D
03:00:44 Bougeons notre création Open Brush
03:01:42 C'est un GLB, ça s'importe facilement avec une instance
03:02:42 Allons un peu voir Gravity Sketch ;) C'est fou
03:04:55 Exportons notre création
03:05:04 Mais pour ça il nous faut un compte
03:05:22 En attendant de créer le compte allons peindre 🖼️🖌️
03:05:24 Ouvrons VR Paint
03:08:04 Exportons notre tableau en format .png
03:08:40 Déplaçons-le dans Godot en Sprite3D
03:11:13 Sauvons tout cela 😋 vous connaissez la routine maintenant.
03:12:14 Bon bah du coup, comment on va chercher notre Gravity Sketch si on a un compte
03:13:33 C'est un Zip... Mais par chance Fossify est un dézippeur
03:14:37 On l'a exporté en .CM... Ajustons dans Godot.
03:15:59 Notre objet est composé de 3 matériaux... Créez un commun
03:18:05 Je n'avais pas pu vous montrer Virtual Desktop. Une petite visite avant de stopper ?




 



































