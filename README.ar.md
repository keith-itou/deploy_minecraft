# deploy_minecraft

هذا البرنامج النصي البسيط، create_minecraft.sh ينشر خادم ماين كرافت كحاوية إلى ACI، مثيلات حاوية Azure، تمكين ليتم الاتصال عن بعد مع MCRCON. فقط ما عليك القيام به هو تغيير 6 معلمات للقراءة فقط في بداية البرنامج النصي. قبل نشر حاوية، يجب تثبيت Azure CLI (https://docs.microsoft.com/ja-jp/cli/azure/install-azure-cli?view=azure-cli-latest) والاشتراك في Azure. إذا كنت قد اشتركت في Azure، فمن الأسهل لتشغيل البرنامج النصي على سحابة شل من بوابة Azure.

دوكرفيل https://github.com/rioriost/dockerfiles/tree/master/minecraft-server

صورة المرسى https://cloud.docker.com/u/rioriost/repository/docker/rioriost/minecraft-server

إذا كنت ترغب في اللعب مع الكثير من أصدقائك، يرجى النظر في استخدام 'create_minecraft_vm.sh' لنشر VM. ACI لديها vCPU محدودة والذاكرة. على سبيل المثال 2vCPU و 8GB ميم في منطقة شرق اليابان. يمكنك استخدام VM أقوى من ACI.
