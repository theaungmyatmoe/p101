# Form and Input Types

Website မှာ User ရဲ့ Data ကို Collect လုပ်ချင်တဲ့အခါ သုံးပါတယ်။
User Data Collect လုပ်တယ်ဆိုတာ -
Username , Password အစရှိတဲ့ Data တွေကိုတောင်းယူတဲ့လုပ်ငန်းကိုဆိုလိုတာဖြစ်ပါတယ်။

```html
<form>
    ...
</form>
```

Form တစ်ခုကို Input လေးတွေနဲ့ဖွဲ့စည်းပါတယ်။
ထို Input လေးမှာ User ဆီကတောင်းယူရမယ့် Data Type ကိုသတ်မှတ်ပေးရပါတယ်။

```html
<form>
    <input>
</form>
```

**Output**
<form>
    <input>
</form>

Input ရဲ့ Default ကတော့ Text ဖြစ်ပါတယ်။

Form Input မှာ Data Type သတ်မှတ်ဖို့ဆိုရင် `type="text"` Attribute ကိုသုံးပြီးသတ်မှတ်နိုင်ပါတယ်။

Form Input Type အတော်များများကို HTML က Support ပေးပါတယ်။ဒီအထဲမှာမှအသုံးများတဲ့ Type လေးတွေနဲ့ဉပမာပေးသွားပါမယ်။

```html
<form>
    <input type="text">
</form>
```

Text ကတော့ Default Type ဖြစ်ပါတယ်။
Password ကိုလက်ခံတဲ့အခါ `password` Type ကိုအသုံးပြုနိုင်ပါတယ်။

```html
<form>
    <input type="password">
</form>
```

အခြားအသုံးပြုနိုင်တဲ့ Type တွေကတော့ အောက်ပါအတိုင်းဖြစ်ပါတယ်။

```
number
button
color
date
datetime
datetime-local
email
month
number
range
search
tel
time
url
week
```

Input ကို User ကဖြည့်ကိုဖြည့်ရမယ့်အချိန်မျိုးကြရင် `required` ဆိုတဲ့ Attribute ကိုသုံးပါတယ်။

```html
<form>
    <input type="text" required>
 </form>
```

**Output**
<form>
    <input type="text" required>
 </form>

Email Type ကိုအသုံးပြုတဲ့အခါ Suggestion များပေါ်တတ်ပါတယ်။ Suggestion များသည်မျက်စိနောက်စရာဖြစ်စေပါတယ်။
ဒီ့အတွက် `autocomplete="off"` ကိုသုံးနိုင်ပါတယ်။

```html
<form>
    <input type="email" autocomplete="off">
</form>
```

**Output**
<form>
    <input type="email" autocomplete="off">
</form>

Input မှာ `value` Attribute ကို Data တွေကြိုထည့်ချင်တဲ့အခါအသုံးပြုနိုင်ပါတယ်။
ဒီ့အပြင် Database မှပြန်ကျလာသော Data များကိုပြ‌ချင်တဲ့အခါလည်းသုံးသလို၊ JavaScript ကနေ Data ကို Collect ဖို့လည်းသုံးလေ့ရှိပါတယ်။

```html
<form>
    <input type="text" value="John Doe" />
 </form>
 ```
 
 **Output**
 <form>
    <input type="text" value="John Doe" />
 </form>
 
User ကို Input မှာဖြည့်ရမယ့် Data ကို Hint ပေးချင်တဲ့အခါ `placeholder` Attribute ကိုသုံးပါတယ်။

```html
<form>
    <input type="text" placeholder="John Doe" />
</form>
```

**Output**
<form>
    <input type="text" placeholder="John Doe" />
</form>

ယခု Username နဲ့ Password တောင်းတဲ့ Form တစ်ခုကိုတည်ဆောက်ကြည့်ပါမယ်။

```html
<form action="">
  <label for="Username">Username</label><br>
  <input type="text" name="Username" id="Username" placeholder="John Doe" /><br>

  <label for="Email">Email</label><br>
  <input type="email" id="Email" placeholder="you@example.com"><br>

  <input type="submit" value="Login">
</form>
```

**Output**
<form action="">
  <label for="Username">Username</label><br>
  <input type="text" name="Username" id="Username" placeholder="John Doe" /><br>

  <label for="Email">Email</label><br>
  <input type="email" id="Email" placeholder="you@example.com"><br>

  <input type="submit" value="Login">
</form>

- Label Element ကို Label Label Nameတပ်ချင်တဲ့အခါသုံးပါတယ်။
- For Attribute ကတော့ Lable Name ကိုနှိပ်တဲ့အချိန်မှာ ID သတ်မှတ်ထားတဲ့ Input ပေါ်ကို Cursor လေးရောက်သွားဖို့ဖြစ်ပါတယ်။
- Submit Button ကိုတော့ Data တွေပို့ဖို့သုံးပါတယ်။



Checkbox 

Checkbox ကို Multiple Selection တွေမှာအသုံးများပါတယ်။

```html
<form>
  <input type="checkbox" />Orange <br>
  <input type="checkbox" />Mango <br>
  <input type="checkbox" />Banana <br>
</form>
```

**Output**
<form>
  <input type="checkbox" />Orange <br>
  <input type="checkbox" />Mango <br>
  <input type="checkbox" />Banana <br>
</form>

# Radio

Radio Type ကိုတော့ တစ်ခုတည်းအတိအကျလိုချင်တဲ့အခါသုံးပါတယ်။

```html
<form>
  <input type="radio" name="gender" />Male <br />
  <input type="radio" name="gender" />Female <br />
</form>
```

**Output**
<form>
  <input type="radio" name="gender" />Male <br />
  <input type="radio" name="gender" />Female <br />
</form>

Name Attribute ကို Server ကနေ လှမ်း ဖတ်နိုင်ဖို့သုံးပါတယ်။
Radio Type မှာ Name ထည့်ရသလိုကျန်တဲ့ Input တွေမှာလည်း Name Attribute ထည့်လို့ရပါတယ်။