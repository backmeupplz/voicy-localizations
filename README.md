[![Voicybot](/img/logo.png?raw=true)](http://voicybot.com/)

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
Please note that all contributors whos translations were accepted will receive 10,000 seconds of Google Speech voice recognition as a reward. If you want to receive the reward, please notify [@borodutch](https://telegram.me/borodutch) about your efforts. Thank you!

# As seen on
[![Habrahabr](/img/habr.png?raw=true)](https://habrahabr.ru/post/316824/)
