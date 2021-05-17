# Table

ဇယားကွက်တွေကို Table လို့ခေါ်ပါတယ်။
Table တွေသည် Data Display တဲ့အခါ သေသေသပ်သပ်ဖြစ်စေပါတယ်။

Table တစ်ခုတွင် Table Row နှင့် Table Column ဆိုပြီးပါဝင်ပါတယ်။
Table Row ထဲမှ အကွက်လေးတစ်ကွက်စီကို Table Cell။ လို့ခေါ်ပါတယ်။

ထိုနည်းအတိုင်းပဲ - HTML ကိုအသုံးပြုတဲ့အခါ Table row , Table Column, Table Cell ဆိုပြီးသုံးခုပါရှိဖို့လိုအပ်ပါတယ်။

```html
<table>
<tr>
<td> ... </td>
</tr>
</table>
```

- `<table>` => Declared as a table
- `<tr>` => Table Row
- `<td>` => A Table Cell

Table ဖြစ်သည့်အတွက် Table Element ထဲမှာ Table Cell နှင့် Table Row ကိုထည့်ရေးရပါတယ်။
Table Row - `<tr>` Element တစ်ခုသည် Horizontal Row တစ်ခုကိုကိုယ်စားပြုပါတယ်။
သူ့အထဲက `<td>` Element ကတော့ Table Cell တစ်ကွက်ကိုကိုယ်စားပြုပါတယ်။
Table Data လို့ခေါ်ပါတယ်။

Table Row ထဲတွင် Table Cell များကိုထည့်သည့်အခါ ညာဘက်သို့ တစ်ကွက်ချင်းစီတိုးသွားမှာဖြစ်ပါတယ်။

```html
<table>
  <tr>
    <td>One</td>
    <td>Two</td>
    <td>Three</td>
  </tr>
</table>
```

Table Row ကတော့ နောက် Table Row အသစ်ယူဖို့သုံးပါတယ်။

```html
<table>
  <tr>
    <td>One</td>
    <td>Two</td>
    <td>Three</td>
  </tr>
  <tr>
    ...
  </tr>
</table>
```

ယခု ကျောင်းသားအမည်များကို Table ပုံစံဖြင့်ဖော်ပြကြည့်ပါမယ်။

```html
<table border="1">
  <tr>
    <th>No.</th>
    <th>Name</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Mg Mg</td>
  </tr>
  <tr>
    <td>2.</td>
    <td>Aung Aung</td>
  </tr>
  <tr>
    <td>3.</td>
    <td>Hla Hla</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Mya Mya</td>
  </tr>
</table>
<caption>Student Table</caption>
```

- Table ဖြစ်သည့်အတွက် Table Element နှင့် Wrap လုပ်ထားပါတယ်။
- ပထမဆုံး Table Row ထဲတွက်ပါဝင်သော `<the
>`  သည် Table Header ဖြစ်ပါတယ်။
- ထင်ရှားစေချင်လို့ `<td>` အစားသုံးတာဖြစ်ပါတယ်။
- ကျန်တဲ့ Table Row အသစ်များတည်ဆောက်တဲ့အခါ ပထမဆုံးပေးထားတဲ့ Table Row ထဲက Table Data အရည်အတွက်များနဲ့တူအောင်ထည့်ပါ။မထည့်တဲ့အခါ အကွက်တွေလိုနေတာ၊ ပိုနေတာ ဖြစ်တတ်ပါတယ်။
- Table Element ထဲက Border Attribute ကတော့ Default Table ပုံစံမှာ Border မပါတဲ့အတွက် Border ထည့်ပေးချင်လို့သုံးတာဖြစ်ပါတယ်။
- `1` ကတော့ Border ရဲ့ Size ဖြစ်ပါတယ်။
Caption Element ကိုတော့ Table ရဲ့ Caption ထည့်ပေးချင်တဲ့အခါသုံးပါတယ်။

```html
<table border="1">
  <tr>
    <th>No.</th>
    <th>Name</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Mg Mg</td>
  </tr>
  <tr>
    <td>2.</td>
    <td>Aung Aung</td>
  </tr>
  <tr>
    <td>3.</td>
    <td>Hla Hla</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Mya Mya</td>
  </tr>
</table>
<caption>Student Table</caption>
```
