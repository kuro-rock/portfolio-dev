# portfolio

> my portfolio

## Build Setup

``` bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).


# Sass
## scssファイル構造
### main.scss
```
@import 'settings/index'; // 設定周り
├ @import './variable'; //Sass変数
├ @import './animation'; //アニメーション
┗ @import './mixin'; // Sass mixin関数

@import 'base/index'; // 要素style定義・font設定

@import 'layout/index'; // レイアウト用style定義

@import 'module/index';
├ @import './block'; // ブロック単位のモジュール
┗ @import './element'; // 要素単位のモジュール

@import 'helper/index'; // 汎用ヘルパーclass

@import 'pages/index'; // NuxtのPages単位でしか利用しない定義
```
