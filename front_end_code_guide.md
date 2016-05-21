# 青春在线前端代码规范

> 部分内容参考 Google 和腾讯 AlloyTeam 的前端代码规范

## 总规范

1. 忽略协议：如 `<a href="http://www.youthol.cn">青春在线</a>` 应写为 `<a href="//www.youthol.cn">青春在线</a>` ；
2. 缩进使用 soft tab （4个空格）；
3. 命名如无特别要求，均使用小写字母；

## HTML

1. 使用 HTML 5 DOCTYPE，注意 DOCTYPE 为大写，html 为小写，如：`<!DOCTYPE html>` ；

2. 在属性上使用双引号，不要使用单引号；

3. 不要在自动闭合标签结尾使用斜线，如：`<input type="text" />` 应写为 `<input type="text">` ；

4. html 标签上加上 lang 属性，简体中文为 `zh-CN` ；

5. 加上字符编码的 meta 标签，如无特别要求，均为 `UTF-8` ；

6. 加上下面这个 meta 标签，让页面优先使用 Chrome 或最高版本 IE 内核进行渲染；

   ```html
   <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
   ```

   ​

   ​