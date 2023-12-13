<h3>Ryou-Yamada Bot (BETA VERSION)</h3>

![ryou-bot](https://telegra.ph/file/10a40a757908e0b2888c5.jpg)

##

<h4>What is Ryou-Bot ?</h4>
<p>Ryou Bot uses the initial base of Suzumi-Bot, this private bot is just for appearance </p>

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
global.sazumiviki_title = 'Ryou - Bot Whatsapp'
global.sazumiviki_thumb = 'https://telegra.ph/file/d5af2e5f90334885674b5.jpg'
global.sazumiviki_source = 'https://instagram.com/Dwi_skizo'
global.sazumiviki_profile = 'https://i.pinimg.com/originals/ee/83/b3/ee83b364c152f474b6e85e8b4737462f.jpg'
global.sig = 'https://instagram.com/Ryou-Yamada'
global.sazumi_version = '©Ryou-Yamada v1.0.1 (Beta)'
global.footer = '≈Ryou-Bot Created By Michio'
global.wm = 'Ryou - Bot Whatsapp';
global.watermark = wm;
global.wait = 'Wait a moment..';
global.sazumiviki_imgur = 'Client-ID 5f98ee8de4fa3c5';
global.rose = 'YOUR_KEY_HERE';
global.xzn = 'michio';
global.sourceUrl = 'https://Instagram.com/Dwi_skizo';

global.stiker_wait = 'Wait a moment..';
global.packname = '@Ryou.Michio';
global.author = 'Ryou-Bot\n';

global.APIs = {
  lolhuman: 'https://api.lolhuman.xyz',
  rose: 'https://api.itsrose.life',
  skizo: 'https://xzn.wtf/',
  sazumiviki: 'https://api.sazumiviki.me'
};

global.APIKeys = {
  'https://api.sazumiviki.me': 'sazumiviki',
  'https://xzn.wtf/': 'sazumiviki',
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
- No Bot : [ryou-bot v1.0.0](https://wa.me/6285742548496?text=.menu)
##

<h4>The script is supported to run on:</h4>

- [x] Rdp
- [x] Vps
- [x] Railway
- [x] Panel Pterodactyl  

##

<h4>Minimum specifications required</h4>

- [x] **Node Version:** 18.16.1
- [x] **Npm Version:** 9.8.0
- [x] **Cpu:** 300%
- [x] **Memory:** 3GB
- [x] **Disk:** 5GB

##

<h4>Recommendations specifications required</h4>

- [x] **Node Version:** 18.16.1
- [x] **Npm Version:** 9.8.0
- [x] **Cpu:** 400%
- [x] **Memory:** 8GB
- [x] **Disk:** 10GB

##

<h4>Latest changelog update</h4>

| ChangeLog | Published On |
| ----- | ------------ |
|  New feature, **create subdomains** and **delete subdomains** ( cloudflare )| Tue Aug 22 2023 |
|  Fixed **simi simi** features| Tue Aug 22 2023 |
|  Fix **Antiporn**| Mon Aug 21 2023 |
|  Fixed the **pairing code** error when entering the **pairing code**| Fri Aug 18 2023 |
|  Added features **Tebak Bom**| Fri Aug 18 2023 |
|  Fixed **Backup** Feature on Bot| Thu Aug 17 2023 |
|  Updating the data on the **lyric feature**| Tue Aug 15 2023 |
|  Added **ram** usage **limit**| Tue Aug 15 2023 |
|  Add Feature **Tts**| Mon Aug 14 2023 |
|  New Feature **Compress Image**| Sun Aug 13 2023 |
|  New Feature **Deepfake**| Sun Aug 13 2023 |
|  New Sticker Feature **.snobg (Sticker without background)** & **.scircle (Circle shape sticker)**| Sun Aug 13 2023 |
|  Remove **Bard Ai**| Sat Aug 12 2023 |
|  Fix **Emojimix**| Fri Aug 11 2023 |
|  Starting **sazumi-bot version 1.0.0** and onwards| Thu Aug 10 2023 |

