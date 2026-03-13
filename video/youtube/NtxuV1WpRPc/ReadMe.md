Comment créer un projet Godot sur SteamVR et Quest 3 avec GitHub
https://youtu.be/NtxuV1WpRPc


Selling point of this tutorial:
https://youtu.be/NtxuV1WpRPc?t=10235

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



 























 



































