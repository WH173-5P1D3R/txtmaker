# txtmaker

# Textpro , Photooxy , Ephoto360 & Instagram Unlimited API

This api can handle thousands of requests. Also its completely free
and unlimited resources. 

##

## 📦 NPM Installation

`npm i w5-textmaker`

##

## 🧾 Examples

### Example Textmaker


#### Textpro 1

```js
const w5botapi = require('w5-textmaker'); // Import NPM Package

w5botapi.textpro("<textpro_html>",
    // "Message One" (One Message)
    // ["Message One"], ["Message Two"] (Two Message)
    ).then(async (data) => { 
      try { 
          console.log(dat)
      } catch(err) { 
          console.log(err)
      } 
});
```

#### Textpro 2 ( Real Usage With One Message )

```js
const w5botapi = require('w5-textmaker');

w5botapi.textpro("https://textpro.me/create-neon-devil-wings-text-effect-online-free-1014.html",
    "white spider"
    ).then(async (data) => { 
      try { 
          console.log(dat)
      } catch(err) { 
          console.log(err)
      } 
});
```

#### Textpro 3 ( Real Usage With Two Message )

```js
const w5botapi = require('w5-textmaker');

w5botapi.textpro("https://textpro.me/create-realistic-vintage-style-light-bulb-1000.html",
    ["Developer"], ["white spider"]
    ).then(async (data) => { 
      try { 
          console.log(dat)
      } catch(err) { 
          console.log(err)
      } 
});
```

#### Photooxy  ( Real Usage With One Message )

```js
const w5botapi = require('w5-textmaker');

w5botapi.photooxy("https://photooxy.com/logo-and-text-effects/create-a-picture-of-love-message-377.html",
    ["teks"]
  )
  .then((data) => console.log(data))
  .catch((err) => console.log(err));
```


#### Photooxy 2 ( Real Usage With Two Message )

```js
const w5botapi = require('w5-textmaker');

w5botapi.photooxy("https://photooxy.com/logo-and-text-effects/make-tik-tok-text-effect-375.html",
    ["teks", "Teks 2"]
  )
  .then((data) => console.log(data))
  .catch((err) => console.log(err));
```

#### Ephoto360  ( Real Usage With One Message )

```js
const w5botapi = require('w5-textmaker');

w5botapi.ephoto2("https://ephoto360.com/hieu-ung-chu-tren-nen-cat-trang-tuyet-dep-663.html", ["text"])
  .then((data) => console.log(data))
  .catch((err) => console.log(err));
```

#### Ephoto360 2 ( Real Usage With Two Message )

```js
const w5botapi = require('w5-textmaker');

w5botapi.ephoto2("https://ephoto360.com/tinh-yeu/viet-chu-len-bong-bay-tinh-yeu-189.html", ["text","text2"])
  .then((data) => console.log(data))
  .catch((err) => console.log(err));
```

### Example Downloader



#### Tiktok Downloader
 
 

 ```js
 const w5botapi = require('w5-textmaker');

  w5botapi.tiktok("https://vm.tiktok.com/ZSJb2Ly6t")
          .then((data) => console.log(data))
          .catch((err) => console.log(err));
``` 

#### Igstory Downloader
 
 

 ```js
 const w5botapi = require('w5-textmaker');

  w5botapi.igstory("wh173_5p1d3r_official")
          .then((data) => console.log(data))
          .catch((err) => console.log(err));
```

#### Igdownloader Downloader
 
 

 ```js
 const w5botapi = require('w5-textmaker');

  w5botapi.instagram("https://www.instagram.com/p/CSnz415reLK/?utm_source=ig_web_copy_link")
          .then((data) => console.log(data))
          .catch((err) => console.log(err));
```

#### Mediafire Downloader
 
 

 ```js
 const w5botapi = require('w5-textmaker');

  w5botapi.mediafire("https://www.mediafire.com/file/atxgngm36m0ytnn/example.txt/file")
          .then((data) => console.log(data))
          .catch((err) => console.log(err));
```
