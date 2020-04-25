# html-i18n-cli

> HTML 国际化工具

## 安装

``` sh
npm i -g html-i18n-cli
```

## 使用

1. 生成 texts 文件

``` sh
html parse input.html
```

2. 翻译 texts 文件

> 输入两次 Ctrl + C 终止，机翻后可手动校对

``` sh
html translate texts.json
```

3. 还原 html 文件

``` sh
html render input.html texts.json
```