# Anchor Link

ပြင်ပ Website များကိုဖြစ်စေ၊ မိမိ၏ Local Web Document ကိုဖြစ်စေ ချိတ်ဆက်ချင်တဲ့အခါ Anchor Link ကိုအသုံးပြုပါတယ်။

ပြင်ပ Website များကိုချိတ်ဆက်တဲ့အခါ အောက်ပါအတိုင်းချိတ်ဆက်ရပါတယ်။

```html
<a href="https://google.com">Go To Google</a>
```

`href` သည် Hyper Reference ရဲ့အတိုကောက်ဖြစ်ပါတယ်။
`href` Attribute သည် သွားလိုသည့် Destination (or) Path ကိုညွှန်းပေးပါတယ်။
ပြင်ပ Website များကို Link ချိတ်ချင်တာဖြစ်လို့ `https://`  (or) `http://` ဆိုတဲ့ Protocol ကို Website Address ရဲ့ ရှေ့မှာထည့်ပေးရပါတယ်။
ပြင်ပ Website များကိုချိတ်ဆက်ခြင်းကို Relative Linking လို့ခေါ်ပါတယ်။

Local Webpage များကိုချိတ်ဆက်ချင်တဲ့အခါ File Path ကိုချိတ်ပေးယုံပါပဲ။
ဉပမာ - index.html File နှင့် another.html ဆိုတဲ့ HTML ဖိုင် နှစ်ခုရှိတယ်ဆိုပါစို့။
`index.html` ကနေ `another.html` ကိုချိတ်ချင်တဲ့အခါအောက်ပါအတိုင်းချိတ်ရပါတယ်။

```html
<a href="another.html">Go To Another Local Web Page (or) Document</a>
````

အကယ်၍ `another.html` သည် Folder တစ်ခုအောက်တွင်ရှိလျှင် ယင်းဖိုဒါ Path ကိုပါအတိအကျထည့်ပြီးချိတ်ဆက်ပေးရပါတယ်။

```html
<a href="folderName/another.html">Go To Another Local Web Page (or) Document</a>
```

##.Local Web Document များကိုချိတ်ဆက်ခြင်းကို Absolute Linking လို့ခေါ်ပါတယ်။

**Identifier Name - ID**

ID ကိုတော့ Unique ဖြစ်စေချင်တဲ့အခါသုံးပါတယ်။
Local Web Document ထဲမှာရှိတဲ့ Data တွေကိုချိတ်ဆက်ချင်တဲ့အခါ ID သတ်မှတ်ပြီးတော့အတိအကျချိတ်ဆက်ရပါတယ်။
သို့မှသာ Link ကို နှိပ်လိုက်တဲ့အခါအတိအကျသွားမှာဖြစ်ပါတယ်။

ID သတ်မှတ်တဲ့အခါအောက်ပါအတိုင်းသတ်မှတ်ရပါတယ်။

```html
<p id="para">
  A Paragrapgh.
</p>
```

ထို ID ကို Anchor Link မှလှမ်းချိတ်ချင်တဲ့အခါ အောက်ပါအတိုင်းချိတ်ပေးရပါတယ်။

```html
<p id="para">
  A Paragrapgh.
</p>
<a href="#para"></a>
```

`#` - Pound Sign (or) Hash Sign အသုံးပြုပြီး Local Web Document ကိုချိတ်ဆက်နိုင်ပါတယ်။
`#` ရဲ့နောက်မှာတော့ သတ်မှတ်ခဲ့တဲ့ `id` ရဲ့ Value ကိုပေးရပါတယ်။သို့မှသာ Local Document အတွင်းကောင်းစွာအလုပ်လုပ်မှာဖြစ်ပါတယ်။
Local Document အတွင်း ချိတ်ဆက်ခြင်းကို Bookmark လုပ်ခြင်းလို့လည်းခေါ်ပါတယ်။
