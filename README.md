# Discord_MessageAutoRole
Sorry, Source code comment out and message in Japanese...
Editting...

## Download
[Click](https://github.com/Ay2416/Discord_MessageAutoRole/archive/refs/heads/main.zip)

# Japanese
Sorry, Source code comment out and message in Japanese...

## 使用言語
JavaScript

## 動作確認済み環境
npm

Node.js v18

discord.js

## 概要

Discord上で動作する、設定した合言葉に対して、認証に成功すれば成功用のロールを、失敗すれば失敗用のロールを自動付与するbotです。

## 動作方法
1. Discordのアカウントが必要なため、アカウントを作成してください。
また、Botを動かすのにトークン等が必要なため、下記URLを参照にBotの作成、取得をしてください。

* [https://dot-blog.jp/news/discord-bot-token/](https://dot-blog.jp/news/discord-bot-token/)

2. 展開されたZipファイルから出てくる「Discord_MessageAutoRole-main」というファイルの中に「.env」というファイルがあるため、テキストエディタで開いて、「your_discord_bot_token」という部分を取得したBotのトークンを入れてください。

3. 「src」フォルダの中の「index.js」をテキストエディタで開き、passwordに設定したい合言葉を。そして、「role_id_1」と「role_id_2」を付与したいロールのIDに書き換えてください。
* 参考サイト:[https://note.com/bardbot/n/na70832cb70a3](https://note.com/bardbot/n/na70832cb70a3)

4. 動作させるのにNode.jsが必要なため下記URLよりインストールします。

* [https://nodejs.org/ja/](https://nodejs.org/ja/)

5. 展開されたZipファイルの中の「Discord_MessageAutoRole-main」にターミナル（Mac,Linux）やコマンドプロンプトで（Windows）移動し、「npm install」を打った後に、「Node src/index.js」と打つとプログラムが起動し、Discord上でBotが立ち上がります。

6.botを招待し、権限の設定で認証用で使う以外のチャンネルをbotが見れないように権限を調整します。

7.無事に認証され、DMに何かしらの反応があれば成功です。

## 利用したもの、参考にしたサイト

* Node.js：[https://nodejs.org/ja/](https://nodejs.org/ja/)

* discord.js：[https://discord.js.org/](https://discord.js.org/)

* node-fetch v2：[https://www.npmjs.com/package/node-fetch](https://www.npmjs.com/package/node-fetch)

* Dotenv：[https://www.npmjs.com/package/dotenv](https://www.npmjs.com/package/dotenv)

* Discord.js Japan User Group：[https://scrapbox.io/discordjs-japan/](https://scrapbox.io/discordjs-japan/)

# English
## Use Language
JavaScript

## Operationg environment
npm

Node.js v18

discord.js

## expanation

## How to use?

1. Discord account create. Bot work token. Because of that, discord bot create and get the code. Please refer to the following. (※Sorry, Japanese Website)

* Discord bot token : [Google translate this site](https://dot--blog-jp.translate.goog/news/discord-bot-token/?_x_tr_sl=ja&_x_tr_tl=en&_x_tr_hl=ja&_x_tr_pto=wapp)

2. Zip File unzip. "Discord_MessageAutoRole-main" folder open, and ".env" file open in text editor. (Visual Studio code etc...) "your_discord_bot_token" write my discord bot token. "src" foleder open, and "index.js" file open in text editor. Source code search "auth_key: 'your_auth_key'". "your_auth_key" write my deepl API key.

3. Node.js need. Please refer to the following.

* [https://nodejs.org/en/](https://nodejs.org/en/)

4. "Discord_MessageAutoRole-main" directory open Terminal(Mac, Linux) or Command Prompt. Typing command "npm install". Next, typing command "node src/index.js", start bot.

## Extension library and use data

* Node.js：[https://nodejs.org/ja/](https://nodejs.org/ja/)

* discord.js：[https://discord.js.org/](https://discord.js.org/)

* node-fetch v2：[https://www.npmjs.com/package/node-fetch](https://www.npmjs.com/package/node-fetch)

* Dotenv：[https://www.npmjs.com/package/dotenv](https://www.npmjs.com/package/dotenv)

* Discord.js Japan User Group：[https://scrapbox.io/discordjs-japan/](https://scrapbox.io/discordjs-japan/)
