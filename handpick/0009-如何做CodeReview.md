# 前端精选#9 如何做 Code Review

欢迎来到《前端精选》，这里记录有趣的见闻，每周一发布。

# 封面

![](../assets/北京环球影城.jpg)
<p align=center>北京环球影城</p>

# 话题

**如何做 Code Review**

组内严抓 Code Review，一小朋友问，如何做 Code Review？我稍微思考，说：主要有3个方面，一是看自己修改的地方是否符合预期，因为合码冲突时很容易有修改；二是看明显笔误、格式问题或不理解的地方，需要指出立即改正；三是写法、用法、接口字段等前后不一致或有隐患的地方，需记录下来排期跟进。

你有哪些 Code Review 的思考，欢迎留言讨论。

# 见闻

1. [免费编程书](https://ebookfoundation.github.io/free-programming-books-search/?&sect=books&file=free-programming-books-zh.md)

这个网站收集了很多编程电子书和文章，既有编程语言相关的，也有无关的，涵盖计算机方方面面，推荐收藏。

2. [MisterDa - JavaScript 练习](https://www.misterda.com/)

这个网站提供了很多 JavaScript 练习题，有解析和答案，另外还有一些不错的文章，不过该网站有部分内容需付费。

3. [remotion - 以编程的方式做视频](https://www.remotion.dev/)

这是一个有趣的工具，能让你使用 JavaScript 和 React 来制作视频，如同写 Web 那样写组件，然后组装起来导出视频，值得一提的是，该项目还包含一个 [悬赏计划](https://www.remotion.dev/docs/contributing/bounty)，提交特定需求的 PR，通过后就能获得奖金。

4. [craft.js - 低代码编辑器](https://craft.js.org/)

本项目是一个支持拖拽生成页面的低代码编辑器，如果有类似需求，可以考虑参考或二次开发，另外对低代码感兴趣的也可以借此学习一下。

5. [react-hook-form - 表单校验库](https://react-hook-form.com/)

这是一个方便表单校验的 JavaScript 库，利用它可以在已有表单上，统一添加和处理校验逻辑，且无需引入封装过的表单组件（比如 antd 中的 Form 组件）。

6. [react-markdown - markdown 渲染组件](https://github.com/remarkjs/react-markdown)

这是一个 markdown 渲染组件，展示风格类似 Github，使用简单，支持插件扩展，适用于在项目里轻量引入。

7. [nice-modal-react - 模态框管理工具](https://github.com/eBay/nice-modal-react)

这个工具能将模特框统一管理，支持将模态框的使用由声明式变为命令式，这样像 visible 等模态框固有属性就不必散落在业务代码中，提供了一种很不错的写模态框方式。

7. [css-content](https://css-tricks.com/css-content/)

本文介绍了伪类的 content 属性用法，它可以是普通字符、特殊字符、以及 attr 属性，最后还介绍了一下伪类的巧妙用途，比如用来做 tooltip。

9. [命名不必那么难](https://classnames.paulrobertlloyd.com/)

该网站收集了一写常用场景下的命名单词举例，如果你感觉时常命名困难，不妨来这里找找灵感。

10. [使用 intl segmenter api 分词](https://polypane.app/blog/using-the-intl-segmenter-api/)

本文介绍了如何利用 intl segmenter api 进行字符串分词，支持多语言，这意味着前端能用原生方法做分词相关的工作了！目前仅 Firefox、IE 不支持，期待完善。
