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

![image of showing 404 Error1](https://github.com/KoMoeArkarOhm/image_resources_to_use_in_my_repositories/blob/master/showing404Error1.PNG)

![image of showing 404 Error2](https://github.com/KoMoeArkarOhm/image_resources_to_use_in_my_repositories/blob/master/showing404Error2.PNG)


နောက်ထပ် စမ်းချင်တာ စမ်းပါ မရှိတာမို မရှိဘူး စက်ကတော့ ဆက်ပြောနေမှာပါ။အဲ့တော့ ဆက်ရအောင်။

laravel မှာ response ပြန်ဖို့ နည်းတွေ အများကြီးရှိတယ်
ဉပမာ ရိုးရိုး string ကို return ပြန်ကြရအောင်။

code မှာ returnနောက်မှာ ပုံမှာပြထားသလို ပြင်လိုက်ပါ။

![image of showing code of returning string](https://github.com/KoMoeArkarOhm/image_resources_to_use_in_my_repositories/blob/master/returning_string.PNG)

output:

![image of showing output of returning string](https://github.com/KoMoeArkarOhm/image_resources_to_use_in_my_repositories/blob/master/returning_string_output.PNG)

JSON return ပြန်မယ်။

code မှာ returnနောက်မှာ ပုံမှာပြထားသလို ပြင်ချင်ရင်ပြင် ကြိုက်တဲ့စာသားရေးပါ။ ကျွန်တော် ပြင်လိုက်သောစာသား

![image of showing 404 Error2](https://github.com/KoMoeArkarOhm/image_resources_to_use_in_my_repositories/blob/master/returning_json.PNG)

output in firefox :

![image of showing 404 Error2](https://github.com/KoMoeArkarOhm/image_resources_to_use_in_my_repositories/blob/master/jsonputput.png)





တခြား browser မှာကြည်ရင် ဉပမာ chrome မှာ

![image of showing 404 Error2](https://github.com/KoMoeArkarOhm/image_resources_to_use_in_my_repositories/blob/master/output_chrome.PNG)

အဲလိုတွေမြင်ရပါမယ်။

firefox လို တွေချင်ရင်တော့ add-on or extension သွင်းပေးရပါမယ်။
firefox headers tag အောက်မှာ content-type ဆိုတဲ့ နေရာကို ကြည်ရင် application/json ဖြစ်လို json အမျိုးအစားမှန်းသိနိင်ပါတယ်။


![image of showing content type](https://github.com/KoMoeArkarOhm/image_resources_to_use_in_my_repositories/blob/master/jsonputput1.png)

ဒီမှာ ထူးထူးခြားခြားမှတ်သားရမှာက  ကျွန်တော်တို့ php array ကြီး return ပြန်လိုက်ပေမယ့် laravel က json အဖြစ် အလိုလျှောက်ပြောင်းပေးလိုက်တာပါပဲ။
['ညီမလေး'] ဆိုပြီး ညီမလေးရှေ့မှာ array ကိုခေါပြလိုက် ထွက်တာတဲ့ outputမြင်ပြီး ပီတီများ ဖြာစေမလား ဟဲဟဲ
