# deploy_minecraft

Dette enkle skriptet, create_minecraft. sh distribuerer en Minecraft-server som en beholder til ACI, Azure container instances, aktivert for å være tilkoblet eksternt med MCRCON. Bare det du trenger å gjøre er å endre 6 skrivebeskyttet parametere i begynnelsen av skriptet.

Før du distribuerer en beholder, må du installere Azure CLI (https://docs.microsoft.com/ja-jp/cli/azure/install-azure-cli?view=azure-cli-latest) og abonnere på Azure.

Hvis du abonnerer på Azure, er det enklest å kjøre skriptet på Cloud Shell fra Azure Portal.

Dockerfile https://github.com/rioriost/dockerfiles/tree/master/minecraft-server

Docker-bilde https://cloud.docker.com/u/rioriost/repository/docker/rioriost/minecraft-server

Hvis du vil gjerne lek med en mengde av din venner, behage betenke å bruk â create_minecraft_vm. sh ' å oppstille en VM. ACI har begrenset vCPU og minne. f. eks 2vCPU og 8GB mem i Japan Øst-regionen. Du kan bruke kraftigere VM enn ACI.
