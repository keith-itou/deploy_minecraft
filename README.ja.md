# デプロイ_マインクラフト

この単純なスクリプト create_minecraft.sh は、MCRCON とリモート接続を有効にした ACI Azure コンテナー インスタンスにコンテナとして minecraft サーバーをデプロイします。 必要なのは、スクリプトの先頭で 6 つの読み取り専用パラメータを変更することだけです。

コンテナーをデプロイする前に、Azure CLI (https://docs.microsoft.com/ja-jp/cli/azure/install-azure-cli?view=azure-cli-latest) をインストールし、Azure にサブスクライブする必要があります。

Azure にサブスクライブしている場合は、Azure Portal からクラウド シェルでスクリプトを実行するのが最も簡単です。

ドッカーファイル https://github.com/rioriost/dockerfiles/tree/master/minecraft-server

Docker イメージ https://cloud.docker.com/u/rioriost/repository/docker/rioriost/minecraft-server

たくさんの友達と遊びたい場合は、VMをデプロイするために'create_minecraft_vm.sh' を使用することを検討してください。ACI には、vCPU とメモリが限られています。例えば、東日本リージョンの2vCPUと8GBのミーム。ACI よりも強力な VM を使用できます。
