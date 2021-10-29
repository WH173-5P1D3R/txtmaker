# txtmaker

# Textpro - Photooxy Unlimited API

This api can handle thousands of requests. Also its completely free
and unlimited resources. 

##

## 📦 NPM Installation

`npm i w5-textmaker`

##

## 🧾 Examples

### Textpro 1

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

### Textpro 2 ( Real Usage With One Message )

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

### Textpro 3 ( Real Usage With Two Message )

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
