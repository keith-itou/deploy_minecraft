# deploy_minecraft

create_minecraft.sh 라는 간단한 스크립트는 마인크래프트 서버를 ACI, Azure 컨테이너 인스턴스에 컨테이너로 배포하여 MCRCON과 원격으로 연결할 수 있도록 합니다. 스크립트의 시작 부분에서 6 개의 readonly 매개 변수를 변경해야합니다.

컨테이너를 배포하기 전에 Azure CLI(https://docs.microsoft.com/ja-jp/cli/azure/install-azure-cli?view=azure-cli-latest)를 설치하고 Azure를 구독해야 합니다.

Azure를 구독한 경우 Azure Portal에서 클라우드 셸에서 스크립트를 실행하는 것이 가장 쉽습니다.

도커 파일 https://github.com/rioriost/dockerfiles/tree/master/minecraft-server

도커 이미지 https://cloud.docker.com/u/rioriost/repository/docker/rioriost/minecraft-server

많은 친구들과 함께 플레이하고 싶다면 'create_minecraft_vm.sh'를 사용하여 VM을 배포하는 것을 고려해 보십시오. ACI에는 vCPU와 메모리가 제한되어 있습니다. 예를 들어, 일본 동부 지역에서 2vCPU 및 8GB 밈. ACI보다 더 강력한 VM을 사용할 수 있습니다.
