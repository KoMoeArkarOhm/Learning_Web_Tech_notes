# laravel ကို ဘယ်လိုသွင်းကြမလဲ (window version)

1. xampp ကိုသွင်းပါ။
xampp သွင်းတာ ပြဿနာရှိ မရှိသိဖို့ C အောက်က xampp ကိုသွား xampp control ကိုဖွင့် mysql နဲ့ သူအောက်က apacheနဲ့ ကို startတွေနိပ်
cmd မှာ 

          php -v လိုရိုက်


လိုရိုက် လို php versionပေါရင် working fineပါ။

2. composer ကိုသွင်းပါ။

composer သွင်းတာ ပြဿနာရှိ မရှိသိဖို့

          composer -V
          
လိုရိုက် လို composer versionပေါရင် working fineပါ။


3. ပထမဆုံး,  Laravel installer ကို  Composer သုံးပြီး download ဆွဲမယ်: cmd မှာ


          composer global require laravel/installer
          
4. laravel သွင်းပြီးရင်  ````laravel command```` သုံးပြီး project တစ်ခုဖန်တီးရအောင် cmd မှာ

          laravel new blog

blog ဆိုတဲ့နေရာမှာ ကြိုက်တဲ့နာမည်ပေးလို့
လိုရပါတယ်။
အခုလုပ်သွားတာက ````laravel new command```` ကိုသုံးပြီး blog ဆိုသော folderထည်းမှာ
laravel project တစ်ခု တည်ဆောက်သွားတာပဲဖြစ်ပါတယ်။

or 
composer သုံးပြီး project ဆောက်မယ်!! cmd မှာ

          composer create-project --prefer-dist laravel/laravel blog
          
````composer create-project --prefer-dist အဖွဲနာမည်/project_name project_folder_name   ````    ပြောတာပါ။    
