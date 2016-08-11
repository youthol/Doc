# 青春在线前端代码规范

> 部分内容参考 Google 和腾讯 AlloyTeam 的前端代码规范

[Code Guide by @AlloyTeam](http://alloyteam.github.io/CodeGuide)

## 总规范

> 坚持制定好的代码规范，无论团队人数多少，代码应该同出一门！

* 忽略协议：如 `<a href="http://www.youthol.cn">青春在线</a>` 应写为 `<a href="//www.youthol.cn">青春在线</a>` ；
* 缩进使用 soft tab （4个空格）；
* 命名如无特别要求，均使用小写字母；

## HTML

* 使用 HTML 5 DOCTYPE，注意 DOCTYPE 为大写，html 为小写，如：`<!DOCTYPE html>` ；
* 在属性上使用双引号，不要使用单引号；
* 不要在自动闭合标签结尾使用斜线，如：`<input type="text" />` 应写为 `<input type="text">` ；
* html 标签上加上 lang 属性，简体中文为 `zh-CN` ；
* 加上字符编码的 meta 标签，如无特别要求，均为 `UTF-8` ；
* 加上下面这个 meta 标签，让页面优先使用 Chrome 或最高版本 IE 内核进行渲染；

   ```html
   <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
   ```

## CSS

* 0 后面不要加单位，如 `0px` 写为 `0` ；
* 小数点前不要加 0，如 `0.7em` 写为 `.7em` ；
* 16 进制尽量使用 3 位来表示，如 `#ffffff` 写为 `#fff` ；
* id 和 class 命名使用小写，连接符使用 `-` ，可适当加上项目名为前缀；
* 属性尽量使用简写，如 `margin` 和 `background` 等；
* 属性后的冒号与值之间使用一个空格隔开；
* 每个选择符及每个属性声明单独使用以后，`{` 前与选择符使用一个空格隔开，如：
 ```html
 html,
body {
        margin: 0;
        padding: 0;
}
```

## JavaScript

* 单行注释双斜线后加一个空格
* 标准变量命名采用驼峰式命名
* 无论是函数声明还是函数表达式，'('前不要空格，但'{'前一定要有空格

   ​

   ​