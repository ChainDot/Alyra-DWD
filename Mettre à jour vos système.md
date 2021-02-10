# **Installation de Node et Visual Studio Code**

## Installation de Node

 * Mettre à jours son systeme 
 
 ```zsh 
 sudo apt update && sudo apt upgrade -y 
 ```
 
 * Installer et mettre à jour NVM "Node version manager".
 
 ```zsh
 curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash
 ```
 
 * Vérifier que NVM est installé.
 
 ```zsh
 command -v nvm
 ```
 
L'output devrait être ``` nvm ``` si votre installation est réussite.

 * Pour télécharger, compiler, et installer la dernière version de Node il faut :
 
 ```zsh
 nvm install node # "node" is an alias for the latest version
 ```
 
 * Pour Installer une version spécifique de Node il faut :
 
 ```zsh
 nvm install 6.14.4 # or 10.10.0, 8.9.1, etc
 ```
La première version installée devient celle par défaut.


## Installation de Visual Studio et d'extensions (Code runner, Prettier)

* Par le terminal télecharger et installer Visual studio

```zsh
sudo apt install ./<file>.deb
```
 
 Installer le package .deb installera automatiquement apt repository et signer pour les mises à jour automatique avec le system package manager.
 
 
* Installation de Code runner extension pour executer le code sur node.
