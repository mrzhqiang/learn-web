学习前端
=======

这个仓库旨在以初学者的身份，学习前端开发的基础知识，以及如何使用前端领域的优秀框架。

---

## 前言

如果你是从零开始学习如何搭建一个网站，你适合阅读本仓库。

如果你只是想了解前端开发的相关知识，在如今的互联网上，有着大量优秀的知识站点，它们绝对比本仓库专业且友好，因此你更适合去阅读它们。

比如这些中文站点：

- [菜鸟教程](https://www.runoob.com/)
- [Mozilla Web 入门](https://developer.mozilla.org/zh-CN/docs/Learn/Getting_started_with_the_web)
- [W3Schools](https://www.w3schools.cn/)

如果你确认适合阅读本仓库，那么请继续，否则你应该转到上面的站点，去探索更专业的内容。

## 目录

- [ ] [HTML](./html)
- [ ] [CSS](./css)
- [ ] [JavaScript](./javascript)
- [ ] [Framework](./framework)
    - [ ] [Angular](./framework/angular)
    - [ ] [React](./framework/react)
    - [ ] [Vue](./framework/vue)

## 前端是什么？

个人认为，前端是面向用户的视觉艺术。

而 `Bito AI` 的回答是：
> 前端通常指的是 Web 前端开发，是指在网站制作过程中，负责制作页面前端效果的一种开发方式。具体来说，包括网页的制作、实现交互效果、实现前端业务逻辑等工作。前端开发通常需要掌握
> HTML、CSS、JavaScript 等技术，以及常用的前端框架和工具。

*漫谈：假如将创建网站比喻成搭建房子，那么用于定义网页结构的 `HTML` 就像砖块，可以构建稳定的房屋结构，而用于网页样式的 `CSS`
则类似墙漆，可以让你的房子多姿多彩，用于网页交互和动态效果的 `JavaScript`
就像家具，虽然这并不完全准确，但足以让你的房子变得生动起来。*

## 如何学习前端？

学习前端，可以从以下几个步骤开始：

1. 掌握 `HTML`、`CSS`、`JavaScript` 等基本技术：`HTML` 用于网页结构，`CSS` 用于网页样式，`JavaScript` 用于网页交互和动态效果。
2. 学习常用的前端框架和工具：比如 `Angular`、`React`、`Vue` 等框架，以及 `Visual Studio Code`、`WebStorm` 等工具。
3. 实战练习：通过运用基础技术和工具进行实战练习，来加深对前端开发的理解。
4. 关注前端技术进展：前端技术在不断发展，需要时刻关注前沿技术，不断学习提高自己的水平。

总之，前端开发需要不断地学习和实践，通过不断的积累和进步，才能成为优秀的前端开发人员。

## 准备工作

在学习前端之前，你需要有一定的准备，比如：开发工具、目标计划、源码管理等。

### 开发工具

你需要准备以下开发工具，注意，如果是【可选】的选项，则表示你可以跳过它们。

- **个人电脑**：最好是笔记本电脑，台式机也没问题。
- **编辑器**：[Sublime Text](https://www.sublimetext.com/)、[Visual Studio Code](https://code.visualstudio.com/)
  文本编辑器或者稍微重量级的 [WebStorm](https://www.jetbrains.com/webstorm/) 代码编辑器。
- **浏览器**：用来测试你编辑好的代码。常用的是：[Chrome](https://www.google.cn/intl/zh-CN/chrome/)
  、[Microsoft Edge](https://www.microsoft.com/zh-cn/edge)、[Firefox](https://www.mozilla.org/zh-CN/firefox/)
  、[Opera](https://www.opera.com/zh-cn)、[Safari](https://www.apple.com.cn/safari/)
  这些，但请注意，[Internet Explorer](https://windows.microsoft.com/en-us/internet-explorer/download-ie)
  已经退出历史舞台，大部分情况下，你无需关注到它。
- **【可选】图形编辑器**：用来制作图像，如果你需要的话。比如：[Photoshop](https://www.adobe.com/products/photoshop.html) 软件。另外，很多
  AI 网站也支持使用文本描述进行绘画，比如：[6pen](https://6pen.art/) 网站。
- **【可选】代码版本控制系统**：用来管理服务器文件，与团队合作开发项目，共享代码和资源，避免冲突。当前， [git](https://git-scm.com/)
  是最流行的版本控制系统。另外，你也可以在开源社区 [github](https://github.com/)
  找到更丰富的学习资源。如果你想拥有私人的可视化版本控制系统，你可以从 [gitlab](https://gitlab.com/) 找到解决方案。
- **【可选】自动化构建工具**：如果你需要的话，你可以选择 [webpack](https://webpack.js.org/)、[Grunt](https://gruntjs.com/)
  、[Gulp](https://gulpjs.com/) 这些工具，但请注意，作为初学者，应该将关注点放在基础知识的探索之上，工具只是一种提升效率的方式。
- **【可选】库、框架**：当我们拥有一定的经验之后，就不必再重复造轮子，因此我们可以选择一些常用库和框架，来帮助我们更快、更好地搭建网站。但前提是，你的基础知识足够扎实，否则当你遇到问题时，你将束手无策，甚至产生挫败感，不再有动力学习。
- **【可选】本地 `Web` 服务器**：事实上，简单的前端代码可以直接在浏览器中打开，以进行预览。如果是比较复杂的前端代码，比如具备异步请求的网站，则需要 `Web` 服务器来支持运行。这方面的内容，建议初学者自行搜索或跳过，等具有一定的开发经验之后，再来探讨。对于有兴趣的同学，也可以试着在 `Windows 7+`
   系统上开启 `IIS` 功能，`Linux` 系统和 `Mac` 系统应该天然支持 `Web` 服务器，即使没有，也可以通过命令下载 `Nginx`
   或者 `Node.js` 以充当本地 `Web` 服务器。

### 目标计划

有目标的学习，才最有效率。

你可以列一个你比较感兴趣的计划，比如你想创建一个新闻站点、黄页、广告牌，甚至后台管理系统、电子商城都可以。

当你有了初步的想法，你就可以进一步构思，比如：网站的主题、内容、风格等等。

你可以用画图工具，或者纸和笔，绘制一个简单的草图，它不需要精湛的绘画功底，只要能够展示你的想法即可。

接下来，你可以开始组织网站的内容，包括但不限于文本、色彩、图像、字体甚至视频等等。

当你做好这一切，你在编写网站源代码的时候，就可以游刃有余，从容不迫。

### 管理源码

你应该简单了解一下，如何管理你的网站源码。

你需要思考，你的源代码是放在个人电脑上，一旦你忘记携带，就无法展示你的劳动成果。

还是放在某个托管服务器上，只要可以访问网络，就随时可以下载源码并运行。

另外，你还要知道，你所使用的计算机系统，文件名大小写是否敏感，文件名是否支持空格。正常情况下，我们建议始终使用小写字母，如果需要多个单词组合命名，则使用 `-`
连字符连接每个单词，并且永远不使用空格来命名文件。

你的项目命名应该具有特色，比如新闻站点文件夹，可以命名为 `my-news`，当然这只是千千万万种方式中的一种，你应该在遵循规范的前提下，保持你个人风格的命名。

当项目文件夹命名完成，就可以开始着手建立项目结构，比如：

- 入口文件：`index.html`——这个文件一般会包含主页内容，也就是人们第一次进入网站时看到的文字和图片。
- 图像资源文件夹：`/imgs`——这个文件夹包含网站上使用的所有图片。
- 样式资源文件夹：`/css`——这个文件夹包含用于设置内容样式的 CSS 代码（例如，设置文本和背景颜色）。
- 脚本资源文件夹：`/js`——这个文件夹包含所有用于向网站添加交互功能的 JavaScript 代码（例如，点击时加载数据的按钮）。

现在的项目结构如下：

```
|--my-news/..
|--my-news/css/some.css
|--my-news/imgs/one.jpg
|--my-news/js/like.js
|--my-news/index.html
```

**注意：以上只是简单的源码结构，在后面你可以进行更深入了解，因此无需担心记不住。**

## 声明

本仓库仅供学习交流使用，所用素材皆来自网上，如有侵权，联系必删。
