# xGetter Library for Android!
[![](https://jitpack.io/v/KhunHtetzNaing/xGetter.svg)](https://jitpack.io/#KhunHtetzNaing/xGetter)

ရုပ်ရှင်နဲ့ Video App ဖန်တီးချင်သူတွေအနေနဲ့
အသုံးဝင်မယ့် Lib လေးတစ်ခုဖန်တီးပေးထားပါတယ်။
Video တွေကို အကန့်အသတ်မရှိ Free တင်လို့ရပြီး
ကြည့်တဲ့အချိန်မှာကြော်ငြာအရမ်းတက်တဲ့
Openload, Streamango တို့လိုလင့်တွေကနေ
ကြော်ငြာကြည့်စရာမလိုပဲ
တိုက်ရိုက်ဒေါင်းဖို့လင့်ဆွဲထုတ်ပေးနိုင်တဲ့ကောင်လေးပါ။
ရလာတဲ့လင့်ကို တိုက်ရိုက်ဒေါင်းမလား
ကိုယ်ပိုင် Player နဲ့တိုက်ရိုက်ပြမလား
အဆင်ပြေသလိုအသုံးချနိုင်ပါတယ်။
လောလာဆယ်ပါဝင်တဲ့ Site တွေကတော့
- **Openload**
- **Streamango**
- **MegaUp**
- **Streamcherry**
- **RapidVideo**
- **Mp4Upload**
- **VidCloud**
- **SendVid**
တို့ပဲဖြစ်ပါတယ်။
ဒီဆိုဒ်တွေအားလုံးကနေ ကြော်ငြာကြည့်စရာမလိုပဲတိုက်ရိုက်လင့်ထုတ်ပေးမှာပါ။
အခြားအခမဲ့ Video တင်လို့ရတဲ့ Site တွေကိုလည်းထပ်ဖြည့်ပေးသွားပါ့မယ် :)
အဲ့တော့ Video Sharing App အတွက် Host ဝယ်စရာမလိုတော့ဘူးလေနော် ;)
Lib နာမည်ကိုတော့ **xGetter** လို့ပဲပေးထားပါတယ်။

အသုံးပြုနည်း
===========
ပထမဦးဆုံး **build.gradle(project)** ထဲက

    allprojects {
        repositories {
            .......
            maven { url 'https://jitpack.io' } //ဒီကုဒ်လေးထည့်ပေးပါ။
        }
    }

ပြီးရင် **build.gradle(app)** ထဲက

    dependencies {
        .........
        implementation 'com.github.KhunHtetzNaing:xGetter:1.1'
    }

**Android Studio** သမားတွေဆိုရင်တော့ **Sync Now** လုပ်ပေးပါ။
**​AIDE** သမားဆိုရင်တော့ **Save** ပြီး **Download** လုပ်ခိုင်းရင်လုပ်ပေးပါ။
**မှတ်ချက်။  ။အင်တာနက်ဖွင့်ထားဖို့လိုပါမယ်**

ပြီးရင်တော့ကိုယ်ခေါ်ချင်တဲ့ Activity ကနေ

    XGetter xGetter = new XGetter(this);
            xGetter.onFinish(new XGetter.OnTaskCompleted() {
                @Override
                public void onTaskCompleted(String vidURL) {
                    // တိုက်ရိုက်လင့်က vidURL
                }
    
                @Override
                public void onError() {
                    // Error
                }
            });
            xGetter.find("Video လင့္");

အသုံးပြုရတာလည်းလွယ်ပါတယ် :)

 - Example APK => http://bit.ly/2TDvLQ2
 - Example Project => http://bit.ly/2Sr6Hiw
 - Repo => https://github.com/KhunHtetzNaing/xGetter

#HtetzNaing #XGetter #2019
