# WeChat Snippets for Visual Studio Code

This extension adds WeChat Snippets into Visual Studio Code.

这个插件基于最新的微信小程序 API 添加了Code Snippets。

### It looks like:
![](https://raw.githubusercontent.com/hollowtree/vscode-vue-snippets/master/img/show1.png)

![](https://raw.githubusercontent.com/hollowtree/vscode-vue-snippets/master/img/show2.png)


### Snippets
Including most of the API of WeChat. You can type `wxif`, choose `wxIf`, and press ENTER, then `wx:if="{{condition}}"` appear on the screen.

插件的 Snippets 如下表格所示，比如你可以键入 `wxif` 然后按上下键选中 `wxIf` 再按Enter键，就输入了`wx:if="{{condition}}`了。

| Prefix | JavaScript Snippet Content |
| ------ | ------------ |
| `import` | `import ... from ...` |
| `createApp` | `createApp({...})` |
| `createPage` | `createPage({...})` |
| `createComponent` | `createComponent({...})` |
| `data` | `date: {...}` |
| `methods` | `methods: {...}` |
| `computed` | `computed: {...}` |
| `watch` | `watch: {...}` |
| `onLaunch` | `onLaunch({...})` |
| `onShow` | `onShow({...})` |
| `onHide` | `onHide({...})` |
| `onError` | `onError({...})` |
| `onPageNotFound` | `onPageNotFound({...})` |
| `onUnhandledRejection` | `onUnhandledRejection({...})` |
| `onThemeChange` | `onThemeChange({...})` |
| `onLoad` | `onLoad({...})` |
| `onUnload` | `onUnload({...})` |
| `onPullDownRefresh` | `onPullDownRefresh({...})` |
| `onReachBottom` | `onReachBottom({...})` |
| `onShareAppMessage` | `onShareAppMessage({...})` |
| `onShareTimeline` | `onShareTimeline({...})` |
| `onAddToFavorites` | `onAddToFavorites({...})` |
| `onPageScroll` | `onPageScroll({...})` |
| `onResize` | `onResize({...})` |
| `onTabItemTap` | `onTabItemTap({...})` |
| `properties` | `properties: {...})` |
| `attached` | `attached({...})` |
| `ready` | `ready({...})` |
| `moved` | `moved({...})` |
| `detached` | `detached({...})` |
| `mpxCanIUse` | `mpx.canIUse(string)` |


<br />

| Prefix | directives Snippet Content |
| ------ | ------------ |
| `template` | `<template></template>` |
| `script` | `<script></script>` |
| `style` | `<style></style>` |
| `wxFor` | `wx:for="{{items}}" wx:key="index"` |
| `wxModel` | `wx:model="{{something}}"` |
| `wxIf` | `wx:if="{{condition}}"` |
| `wxElse` | `wx:else` |
| `wxElif` | `wx:elif="{{condition}}"` |
| `bindtap` | `bindtap` |
| `wx:ref` | `wx:ref="{{reference}}"` |
| `wx:key` | `wx:key=""`|
| `wx:class` | `wx:class="{{something}}"` |
| `wx:style` | `wx:style="{{something}}"` |


<br />

| Prefix | HTML Snippet Content |
| ------ | ------------ |
| `coverImage` | `<cover-image></cover-image>`|
| `coverView` | `<cover-view></cover-view>`|
| `matchMedia` | `<match-media></match-media>`|
| `movableArea` | `<movable-area></movable-area`|
| `movableView` | `<movable-view></movable-view`|
| `scrollView` | `<scroll-view></scroll-view`|
| `swiper` | `<swiper></swiper>`|
| `swiperItem` | `<swiper-item></swiper-item>`|
| `view` | `<view></view>`|
| `icon` | `<icon></icon>`|
| `progress` | `<progress></progress>`|
| `richText` | `<rich-text></rich-text>`|
| `text` | `<text></text>`|
| `button` | `<button></button>`|
| `checkbox` | `<checkbox></checkbox>`|
| `checkboxGroup` | `<checkbox-group></checkbox-group>`|
| `editor` | `<editor></editor>`|
| `form` | `<form></form>`|
| `input` | `<input></input>`|
| `label` | `<label></label>`|
| `picker` | `<picker></picker>`|
| `pickerView` | `<picker-view></picker-view>`|
| `pickerViewColumn` | `<picker-view-column></picker-view-column>`|
| `radio` | `<radio></radio>`|
| `radio-group` | `<radio-group></radio-group>`|
| `slider` | `<slider></slider>`|
| `switch` | `<switch></switch>`|
| `functionalPageNavigator` | `<functional-page-navigator></functional-page-navigator>`|
| `navigator` | `<navigator></navigator>`|
| `audio` | `<audio></audio>`|
| `camera` | `<camera></camera>`|
| `image` | `<image></image>`|
| `livePlayer` | `<live-player></live-player>`|
| `livePusher` | `<live-pusher></live-pusher>`|
| `video` | `<video></video>`|
| `voip-room` | `<voip-room></voip-room>`|
| `map` | `<map></map>`|
| `canvas` | `<canvas></canvas>`|
| `ad` | `<ad></ad>`|
| `officialAccount` | `<official-account></official-account>`|
| `openData` | `<open-data></open-data>`|
| `webView` | `<web-view></web-view>`|
| `navigationBar"` | `<navigation-bar"></navigation-bar">`|
| `pageMeta` | `<page-meta></page-meta>`|
| `progress` | `<progress></progress>`|
| `pages` | `pages: []` |

<br />

| Prefix | Store Snippet Content |
| ------ | ------------ |
| `mpxCreateStore` | `const store = mpx.createStore({})` |


### Supported languages
* MPX(.mpx)
* javascript(.js)
* typescript(.ts)

### Base on
[vue-syntax-highlight (vue.tmLanguage)](https://github.com/vuejs/vue-syntax-highlight/blob/master/vue.tmLanguage)

##### 2020/07/18 (0.0.1)
* Add code snippets
* Add syntax highlight
