                                                                                  SAE_1.03



Installation d'une VM via Oracle: 
J'ai décidé d'installer une VM avec Oracle car j'étais curieux de voir comment cela fonctionnait. Je voulais comprendre ce qu'était une VM mais surtout comment en installer une. 
Processus d'installation :
Tout d'abord, il faut aller sur Oracle VM VirtualBox
-Installer la VM adapté à notre OS 
-Installer un ISO (XUBUNTU par exmple)
-Configurer sa VM avec l'ISO
-Mettre un nom d'utilisateur et un mot de passe 
-Configurer sa VM de sort à ce que l'ISO puisse s'installer par la suite(ex:mettre la capacité de stockage à 25Go)
-Lancer la VM
-Installer Docker:
Pour mettre à jour le ststème : sudo apt update et sudo apt upgrade 
-Installer les paquets pré-requis pour Docker  : sudo apt-get install  curl apt-transport-https ca-certificates software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
Ensuite, nous ajoutons le dépôt :  sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
Après cela, il suffit de mettre à jour les informations du dépôt :
-sudo apt update
Et enfin : sudo apt install docker-ce   ;pour installer docker 
-Installer VsCode : Aller sur Internet, tapper Vscode, télécharger le fichier qui correspond à votre OS donc pour ma part le format x64 sur WIndows. Puis ouvrir le fichoer.
-Installer GIT, puis se connecter sur Vscode avec les commandes: git config --global user.name "John Doe"  et  git config --global user.email johndoe@example.com
-Ensuite, cloner le repository sur Vscode permet de choisir dans quel repository nous voulons un changement. Nous avons plus qu'à Commit. 
-Pour faciliter l'échange de donées entre Github et Vscode, nous pouvons également ajouter l'extension Github Codespaces
-Python installé directement avec Xubuntu don il y a plus qu'à le lancer avec la commande python3
-Installer l'extension java : sudo apt install openjdk-11-jdk   
-Compiler un fichier java avec la commande javac Executable.java pour le fichier Executable.java 
-Puis l'exécuter avec: java Executable 


Configurer WSL2:
J'ai également installer WSL2(Windows Sub Linux) afin de me faciliter l'accès à un environnement Linux. Avec une simple commande, je peux désormais accèder à l'univers de Linux. 
Processus d'installation:
-Tout d’abord : wsl --install  
-Télécharger "Package de mise à jour du noyau Linux WSL2 pour machines x64" qui se trouve sur le site de Microsoft 
-Se créer un compte UNIX avec un mot de passe 
-wsl : Lance la distribution installée  
-wsl -l -v : Voir la version installée  
-wsl -l : voir les distributions installées 
Ensuite, il faut faire 
-sudo apt upgrade : Installe les dernières mises à jour 
-sudo apt update : Met à jour  
-Installer l'extension java : sudo apt install openjdk-11-jdk  
-Compiler un fichier java avec javac Executable.java 
Puis l'exécuter avec java Executable  
Installer Docker:
Pour mettre à jour le ststème : sudo apt update et sudo apt upgrade 
-Installer les paquets pré-requis pour Docker  : sudo apt-get install  curl apt-transport-https ca-certificates software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
Ensuite, nous ajoutons le dépôt :  sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
Après cela, il suffit de mettre à jour les informations du dépôt :
-sudo apt update
Et enfin : sudo apt install docker-ce   ;pour installer docker 
-Installer VsCode : Aller sur Internet, tapper Vscode, télécharger le fichier qui correspond à votre OS donc pour ma part le format x64 sur WIndows. Puis ouvrir le fichoer.
-Installer GIT, puis se connecter sur Vscode avec les commandes: git config --global user.name "John Doe"  et  git config --global user.email johndoe@example.com
Ensuite, cloner le repository sur Vscode permet de choisir dans quel repository nous voulons un changement. Nous avons plus qu'à Commit. 
-Pour faciliter l'échange de donées entre Github et Vscode, nous pouvons également ajouter l'extension Github Codespaces
-Python3 installé directement avec Ubuntu donc avec la commandee python3, il se lance
 
