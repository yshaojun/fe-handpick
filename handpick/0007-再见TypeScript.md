# 前端精选#6 再见 TypeScript?

欢迎来到《前端精选》，这里记录有趣的见闻，每周一发布。

# 封面

![](../assets/北京奥林匹克塔.jpg)
<p align=center>北京奥林匹克塔</p>

# 话题

**再见 TypeScript?**

著名项目 Deno、Svelte、Turbo 先后放弃 TypeScript 转回 JavaScript，在社区引起了广泛讨论，从我的角度，也不太喜欢 TypeScript。比如，我曾见过类型声明行数远超实际功能的代码、string 到联合类型转换为了简洁不得不写 as any、以及因配置问题出现的类型报错等，在迭代频繁的项目中，很多常常变化的、深层嵌套的数据，也更多用 “any 加注释”的方式去做。

在实践中，往往简单逻辑用具体类型，复杂逻辑则用 any，前者出错率低，TypeScript 提升很小，后者出错高，但 TypeScript 帮不上忙，总体反而不如 JavaScript 简洁高效。你有哪些 TypeScript 的思考，欢迎留言讨论。

# 见闻

1. [Turbo 8 放弃 TypeScript](https://world.hey.com/dhh/turbo-8-is-dropping-typescript-70165c01)

著名开发者 DDH 宣布 Turbo 8 放弃 TypeScript，本文表达了他的看法，直言不讳的透露他对 JavaScript 的喜爱以及对放弃 TypeScript 的欣喜。

2. [type-challenges - TypeScript 类型挑战收集](https://github.com/type-challenges/type-challenges)

“众所周知，TypeScript 的类型系统是图灵完备的”，这个仓库收录了很多利用 TypeScript 类型系统去实现的有趣功能，并包含答案和题解，非常有意思。

3. [MDXEditor - Markdown 富文本编辑器](https://mdxeditor.dev/)

这是一个富文本编辑器，所不同的是，它的输出是 Markdown 文件。

4. [create-chrome-ext - Chrome 插件脚手架](https://github.com/guocaoyi/create-chrome-ext)

这是一个 Chrome 插件脚手架合集，提供了多种多样的插件模板，插件开发者可以从这个模板库里挑选适当的，快速上手。

5. [用 CSS 遮罩动画展示图片](https://www.smashingmagazine.com/2023/09/revealing-images-css-mask-animations/)

这是一个使用纯 CSS 实现的展示图片的动效，主要用到 mask 属性，文中展示了多种动效的技巧和代码。

![](https://p1-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/a290abf08d874747ba1cd45dd1b430a4~tplv-k3u1fbpfcp-jj-mark:0:0:0:0:q75.image)

6. [用 linear 函数创建自定义缓动效果](https://developer.mozilla.org/en-US/blog/custom-easing-in-css-with-linear/)

本文详细介绍了 CSS linear() 函数的用法，提供了用此实现的多种自定义缓动效果。

7. [使用纯 JavaScript 实现响应模式](https://frontendmasters.com/blog/vanilla-javascript-reactivity/#reactive-rendering-of-ui)

本文介绍了如何用纯 JavaScript 实现多种响应模式，包括发布/订阅、观察者、使用 Proxy 实现属性响应、响应式系统和响应式 UI。

8. [用优先级提示控制网络活动](https://www.macarthur.me/posts/priority-hints)

本文介绍了如何显示提示浏览器网络优先级，包含以下4种情况：预加载资源、fetch、img 和 script。

9. [为什么 every 函数返回对空数组 true](https://humanwhocodes.com/blog/2023/09/javascript-wtf-why-does-every-return-true-for-empty-array/)

本文探究了为什么 every 函数对空数组总是返回 true，最后总结出对该函数的理解应该是：数组里是否有元素不满足条件。

10. [ViteConf 将在10月5-6日线上举办](https://viteconf.org/23/)

ViteConf 将在10月5、6日线上举办，届时尤雨溪将带来题为《The State of Vite》的分享，还有众多开发者演讲嘉宾，值得关注一下。
