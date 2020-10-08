# Hexo Butterfly Snippets

修改自 @KakaWanYifan/VSCode-Hexo-Butterfly-Snippets，增加了对 CheckBox & Radio 的支持。

## 用法

### 补全

敲入`>`，然后会有提示，自动补全。

### 新功能

`checkbox` `plus` `minus` `times` `radio` `strong`

默认为 checked 状态。
  
### 功能

- `>default`: Insert Default.
- `>primary`: Insert Primary.
- `>primary-no-icon`: Insert Primary No-Icon.
- `>success`: Insert Success.
- `>info`: Insert Info.
- `>warning`: Insert Warning.
- `>danger`: Insert Danger.
- `>mermaid`: Insert Mermaid.
- `>tabs`: Insert Tabs.
- `>tabs_tensorflow`: Insert Tabs TensorFlow.

### 自定义功能

修改`/snippets/markdown.json`，然后重新打包。

## 打包

clone源代码，安装插件`vsce`。

```
git clone https://github.com/SerokSSR/VSCode-Hexo-Butterfly-Snippets
npm i vsce -g
vsce package
```

## 要求

`Visual Code`版本不低于 `1.41.0`

## LICENSE

MIT LICENSE.