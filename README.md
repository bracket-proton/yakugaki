# Kogomi

女の子と山菜を採るノベルゲーム

・プレイ方法

ーブラウザ版

Cloudflare Pagesでホスティングしている。

https://yakugaki.pages.dev

> [!IMPORTANT]

> [Cloudflare Web Analytics](https://www.cloudflare.com/ja-jp/web-analytics/)を利用していますが*アクセスした時・数、リファラ、パス、ブラウザ、OS、デバイスタイプ（PCか携帯か）のみわかります。*それらは紐づけされていなく、ユニークユーザなどもわかりません。またトラッキングも行うことができません。

> サービス元の仕様変更が無い限り広告が表示されることはありません。

ー自分でビルド

ビルドしたプログラムはdistフォルダに生成される。実行ファイルではないので注意。

必要なもの

[Git](https://git-scm.com.)

[Node.js](https://nodejs.org.) 20+

```
git clone https://github.com/bracket-proton/yakugaki.git
cd yakugaki
npm install
npm run build
npm start
```

あら！ゲームをビルドできるならもう開発環境は整ってますね😁

[ドキュメント](https://docs.narrat.dev/jp/guides/getting-started.html)はこちらです

・アップデート

2024.05.07　システム：楽曲の差し替え、一部選択肢の並び替え、READMEの整備　https://4e11ae42.yakugaki.pages.dev

・使用フォント

はちまるポップ　Copyright 2020 The Hachi Maru Pop Project Authors (https://github.com/noriokanisawa/HachiMaruPop)

よもぎフォント　Copyright 2020 The Yomogi Project Authors (https://github.com/satsuyako/YomogiFont)

IBM Plex Sans JP　Copyright © 2017 IBM Corp

・使用楽曲

Pohádka (Janáček, Leoš)　 Le Chant du Monde, LD-M-8152 (P) 1956

※日本国内でのプレイのみ想定

・その他の画像やスクリプトについて

MITライセンスでライセンスされる。

画像は[public/img](/public/img/)に格納されている。

設定は[src/config](/src/config/)に、Narratスクリプトは[src/scripts](/src/scripts/)にあります。

以下NarratのREADMEテンプレート

# Narrat Template

Template app for [Narrat](https://github.com/nialna/narrat).

> ✨ Bootstrapped with Create Snowpack App (CSA).

## Usage

You can clone, fork or download this to get it in a local folder, then:

1. `npm install`
2. `npm start`

## Building for the web

`npm run build`

Builds the app for production to the `build/` folder.
It correctly bundles Vue in production mode and optimizes the build for the best performance.

It should be easy to host the built result as a static website on a service like [Netlify](https://www.netlify.com)

## Building as an app

This template has [electron](https://www.electronjs.org) already setup to create a built app of your game.

To run it:

`npm run electron`

To build it (it will come out in the `out` folder):

`npm run package`

This should work on Windows, Mac and Linux

## Narrat documentation

[See docs](https://docs.narrat.dev)

## Changing game code

You can edit game code and config in the data folder (`data/example.narrat`).

[See docs](https://docs.narrat.dev) for more usage info

## Available Scripts

### npm start

Runs the app in the development mode.
Open http://localhost:8080 to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.
