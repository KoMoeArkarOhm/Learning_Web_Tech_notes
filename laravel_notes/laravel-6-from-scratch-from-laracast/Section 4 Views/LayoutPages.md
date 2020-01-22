# အပိုင်း (၁၄) Layout Page
ကျွန်တော်တို့ view ဖိုင်တွေ အများကြီး ရှိတဲ့ အခါမှာ 
script လေး ၄ ကြောင်းလိုက်ထည်ချင်ရင်
 တစ်ဖိုင်ချင်းစီ လိုက်ထပ်နေရင် အချိန်ကုန်လူပန်းပြီး
လက်တွေမှာ laravel သမားတွေက အဲ့လို မထည်ကြပါဘူး။
အဲ့အတွက် layout file ဆိုတာကို သုံးကြပါတယ်။


```အရင်ဆုံး resources folderအောက်က views folderအောက်မှာ layout.blade.phpလိုဖန်တီးလိုက်ပါ။```


layout ဖိုင်ဆိုတာက အမြဲ   တူညီသော look ရှိသောနေရာများအတွက် ဘုံထုတ်ထားတာမျိုးပါ။

web page မှာ header, footer ကတော့ site ၏မည်သည် page မှာမဆို same look ရှိနေသင့်ပါတယ်။
body section ကတော့ မတူတဲ့အတွက် မတူသောအပိုင်းများကို
file ခွဲရေး layout file ကတော့ @yield ('content')
ဆိုပြီး ခေါယုံနဲ့ မတူတဲ့အပိုင်းတွေ အကုန် import လုပ်သုံးပါတယ်။


ကျွန်တော်ကိုယ်တိုင်တောင် ကိုယ်ရေးတာ ကိုယ်ဖတ်ရင်း
လည်ချင်လာသလို လုပ်ပြတာကို ကြည်ရင်း နားလည်သွားမှာပါ။

1.ဖန်တီးလိုက်တဲ့ layout file ထည်းကို welcome.blade.php က ဟာ တွေ အကုန် cut ပြီး layout.blade.php မှာ ကူးထည့်လိုက်

2.layout.blade.php က body tag ကြားက အကုန်ဖျက်လိုက်

3.layout.blade.php ရဲ့ body tag ကြားမှာ @yield ('content')လို ရေးလိုက်ပါ။

4.welcome.blade.php အပေါဆုံးမှာ

     @extends ('layout')
     @section ('content')
     @endsection လိုရေး

5.ဒီ section အဖွင့်အပိတ် နစ်ခု ကြားထည်းမှာ welcome page မှာ ပြချင်သော အရာတွေ ရေး


@extends ('layout')ဒီဆိုလိုရင်း က
ကျွန်တော်တို လိုချင်တဲ့ ဘုံ code တွေ ထပ်ရေးစရာမလိုပဲ
ဒီfileမှာထပ်လိုက်တာ
@section ('content')
ကတော့ section တစ်ခုသက်မှတ်လိုက်တာပါ။
content မှမဟုတ်ပါဘူး။ ကိုယ်စိတ်ကြိုက်နာမည်ပေးလို့ရပါတယ်။
ဒီ section သည် layout.blade.php မှ
body မှာရေးထားသော  @yield ('content') ဆိုတဲ့နေရာမှာ အစားဝင်သွားမှာပါ။
content နေရာ ကြိုက်တဲ့ နာမည်ပေးခဲ့ရင် @yield ('ကြိုက်တဲ့နာမည်')လိုခေါပေးရပါမယ်။

အဲတော့ ဘုံ ဖိုင်တစ်ခုရှိခြင်းကြောင့်
 ကျွန်တော်တို့ page တိုင်းကို လိုက်ပြင်စရာမလိုပဲ
တစ်နေရာပြင်လိုက်ယုံနဲ့ pageတိုင်း update ကို ရရှိမှာပဲဖြစ်ပါတယ် ခင်ဗျာ။


ဉပမာ contact page ထပ်ထည်ကြည်ရအောင်

 ```routes folder အောက်က web.php မှာ```

     Route::get('/contact', function() {
     return view('contact');
     });

လိုရေးလိုက်ပါ။
url ကိုသွားကြည့် ရင် contactဆိုသော view ဖိုင်မရှိသေးသောကြောင့် error ပြပါလိမ့်မယ်။

contact view file ဖန်တီးရအောင်။

```resources folder အောက်က views folderအောက်မှာ contact.blade.php``` လိုဖိုင်အသစ်ဆောက် ရေးချင်တာရေးပါ။

ပေါမှာလုပ်ခဲ့သလိုပါပဲ။

layout က codတွေ ပြန်ရေးစရာမလို‌အောင်

     @extends ('layout')
     @section ('content')
     ရေးချင်သော codeရေ
     @endsection
     
url မှာ /contact လိုရိုက်လိုက်ရင် ပေါလာပါမယ်။


