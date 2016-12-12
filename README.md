[![Voicybot](/img/logo.png?raw=true)](https://voicybot.com/)

# [@voicybot](https://telegram.me/voicybot) localization files
This repository contains all the strings used in this bot with an instrument to localize them to different languages. If you want add your language to [@voicybot](https://telegram.me/voicybot), please fork, edit `strings.js` file and submit new pull request.

Please follow the same `strings.js` file internal format:
```javascript
const localize = new Localize({
  'potato': {
    'en': 'potato',
    'ru': 'картошка',
    'fr': 'pomme de terre'
  },
  'tomato': {
    'en': 'tomato',
    'ru': 'помидор',
    'fr': 'tomate'
  },
});
```

# As seen on
[![Habrahabr](/img/habr.png?raw=true)](https://habrahabr.ru/post/316824/)
