- déployer-minecraft

Ce script simple, create-minecraft.sh déploie un serveur minecraft comme un conteneur à ACI, Azure Container Instances, activé pour être connecté à distance avec MCRCON. Seul ce que vous devez faire est de changer 6 paramètres lissés au début du script. 

Avant de déployer un conteneur, vous devez installer Azure CLI (https://docs.microsoft.com/ja-jp/cli/azure/install-azure-cli?view=azure-cli-latest) et vous abonner à Azure.

Si vous vous êtes abonné à Azure, il est le plus facile d'exécuter le script sur Cloud Shell à partir d'Azure Portal. 

Dockerfile (Dockerfile) https://github.com/rioriost/dockerfiles/tree/master/minecraft-server

Image Docker https://cloud.docker.com/u/rioriost/repository/docker/rioriost/minecraft-server

Si vous voulez jouer avec beaucoup de vos amis, s'il vous plaît envisager d'utiliser 'create'minecraft'vm.sh' pour déployer une machine utile. ACI a un vCPU et une mémoire limités. par exemple 2vCPU et 8 Go mem dans la région du Japon Est. Vous pouvez utiliser plus puissant VM que ACI.
