# Copycat [![Chrome Web Store](https://img.shields.io/chrome-web-store/v/jdjbiojkklnaeoanimopafmnmhldejbg.svg?maxAge=86400)](https://chrome.google.com/webstore/detail/copycat/jdjbiojkklnaeoanimopafmnmhldejbg) [![Mozilla Add-on](https://img.shields.io/amo/v/extension-copycat.svg?maxAge=864000)](https://addons.mozilla.org/firefox/addon/extension-copycat/) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/BlackGlory/copycat/master/LICENSE)

[![Copycat](https://github.com/BlackGlory/copycat/blob/master/src/assets/images/icon-128.png?raw=true)](https://chrome.google.com/webstore/detail/copycat/jdjbiojkklnaeoanimopafmnmhldejbg)

Copy content from web powerful than ever before.

## Support browsers

- [x] [Chrome](https://chrome.google.com/webstore/detail/copycat/jdjbiojkklnaeoanimopafmnmhldejbg)
- [x] [Firefox](https://addons.mozilla.org/firefox/addon/extension-copycat/)
- [x] Opera: Code review too slow, never publish again, please manually install.
- [x] [Vivaldi](https://chrome.google.com/webstore/detail/copycat/jdjbiojkklnaeoanimopafmnmhldejbg)
- [ ] Edge: Microsoft Edge is not compatible with [mozilla/webextension-polyfill](https://github.com/mozilla/webextension-polyfill) because of [Issue #3](https://github.com/mozilla/webextension-polyfill/issues/3), so I had to give up porting.

## Features

- [ ] 累加式剪贴板(开启, 关闭)
- [ ] 将多行缩为一行复制(在IETF的文档和电子邮件格式里, 会出现这种将一句话拆分成多行的文本形式)
- [x] Copy tab link as
  - [x] Plaintext
  - [x] Markdown
  - [x] BBCode
  - [x] HTML
  - [ ] Org-mode
- [x] Copy frame link as
  - [x] Plaintext
  - [x] Markdown
  - [x] BBCode
  - [x] HTML
  - [ ] Org-Mode
- [x] Copy link as
  - [x] Markdown
  - [x] BBCode
  - [x] HTML
  - [ ] Org-mode
- [x] Copy selection as
  - [x] Plaintext
  - [x] Raw strings
  - [x] Markdown
  - [x] BBCode
  - [x] HTML
  - [x] HTML(only \<a\> tag)
  - [x] HTML(no attributes)
  - [ ] JSON string
- [x] Copy image as
  - [x] Markdown
  - [x] Markdown(DataURI jpeg, png, webp\*)
  - [x] HTML
  - [x] HTML(DataURI jpeg, png, webp\*)
  - [x] DataURI(original format)
  - [x] DataURI(jpeg, png, webp\*)
  - [x] BBCode
- [x] Copy browser native audio/video as HTML

\* *WebP format is Chromium(Chrome, Opera, Vivaldi) only*

## Support Markdown flavors

- [x] [GitHub Flavored Markdown](https://github.github.com/gfm/)
- [x] [CommonMark](http://commonmark.org/)
- [x] [Ghost's Markdown](https://help.ghost.org/article/4-markdown-guide)

## Extension shortcuts

Copy tab link and selection can be set as extension shortcuts.

Manage Chrome shortcuts: `chrome://extensions/shortcuts`
Manage Firefox shortcuts: `about:addons` -> Extensions -> Settings -> Manage Extension Shortcuts
