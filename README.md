<h3>Ryou-Yamada Bot (BETA VERSION)</h3>

![ryou-bot](https://telegra.ph/file/10a40a757908e0b2888c5.jpg)

##

<h4>What is Ryou-Bot ?</h4>
<p>Ryou Bot Private Script Created by Michio and Not for Sale</p>

##
<h>**config.js**</h2>

```javascript
global.owner = ['62857122663191'];
global.mods = ['62857122663191'];
global.prems = ['62857122663191'];

global.nameowner = 'Michio';
global.numberowner = '62857122663191';
global.mail = 'michiokawaii@gmail.com';

global.namebot = 'Ryou - Bot Whatsapp';
global.gc = 'https://chat.whatsapp.com/I057peOL7sK7v1jqcTEXoZ';
global.web = 'https://chat.whatsapp.com/I057peOL7sK7v1jqcTEXoZ';
global.instagram = 'https://instagram.com/Dwi_skizo';

global.lolkey = 'GataDios';
global.title = 'Ryou - Bot Whatsapp'
global.thumb = 'https://telegra.ph/file/d5af2e5f90334885674b5.jpg'
global.source = 'https://instagram.com/Dwi_skizo'
global.profile = 'https://i.pinimg.com/originals/ee/83/b3/ee83b364c152f474b6e85e8b4737462f.jpg'
global.sig = 'https://instagram.com/Ryou-Yamada'
global.sazumi_version = '©Ryou-Yamada v1.0.1 (Beta)'
global.footer = '≈Ryou-Bot Created By Michio'
global.wm = 'Ryou - Bot Whatsapp';
global.watermark = wm;
global.wait = 'Wait a moment..';
global.imgur = 'Client-ID 5f98ee8de4fa3c5';
global.rose = 'YOUR_KEY_HERE';
global.xzn = 'michio';
global.sourceUrl = 'https://Instagram.com/Dwi_skizo';

global.stiker_wait = 'Wait a moment..';
global.packname = '@Ryou.Michio';
global.author = 'Ryou-Bot\n';

global.APIs = {
  lolhuman: 'https://api.lolhuman.xyz',
  rose: 'https://api.itsrose.life',
  skizo: 'https://xzn.wtf/'
};

global.APIKeys = {
  'https://xzn.wtf/': 'YOUR_KEY',
  'https://api.itsrose.life': 'YOUR_KEY_HERE',
  'https://api.lolhuman.xyz': 'GataDios',
};

global.multiplier = 45;
global.rpg = {
  emoticon(string) {
    string = string.toLowerCase();
    let emot = {
      exp: '✉️',
      money: '💵',
      potion: '🥤',
      diamond: '💎',
      common: '📦',
      uncommon: '🎁',
      mythic: '🗳️',
      legendary: '🗃️',
      pet: '🎁',
      sampah: '🗑',
      armor: '🥼',
      sword: '⚔️',
      kayu: '🪵',
      batu: '🪨',
      string: '🕸️',
      kuda: '🐎',
      kucing: '🐈',
      anjing: '🐕',
      petFood: '🍖',
      gold: '👑',
      emerald: '💚'
    };
    let results = Object.keys(emot).map(v => [v, new RegExp(v, 'gi')]).filter(v => v[1].test(string));
    if (!results.length) return '';
    else return emot[results[0][0]];
  }
};

let fs = require('fs');
let chalk = require('chalk');
let file = require.resolve(__filename);
fs.watchFile(file, () => {
  fs.unwatchFile(file);
  console.log(chalk.redBright("Update 'config.js'"));
  delete require.cache[file];
  require(file);
});
```
##

<h4>Bot Code Type</h4>

- <b>Plugins</b>
- ~Case~

##

- [Whatsapp](https://wa.me/+62857122663191)
- [Telegram](https://t.me/michiokawaii)
- [Group Official Ryou Bot](https://chat.whatsapp.com/IsLUDInfrTC4Tv74I96imL)
- [ryou-bot v1.0.0](https://wa.me/6285742548496?text=.menu)
##
