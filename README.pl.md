# deploy_minecraft

Ten prosty skrypt, create_minecraft. sh wdraża serwer Minecraft jako kontener do ACI, Azure Container Instances, umożliwił zdalne połączenie z MCRCON. Tylko co trzeba zrobić, to zmiana 6 ReadOnly parametry na początku skryptu.

Przed wdrożeniem kontenera, należy zainstalować interfejs wiersza polecenia platformy Azure (https://docs.microsoft.com/ja-jp/cli/azure/install-azure-cli?view=azure-cli-latest) i subskrybować Azure.

Jeśli subskrybujesz Azure, jest najłatwiejszy do uruchomienia skryptu w usłudze Cloud Shell z witryny Azure Portal.

Plik dockerfile https://github.com/rioriost/dockerfiles/tree/master/minecraft-server

Obraz platformy Docker https://cloud.docker.com/u/rioriost/repository/docker/rioriost/minecraft-server

Jeśli chcesz grać z wieloma znajomymi, należy rozważyć użycie "create_minecraft_vm. sh" do wdrożenia maszyny wirtualnej. ACI ma ograniczony procesor vCPU i pamięć. np. 2vCPU i 8GB mem w regionie Japonia Wschodnia. Można użyć bardziej wydajne maszyny wirtualnej niż ACI.
