# Vue Editor

[![VueEditor](https://img.shields.io/npm/v/vue-md-editor.svg)](https://www.npmjs.org/package/vue-md-editor) [![NPM downloads](http://img.shields.io/npm/dm/vue-md-editor.svg)](https://npmjs.org/package/vue-md-editor) [![JS gzip size](http://img.badgesize.io/https://unpkg.com/vue-md-editor/dist/vue-editor.min.js?compression=gzip&label=gzip%20size:%20JS)](https://unpkg.com/vue-md-editor/dist/vue-editor.min.js)

## [Demo](http://vue-editor.beblog.cn/)
or [Edit in JSFiddle](https://jsfiddle.net/mb5kxrfb/6/)

## Install

```shell
npm install vue-md-editor --save
```
or
```html
<script src="https://unpkg.com/vue-md-editor/dist/vue-editor.min.js"></script>
```

## Usage

```js
// main.js
import Vue from 'vue'
import VueEditor from 'vue-md-editor'

Vue.use(VueEditor)

new Vue({
  el: '#app',
  data: {},
  ...
})
```
```html
<!--index.html-->
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>VueEditor example</title>
</head>
<body>
  <div id="app">
    <vue-editor v-model="value"></vue-editor>
  </div>
</body>
</html>
```

## Dependencies
- [marked](https://github.com/chjj/marked)
- [highlight.js](https://github.com/isagalaev/highlight.js)
- If you want's to use [highlight.js style](https://cdnjs.com/libraries/highlight.js/).

## Keyboards
Markdown | Result | Shortcut
---|---|---
\*\*text\*\* | **text** | Ctrl + B
\_text_ | _text_ | Ctrl + I
\### text | Heading | Ctrl + H
\~\~text\~\~ | ~~text~~ | Ctrl + D
\- text | List | Ctrl + U
<span>1. text</span> | List| Ctrl + O
\[Demo](http://vue-editor.beblog.cn) | [Demo](http://vue-editor.beblog.cn) | Ctrl + A
\!\[Image](https://cn.vuejs.org/images/logo.png "Title") | Image | Ctrl + P
\`text` | `text` | Ctrl + C
\> text | Blockquote | Ctrl + Q

## Issues
修复 [Issue #5](https://github.com/anguer/vue-editor/issues/5)


## License
Ruby on Rails is released under the MIT License.

