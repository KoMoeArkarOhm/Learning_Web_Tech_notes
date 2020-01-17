# Basic Routing and Views 

## ````project folder```` ထည်းက ````routes folder```` ထည်းက ````web.php ````
![image of showing web.php](https://github.com/KoMoeArkarOhm/image_resources_to_use_in_my_repositories/blob/master/laracast_note_1.PNG)

web.phpမှာ ကျွန်တော်တို့ project ကို run လိုက်ရင်ပြမယ့် laravel default home page route ကိုရေးထားတာပါ

```
Route::get('/', function () {
    return view('welcome');
});
```

/ ဆိုတာက browserမှာ www.ohm.com လိုပဲ ပြောပြော www.ohm.com/ ပဲပြောပြောပါ အတူတူကို ဆိုလိုခြင်းပါ။
မယုံရင် အခု run ထားတဲ့ http://127.0.0.1:8000 ကို / ပါြခင်း မပါခြင်း သည် ဘာထူးသွားလည်း သိရအောင် စမ်းကြည်ပါ။

run လိုက်ရင် default page ကိုပြမယ်ဆိုတာ ကျွန်တော်တို့ သိပြီးသားပါ။
run တော့ request သည် server ကိုdefault homepage ကိုပြပေးပါ ပြောလိုက်တာပါ။
request ရှိရင် response ရှိရမယ်။
အဲ့တာကြောင့် return ဆိုပြီး welcome လိုနာမည်ရတဲ့ view တစ်ခုကို response ပြန်လိုက်တယ်။

အဲ့တော့ view ဆိုတာဘာကြီးလည်း အုန်းကြီးရ လုပ်ပါအုန်း?????????????

view ဆိုတာက project code base တစ်ခုလုံးမှာ html အပိုင်းလေးကို ပြောတာဗျ။

အဲ့တာဆို view ဖိုင်လေးတွေက html တွေပါမှာပေါ့နော်။

ဟုတ်တာပေါ့ဗျ။

view ဖိုင်လေးတွေကို ကြည်ချင်ရင်
resources folder ထည်းမှာ views ဆိုတဲ့ folder မှာ သိမ်းထားတာဗျ။
အဲ folder ကိုဖွင်ကြည်ရင် ဒိလိုမျိုးရေး တွေရမယ်။
ဟော် အခုနက welcome view ကို တွေပြီမလား။


![image of showing web.php](https://github.com/KoMoeArkarOhm/image_resources_to_use_in_my_repositories/blob/master/lara_cast2.PNG)

Ok!! အဲ့တာဆိုရင် project ၏ အောက်ဆုံးနားလောက်ကိုသွား ပုံမှာမြင်ရတဲ့ laravel ဆိုတဲ့ နေရာကို ကိုယ်ရေးချင်တာရေးလိုက်ပါ။

![image of showing laravel text in web.php](https://github.com/KoMoeArkarOhm/image_resources_to_use_in_my_repositories/blob/master/lara_cast3.PNG)

ကျွန်တော် ရေးလိုက်သောစာ

![image of my text](https://github.com/KoMoeArkarOhm/image_resources_to_use_in_my_repositories/blob/master/lara_cast4.PNG)

run ထားတဲ့ project ကိုပြန်ကြည်လိုက်ရင်တော့ 

![image of showing web.php](https://github.com/KoMoeArkarOhm/image_resources_to_use_in_my_repositories/blob/master/after_changing_pj.png)

ကျွန်တော်၏ url မှာ web.php မှာ မသတ်မှတ်ထားသော route ကို စမ်းခေါကြည်ကြည်ကြပါစို။

ကျွန်တော် url bar or address bar မှာ ပုံမှာပြထားတဲ့အတိုင်း index.html တို့  home တို့ a  တို့ စမ်းကြည်တဲ့အခါ web.phpမှာ မသတ်မှတ်ထားတဲ့ route ဖြစ်တဲ့အတွက် မိတ်ဆွေ တွေးထားသလိုပါပဲ မရှိဘူးဆိုသော 404 page not found errorကိုတွေရမှာပဲဖြစ်ပါတယ်။

![image of showing 404 Error](https://github.com/KoMoeArkarOhm/image_resources_to_use_in_my_repositories/blob/master/showing404Error.PNG)

![image of showing 404 Error](https://github.com/KoMoeArkarOhm/image_resources_to_use_in_my_repositories/blob/master/showing404Error1.PNG)

![image of showing 404 Error](https://github.com/KoMoeArkarOhm/image_resources_to_use_in_my_repositories/blob/master/showing404Error2.PNG)


နောက်ထပ် စမ်းချင်တာ စမ်းပါ မရှိတာမို မရှိဘူး စက်ကတော့ ဆက်ပြောနေမှာပါ။အဲ့တော့ ဆက်ရအောင်။


