
<<<<<<< HEAD
## Install Unity with Vuforia
=======
Install Unity with Vuforia
>>>>>>> fd8df98ca5740f104215deeb5c9e67b4a65bb259
https://docs.unity3d.com/Manual/vuforia_get_started_project_setup.html

Récupérer la dernière version d'Unity 
https://unity3d.com/get-unity/download

Liste des composants à cocher dans l'install 
Unity
Documentation
Standards Assets
Android Build Support
Vuforia Augmented Reality

<<<<<<< HEAD

## Configuration
=======
Configuration
>>>>>>> fd8df98ca5740f104215deeb5c9e67b4a65bb259
Une fois Unity installé et le projet récupéré sur github
Edit > Project Settings > Player
Onglet Android => Vuforia Suported Reality


<<<<<<< HEAD
## Build And Run
=======
Build And Run
>>>>>>> fd8df98ca5740f104215deeb5c9e67b4a65bb259
Edit > Project Settings > Player
Onglet Android => Other Setting 
Compléter Package Name : com.Tracksgame.ARBuildTest par ex.


Branché le smartphone en USB sur le PC
Activé le mode Développeur dans système/option pour les developpeurs sur le smartphone
<<<<<<< HEAD

Sur gitBash, activer ADB
```
=======

Sur gitBash, activer ADB

Facultatif
>>>>>>> fd8df98ca5740f104215deeb5c9e67b4a65bb259
export JAVA_HOME='"C:\Program Files\Java\jdk1.8.0_191"'
export ANDROID_HOME="C:\Users\Lenovo\AppData\Local\Android\Sdk"
```

Get <device name>
<<<<<<< HEAD
```
Adb devices 
```
Si liste vide, penser à vérifier si le mode debugger via USB est bien activé dans système/option pour les developpeurs sur le smartphone
```
=======
Adb devices 
Si liste vide, penser à vérifier si le mode debugger via USB est bien activé dans système/option pour les developpeurs sur le smartphone
>>>>>>> fd8df98ca5740f104215deeb5c9e67b4a65bb259
adb -s <device name> reverse tcp:8081 tcp:8081
QV7022820B

adb reverse tcp:8081 tcp:8081
Ou
adb -s QV7022820B reverse tcp:8081 tcp:8081
```

Fin
