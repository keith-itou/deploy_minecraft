# deploy_minecraft

Script ini mudah, create_minecraft.sh merekacipta minecraft pelayan seperti bekas untuk ACI, keadaan bekas Azure, dibolehkan untuk dihubungkan dari jauh dengan MCRCON. Hanya apa yang anda perlu lakukan adalah mengubah 6 parameter readonly dalam permulaan skrip.

Sebelum menggunakan bekas, anda mesti memasang CLI Azure (https://docs.microsoft.com/ja-jp/cli/azure/install-azure-cli?view=azure-cli-latest) dan melanggan Azure.

Jika anda telah melanggan ke Azure, ia adalah yang paling mudah untuk Jalankan skrip pada Shell awan daripada Azure Portal. 

Dockerfile https://GitHub.com/rioriost/dockerfiles/Tree/Master/minecraft-Server

Imej docker https://Cloud.docker.com/u/rioriost/Repository/docker/rioriost/minecraft-Server

Jika anda ingin bermain dengan banyak kawan-kawan anda, sila pertimbangkan untuk menggunakan 'create_minecraft_vm.sh' untuk menempatkan sebuah VM. ACI terhad vCPU dan ingatan. Contohnya 2vCPU dan 8GB mem di kawasan Timur Jepun. Anda boleh menggunakan VM lebih berkuasa daripada ACI.
