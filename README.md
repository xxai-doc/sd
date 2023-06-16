<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

ان کي انسٽال ڪرڻ جي صلاح ڏني وئي آهي nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) پهرين, ۽ پوء `direnv allow` ڊاريڪٽري ۾ داخل ٿيڻ کان پوء ( [. envrc](https://github.com/xxai-art/doc/blob/main/.envrc) ڊاريڪٽري ۾ داخل ٿيڻ کان پوء خودڪار طريقي سان عمل ڪيو ويندو).

مطلب آهي: چيني ترجمو جاپاني، ڪورين، انگريزي، انگريزي ترجمو ٻين سڀني ٻولين ۾. جيڪڏهن توهان صرف چيني ۽ انگريزي کي سپورٽ ڪرڻ چاهيو ٿا، توهان صرف لکي سگهو ٿا `zh: en` .

## اڳيون ڪوڊ

* [اڳيون ڪوڊ](https://github.com/xxai-art/web)
* [مڪمل طور تي سائيٽ لاء ٻولي پيڪ](https://github.com/xxai-art/web/tree/main/i18n)
* [لاگ ان ماڊلز لاءِ ٻولي پيڪ](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [ويب سائيٽ گهڻ لساني دستاويز](https://github.com/xxai-doc)

سامهون واري پروگرامنگ ٻولي [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) آهي، جيڪا ڪافي اسڪرپٽ نحو جي بنياد تي ڪجهه خاصيتون شامل ڪري ٿي، ڏسو [./coffee_plus.md](./coffee_plus.md) .

## ويب سائيٽن ۽ دستاويزن جي بين الاقواميت

ھيٺ ڏنل 3 منصوبن تي ٺاھيو

* [@w5/mdt](https://www.npmjs.com/package/@w5/mdt)

  لاحقو `.mdt` آھي، توھان استعمال ڪري سگھوٿا نحو جھڙيءَ طرح `<+ ./coffee_plus/import.js>` ٻاھرين فائلن جي حوالي ڪرڻ لاءِ، ۽ لاحقہ سان مارڪ ڊائون ٺاھيو `.md` .

* [@w5/trmd](https://www.npmjs.com/package/@w5/trmd)

  مارڪ ڊائون ترجمو ڪوڊس ۽ لنڪس جو ترجمو نه ڪندو، ۽ ترجمو ڪيل جملن کي ڪيش ڪندو. جيڪڏهن ترجمو تبديل ڪيو ويو آهي پر اصل متن تبديل نه ڪيو ويو آهي، ان کي ٻيهر هلائڻ سان ترجمي جي ترميم کي ختم نه ڪيو ويندو.

* [@w5/i18n](https://www.npmjs.com/package/@w5/i18n)

  `yaml` ٺاهيل ويب سائيٽن جو ترجمو ڪرڻ لاءِ ٻولي فائلون.

### دستاويزن ترجمو خودڪار هدايتون

ڏسو ڪوڊ مخزن [xxai-art/doc](https://github.com/xxai-art/doc)

ان کي انسٽال ڪرڻ جي صلاح ڏني وئي آهي nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) پهرين, ۽ پوء `direnv allow` ڊاريڪٽري ۾ داخل ٿيڻ کان پوء ( [. envrc](https://github.com/xxai-art/doc/blob/main/.envrc) ڊاريڪٽري ۾ داخل ٿيڻ کان پوء خودڪار طريقي سان عمل ڪيو ويندو).

سوين ٻولين ۾ ترجمو ٿيل وڏي ڪوڊ بيس کان بچڻ لاءِ، مون ھر ٻوليءَ لاءِ الڳ ڪوڊ بيس ٺاھيو ۽ ڪوڊ بيس کي ذخيرو ڪرڻ لاءِ ھڪڙي تنظيم ٺاھي

ماحوليات جي متغير `GITHUB_ACCESS_TOKEN` ترتيب ڏيڻ ۽ پوءِ هلائڻ سان [create.github.coffee](https://github.com/xxai-art/doc/blob/main/create.github.coffee) خودڪار طريقي سان ڪوڊ ريپوزٽري ٺاهي ويندي.

يقينا، توهان ان کي ڪوڊ بيس ۾ پڻ رکي سگهو ٿا.

ترجمو اسڪرپٽ جو حوالو [run.sh](https://github.com/xxai-art/doc/blob/main/run.sh)

اسڪرپٽ ڪوڊ هن ريت بيان ڪيو ويو آهي:

[bunx](https://bun.sh/docs/cli/bunx) npx جو متبادل آھي، جيڪو تيز آھي. يقينا، جيڪڏهن توهان بون نصب نه ڪيو آهي، توهان ان جي بدران استعمال ڪري سگهو ٿا `npx` .

`bunx mdt zh` `.mdt` کي zh ڊاريڪٽري ۾ `.md` طور ڏيکاري ٿو، ھيٺ ڏنل 2 ڳنڍيل فائلون ڏسو

* [coffee_plus.mdt](https://github.com/xxai-doc/zh/blob/main/coffee_plus.mdt)
* [coffee_plus.md](https://github.com/xxai-doc/zh/blob/main/coffee_plus.md)

`bunx i18n` ترجمي لاءِ بنيادي ڪوڊ آهي (جيڪڏهن توهان وٽ صرف `nodejs` انسٽال ٿيل آهن، پر `bun` ۽ `direnv` انسٽال ٿيل نه آهن، توهان پڻ هلائي سگهو ٿا `npx i18n` ترجمو ڪرڻ لاءِ).

اهو پارس ڪندو [i18n.yml](https://github.com/xxai-art/doc/blob/main/i18n.yml) ، هن دستاويز ۾ `i18n.yml` جي تشڪيل هن ريت آهي:

```
en:
zh: ja ko en
```

مطلب آهي: چيني ترجمو جاپاني، ڪورين، انگريزي، انگريزي ترجمو ٻين سڀني ٻولين ۾. جيڪڏهن توهان صرف چيني ۽ انگريزي کي سپورٽ ڪرڻ چاهيو ٿا، توهان صرف لکي سگهو ٿا `zh: en` .

آخري آهي [gen.README.coffee](https://github.com/xxai-art/doc/blob/main/gen.README.coffee) ، جيڪو مواد ڪڍي ٿو مکيه عنوان جي وچ ۾ ۽ هر ٻوليءَ جي `README.md` جي پهرين ذيلي عنوان جي وچ ۾ داخل ٿيڻ لاءِ `README.md` . ڪوڊ تمام سادو آهي، توهان ان کي پاڻ ڏسي سگهو ٿا.

گوگل API استعمال ڪيو ويندو آهي مفت ترجمي لاءِ. جيڪڏھن توھان گوگل تائين رسائي نٿا ڪري سگھو، مھرباني ڪري ھڪ پراڪسي ترتيب ۽ سيٽ ڪريو، جھڙوڪ:

```
export https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890
```

ترجمو اسڪرپٽ `.i18n` ڊاريڪٽري ۾ ترجمو ڪيل ڪيش ٺاهيندو، مهرباني ڪري ان کي `git status` سان چيڪ ڪريو ۽ بار بار ترجمن کان بچڻ لاءِ ان کي ڪوڊ ريپوزٽري ۾ شامل ڪريو.

مھرباني ڪري ھلايو `bunx i18n` هر دفعي جڏھن توھان ڪيش کي اپڊيٽ ڪرڻ لاءِ ترجمي ۾ ترميم ڪريو.

جيڪڏهن اصل متن ۽ ترجمي کي ساڳئي وقت تبديل ڪيو وڃي ته، ڪيش ۾ مونجهارو ٿيندو، تنهنڪري جيڪڏهن توهان ترميم ڪرڻ چاهيو ٿا، ته توهان صرف هڪ کي تبديل ڪري سگهو ٿا، ۽ پوءِ ڪيش کي اپڊيٽ ڪرڻ لاءِ `bunx i18n` هلايو.
