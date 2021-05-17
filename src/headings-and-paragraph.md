# Headings and Paragraph

Web Page များသည်လည်း Document များပဲဖြစ်သည့်အတွက် ခေါင်းစဉ်များ၊ စာပိုဒ်များ ကို HTML တွင်ရေးသားနိုင်ပါတယ်။

## Headings

ခေါင်းစဉ်များရေးသားတဲ့အခါ `<h>` Element ကိုအသုံးပြုပါတယ်။ `h` ရဲ့အရှည်ကတော့ Heading ဖြစ်ပါတယ်။
Heading ‌တည်‌‌ဆောက်တဲ့အခါ သူတို့ရဲ့ အရွယ်အစားကိုသတ်မှတ်ဖို့လိုပါတယ်။
Heading သည်အရွယ်အစား (၆) ခုရှိပါတယ်။
၎င်းတို့မှာ - 

```
Heading 1 => h1
Heading 2 => h2
Heading 3 => h3
Heading 4 => h4
Heading 5 => h5
Heading 6 => h6
```


`h1` သည် အကြီးဆုံးအရွယ်အစားဖြစ်ပြီး၊ `h6` သည် အငယ်ဆုံးအရွယ်အစားဖြစ်ပါတယ်။
၎င်းတို့ကို HTML ပုံစံဖြင့်ရေးသားရလျှင် -

```html
  <h1>Heading 1</h1>
  <h2>Heading 2</h2>
  <h3>Heading 3</h3>
  <h4>Heading 4</h4>
  <h5>Heading 5</h5>
  <h6>Heading 6</h7>
```
၎င်းတို့၏ ရလဒ်သည် အောက်ပါအတိုင်းဖြစ်ပေါ်လာမည်ဖြစ်သည်။

  <h1>Heading 1</h1>
  <h2>Heading 2</h2>
  <h3>Heading 3</h3>
  <h4>Heading 4</h4>
  <h5>Heading 5</h5>
  <h6>Heading 6</h7>
  
Heading များကိုအရေးကြီးသည့်ခေါင်းစဉ်ကြီးများအတွက်အသုံးပြုလေ့ရှိပါတယ်။

## Paragraph

Document တစ်ခုတွင် Heading အပြင် Paragraph များလည်းပါရှိပါသည်။ Paragraph တစ်ခုကို HTML တွင်အောက်ပါအတိုင်းရေးသားနိုင်ပါတယ်။

```html
<p>
A paragraph.
</p>
```

Paragraph များသည်တစ်ခုမကပို၍ရေးသားနိုင်သည်။ 

```html
  <p>
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ea quae, veritatis praesentium dicta unde et ex soluta ipsa, culpa in voluptate officiis nihil magni fugiat tempora, commodi nulla iste voluptatibus.
  </p>
  <p>
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Exercitationem animi corporis dolore optio facere odit illo fugit laborum, mollitia. Maiores, rem earum beatae reiciendis cumque aliquam consectetur! Maiores sapiente, cumque.
  </p>
  ```
  ၎င်းတို့ကို Web Browser က Render လုပ်တဲ့အခါ အောက်ပါအတိုင်းတွေ့ရမှာဖြစ်ပါတယ်။

  <p>
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ea quae, veritatis praesentium dicta unde et ex soluta ipsa, culpa in voluptate officiis nihil magni fugiat tempora, commodi nulla iste voluptatibus.
  </p>
  <p>
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Exercitationem animi corporis dolore optio facere odit illo fugit laborum, mollitia. Maiores, rem earum beatae reiciendis cumque aliquam consectetur! Maiores sapiente, cumque.
  </p>
  
Combination of Heading and Paragraph

Heading များနှင့် Paragraph များကိုအောက်ပါအတိုင်းပေါင်းရေးနိုင်ပါတယ်။

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Title of This Document</title>
</head>
<body>

  <h1>Programming 101</h1>
  <p>
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Officiis labore sunt sit, ut quos cupiditate autem, unde quis repellendus, placeat quidem a voluptatibus. Animi excepturi quia perferendis cum repellat tenetur!
  </p>
  <p>
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Reprehenderit qui minima doloribus suscipit eveniet nisi libero autem magni enim tempore, consectetur repudiandae voluptatem assumenda cumque, obcaecati. Magni aut vero labore.
  </p>
  <h2>About</h2>
  <p>
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rerum dignissimos magni consequuntur, earum atque assumenda similique et perferendis, ex, consequatur in, numquam a quis fugit sit alias suscipit dolor nam!
  </p>

</body>
</html>
```