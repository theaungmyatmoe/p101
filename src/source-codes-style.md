# Source Codes Style

ကျွန်တော်တို့ရေးသားနေတဲ့ HTML Source Code များကိုဖြစ်စေ၊ အခြား Language တစ်ခုခု၏ Source Code များကိုဖြစ်စေ Web Browser ပေါ်တွင်ဖော်ပြချင်တဲ့အခါ XMP Element,Pre Element နဲ့ Code Element တို့ကိုသုံးပါတယ်။

## XMP Element

```html
<xmp>
  <?php
  echo "Hello World!";
  ?>
</xmp>
```

## Pre Element

Pre Element ကို ဖော်ပြလိုသည့်စာသားကို Source Code ထဲတွင်ရေးသားသာ့်အတိုင်း Browser တွင်ဖော်ပြချင်တဲ့အခါအသုံးပြုပါတယ်။

```html
<pre>
    Hey
        Now
            Brown
                  Cow
</pre>
```

## Code Element

Inline Text များတွင် Source Code များကိုဖော်ပြချင်တဲ့အခါအသုံးပြုပါတယ်။

```html
<p>
 <code>echo "Hello World!";</code> is a  statement of PHP.
</p>
```