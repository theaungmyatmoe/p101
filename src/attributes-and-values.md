# Attributes and Values

HTML Document များကို HTML Element များနှင့်တည်ဆောက်ပါတယ်။
HTML Element တစ်ခုတွင် -

- Opening Tag   => `<opening-tag>`
- Content           => `Content`
- Closing Tag    => `</closing-tag>`

ဟူ၍သုံးခုပြည့်စုံရန်လိုအပ်ပါတယ်။

## HTML Element

```html
<opening-tag> Content </closing-tag>
```

Opening Tag နှင့် Closing Tag ထဲတွင် HTML ကသတ်မှတ်ထားသောသက်ဆိုင်ရာ Tag Name များကိုထည့်ရေးနိုင်မှာဖြစ်ပါတယ်။
Closing Tag များတွင် `/` ပါသည်ဆိုတာကိုသျိပြုဖို့လိုအပ်သလို။
Opening Tag ပြီးတဲ့နောက်မှာ Closing Tag အသုံးပြုပြန်ပိတ်ဖို့ကိုလည်းသတိပြုပါ။

Paragraph Element တစ်ခုတည်ဆောက်မယ်တိုလျှင် အောက်ပါအတိုင်းတည်ဆောက်ရပါတယ်။

```html
<p>
Content
</p>
```

- `<p>`         => Opening Tag
- `Content` => Content
- `</p>`       => Closing Tag

`p` သည် Tag Name ဖြစ်ပါတယ်။ HTML ကသတ်မှတ်ထားသော Tag Name များကို `p` နေရာတွင်အသုံးပြုနိုင်မှာဖြစ်ပါတယ်။

HTML တွင် အချက်အလက်‌များ ထပ်ထည့်ထည့်ချင်တဲ့အခါ HTML Attribute များကိုအသုံးပြုပါတယ်။
Attribute များကို HTML Opening Tag ထဲတွင်ထည့်သတ်မှတ်ရပါတယ်။

```
<opening-tag attributeName="Information"> Content </closing-tag>
```

Attribute Name သည် HTML ကသတ်မှတ်ထားသော Property Name ဖြစ်ပါတယ်။
Information သည် HTML Property နှင့်တွဲဖက်အသုံးပြုနိုင်သော Value ဖြစ်ပါတယ်။

ဉပမာအားဖြင့် HTML Document နောက်ခံကိုအနီရောင်ပြောင်းမယ်ဆိုလျှင် နှစ်ပိုင်းခွဲလို့ရပါတယ်။

- HTML Document
- နောက်ခံကိုအနီရောင်ပြောင်းမယ်

Document သည် User မြင်ရသောအပိုင်းဖြစ်၍ `body` Element ကိုဆိုလိုပါတယ်။
`နောက်ခံကိုအနီရောင်ပြောင်းမယ်` ဆိုတာသည်ထပ်ထည့်ရမည့်အချက်အလက်ဖြစ်ပါတယ်။

ဒါ့ကြောင့် -

`body` Element ‌ရဲ့ နောက်ခံကို အနီရောင်ပြောင်းမယ်လို့  ဆိုလိုပါတယ်။

Body Element ဖြစ်၍ -

```html
<body> 
...
</body>
```

ဖြစ်သည်။

Background Color ဖြစ်၍ `bgcolor` ဆိုတဲ့ Attribute Name ကိုသုံးရမှာဖြစ်ပါတယ်။
Value ကိုတော့ အနီရောင်ပြောင်းမှာဖြစ်လို့ `red` လို့ထည့်ပေးရမှာဖြစ်ပါတယ်။

```html
<body bgcolor="red"> 
...
</body>
```
ထိုအခါ Web Page Document ကြီးသည် အနီရောင်နောက်ခံ‌ ပြောင်းသွားတာကိုတွေ့ရမှာဖြစ်ပါတယ်။

> မှတ်ချက်။ ။ HTML တွင် Attributes Name ကို Property လို့အသုံးမပြုပါ။
> Attribute Name နှင့် Value လို့သာသုံးပါတယ်။
> နားလည်စေရန်သာရည်ရွယ်ပြီး Property လို့သုံးတာဖြစ်ပါတယ်။