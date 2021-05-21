# Entities and Reading URI

`©,®,™` စတဲ့ Symbol တွေကို HTML ကနေသတ်မှတ်လို့ရပါတယ်။

`©` ကိုသုံးဖို့အတွက် `&copy;` ကိုသုံးနိုင်ပါတယ်။

```html
<p>
  &copy;2021-2022 By Programming 101.
</p>
```

Symbol List ကို အောက်ပါလိပ်စာမှာအသေးစိတ်ကြည့်လို့ရပါတယ်။

https://dev.w3.org/html5/html-author/charref

# Reading URI

https://example.com:443/post/?id=123

- https => Scheme 
- example.com => User Info
- 443 => Port
- /post/?id=123 => Query

Scheme ကတော့ HTTP,HTTPS နဲ့ FTPS လို Service တွေကိုဖော်ပြတာပါ။

example.com ကတော့ Host ပါ။

443 ကတော့ Port ဖြစ်ပါတယ်။

Query ကတော့သက်ဆိုင်ရာ Fragmentတွေကိုညွှန်းဖို့သုံးတာဖြစ်ပါတယ်။

# Other Example

```
          userinfo       host      port
          ┌──┴───┐ ┌──────┴──────┐ ┌┴┐
  https://john.doe@www.example.com:123/forum/questions/?tag=networking&order=newest#top
  └─┬─┘   └───────────┬──────────────┘└───────┬───────┘ └───────────┬─────────────┘ └┬┘
  scheme          authority                  path                 query           fragment

  ldap://[2001:db8::7]/c=GB?objectClass?one
  └┬─┘   └─────┬─────┘└─┬─┘ └──────┬──────┘
  scheme   authority   path      query

  mailto:John.Doe@example.com
  └─┬──┘ └────┬─────────────┘
  scheme     path

  news:comp.infosystems.www.servers.unix
  └┬─┘ └─────────────┬─────────────────┘
  scheme            path

  tel:+1-816-555-1212
  └┬┘ └──────┬──────┘
  scheme    path

  telnet://192.0.2.16:80/
  └─┬──┘   └─────┬─────┘│
  scheme     authority  path

  urn:oasis:names:specification:docbook:dtd:xml:4.1.2
  └┬┘ └──────────────────────┬──────────────────────┘
  scheme                    path
```
