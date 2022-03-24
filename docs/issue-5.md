# 好工具周刊（第 5 期）: 用 RSS 订阅竹白的 3 个方法 / 竹白转 RSS, imgggg, Screely, Kill the Newsletter!

发现并分享有趣，有创意，免费、好用的工具，每周四发布。由 [BestXTools](https://www.bestxtools.com/) 创作。

---

[上一期内容](https://github.com/bestxtools/weekly-cn/blob/main/docs/issue-4.md) | [往期内容](https://github.com/bestxtools/weekly-cn) | [RSS 订阅](https://discuss-cn.bestxtools.com/t/weekly) | [邮箱订阅](https://bestxtools.zhubai.love/) | [微信订阅](https://discuss-cn.bestxtools.com/d/5/2) | [工具推荐](https://discuss-cn.bestxtools.com/d/8) | [评论](https://discuss-cn.bestxtools.com/d/13)

---

## 用 RSS 订阅竹白的 3 个方法 / 竹白转 RSS

最近发现很多在[竹白](https://zhubai.love/)上写周刊的，包括现在这个也是[竹白周刊](https://bestxtools.zhubai.love/)。

竹白目前支持邮箱订阅和微信订阅两种方式，暂时还不支持 RSS 订阅。从一些论坛的留言可以看出，有些读者是希望通过 RSS 订阅的。

这里将介绍 3 个可以用 RSS 订阅竹白的方法。

方法 1：一些竹白上的周刊，创作者自己会另外搭建一个网站，提供 RSS。在每期的内容里，一般能找到 RSS 源的链接。

举例：

- [好工具周刊](https://bestxtools.zhubai.love/)
  - 竹白: <https://bestxtools.zhubai.love/>
  - 网站 1: <https://discuss-cn.bestxtools.com/>
  - 网站 2: <https://github.com/bestxtools/weekly-cn>
  - RSS: <https://discuss-cn.bestxtools.com/atom/t/weekly/discussions>
- [DecoHack 周刊](https://decohack.zhubai.love/)
  - 竹白: <https://decohack.zhubai.love/>
  - 网站: <https://www.decohack.com/>
  - RSS: <https://www.decohack.com/feed>
- [GeekPlux Lab](https://geekplux.zhubai.love/)
  - 竹白: <https://geekplux.zhubai.love/>
  - 网站: <https://geekplux.com/newsletters>
  - RSS: <https://geekplux.com/feed.xml>

方法 2：使用 [RSSHub](https://docs.rsshub.app/blog.html#zhu-bai) 提供的路由，获得竹白周刊 RSS 源地址。

举例: <https://rsshub.app/zhubai/bestxtools>

路由: `/zhubai/:id`

参数:

- id, 必选 - `id` 为竹白主页 url 中的三级域名，如 [bestxtools.zhubai.love](https://bestxtools.zhubai.love/) 的 `id` 为 `bestxtools`

> **提示**
>
> 1. 在路由末尾处加上 `?limit=限制获取数目` 来限制获取条目数量，默认值为 `20`

> 2. 这个 RSS 源不支持全文输出。

方法 3：使用 [Kill the Newsletter!](https://kill-the-newsletter.com/) 服务，把竹白 newsletter 转成 RSS。

**使用方法**

1. 打开 <https://kill-the-newsletter.com/> ，输入 Newsletter 的名字(比如：[好工具周刊](https://bestxtools.zhubai.love/))，然后点击 `Create Inbox`
2. 然后你会看到它提供给你的用来订阅的邮箱地址和 RSS 订阅源地址
3. 将邮箱地址输入到你要订阅的 newsletter 网站（[竹白周刊网站](https://bestxtools.zhubai.love/)）里
4. 将 RSS 订阅源地址添加到你的 RSS 阅读器里
5. 一般情况下，RSS 阅读器里收到的第一个订阅消息是叫你确认订阅或验证邮箱的内容，点击确认地址即可。下一期内容开始会出现在 RSS feed 里。

到这里 3 种通过 RSS 订阅竹白的方法讲完了。如果你知道其他方便有效的方法，请在[评论](https://discuss-cn.bestxtools.com/d/13/3)里分享出来。

## 🔧 在线工具

### [imgggg | Capture and share anything as image](https://imgg.gg/)

将**链接**转换为精美的分享图片的小工具，以图片的方式截取并分享万物。

支持 [Twitter](https://twitter.com/), [Hacker News](https://news.ycombinator.com/), [Instagram](https://www.instagram.com/), [GitHub](https://github.com/) 代码，Issues, [V2EX](https://www.v2ex.com/), 即刻等平台上的内容。

链接: [https://imgg.gg/](https://imgg.gg/)

![imgggg | Capture and share anything as image](https://cdn.jsdelivr.net/gh/bestxtools/weekly-cn@main/images/2022-03-01-14-59-38.png)

### [Screely](https://www.screely.com/)

一款简单的截图美化工具。

链接: [https://www.screely.com/](https://www.screely.com/)

![carbon](https://cdn.jsdelivr.net/gh/bestxtools/weekly-cn@main/images/2022-02-22-15-27-04.png)

类似工具:

- [Pika: 屏幕截图美化工具](https://pika.style/)

### [Kill the Newsletter!](https://kill-the-newsletter.com/)

上面竹白转 RSS 提到的工具。这是一个开源服务，可以将新闻邮件（Newsletter），转为 RSS feed 输出。用户可以自己架设服务。

链接: [https://kill-the-newsletter.com/](https://kill-the-newsletter.com/)

源码: [https://github.com/leafac/kill-the-newsletter](https://github.com/leafac/kill-the-newsletter)

![Kill the Newsletter!](https://cdn.jsdelivr.net/gh/bestxtools/weekly-cn@main/images/2022-03-23-15-50-46.png)

### [follow.it](https://follow.it/enter-website)

与 [Kill the Newsletter!](https://kill-the-newsletter.com/) 相反的工具，以 Newsletter 的形式订阅任意 RSS 的服务。

链接: [https://follow.it/enter-website](https://follow.it/enter-website)

![follow.it](https://cdn.jsdelivr.net/gh/bestxtools/weekly-cn@main/images/2022-03-23-16-26-46.png)

### [View Source](https://neatnik.net/view-source/)

可以在手机查看网页源码的工具。

链接: [https://neatnik.net/view-source/](https://neatnik.net/view-source/)

![View Source](https://cdn.jsdelivr.net/gh/bestxtools/weekly-cn@main/images/2022-02-21-16-31-04.png)

### [Magic Eraser](https://www.magiceraser.io/)

使用人工智能技术从图片中删除你不需要的东西，100%免费，无需注册！

链接: [https://www.magiceraser.io/](https://www.magiceraser.io/)

![Magic Eraser](https://www.magiceraser.io/magic-eraser-demo-food-on-plate.gif)
![Magic Eraser](https://www.magiceraser.io/magic-eraser-demo-car-and-pedestrian-crossing.gif)

### [Yandex 图片在线翻译器](https://translate.yandex.com/ocr)

这个工具可以将图片上的文本内容进行识别并翻译成各种语言。

链接: [https://translate.yandex.com/ocr](https://translate.yandex.com/ocr)

![Yandex图片在线翻译器](https://cdn.jsdelivr.net/gh/bestxtools/weekly-cn@main/images/2022-02-21-17-56-46.png)

## 📖 文章

- [Notion 优质资源汇总 - 少数派](https://sspai.com/post/71893)

[![Notion 优质资源汇总 - 少数派](https://cdn.jsdelivr.net/gh/bestxtools/weekly-cn@main/images/2022-03-23-16-26-48.png)](https://sspai.com/post/71893)

- [科技爱好者周刊（第 199 期）：俄罗斯的 HTTPS 证书问题](https://www.ruanyifeng.com/blog/2022/03/weekly-issue-199.html)

[![科技爱好者周刊（第 199 期）：俄罗斯的 HTTPS 证书问题](https://cdn.jsdelivr.net/gh/bestxtools/weekly-cn@main/images/2022-03-23-16-26-47.png)](https://www.ruanyifeng.com/blog/2022/03/weekly-issue-199.html)

- [Product Hunt Weekly Digest - March 19th, 2022](https://www.producthunt.com/newsletter/10324-move-over-tesla)
  - 本周第一：[Amie - The joyful productivity app](https://www.producthunt.com/posts/amie-4)
  - 本周第二：[Hints - Valuable info is quickly captured and self-organized](https://www.producthunt.com/posts/hints)
  - 本周第三：[Avvvatars - Open source React unique UI avatar library](https://www.producthunt.com/posts/avvvatars)

## 📧 周刊推荐

### [TNT-Weekly](https://github.com/tnfe/TNT-Weekly)

前端行业发展飞速，新技术如雨后春笋般快速出现，尤其是各种小程序陆续推出，相关的信息、文章也铺天盖地的遍布在各处，我们有时候会困惑，不知道哪些信息对于自己是有价值的，那么 TNFE 团队启动了这个周刊项目，为所有的前端开发人员整理出小程序相关以及其它 web 前端技术领域的精品内容。

🐝 我们坚持每周为你提供高质量的关于小程序、h5 等前端领域的文章和项目 ✨。

> 链接: <https://github.com/tnfe/TNT-Weekly>

[![TNT-Weekly](https://raw.githubusercontent.com/Tnfe/TNFE-Weekly/master/assets/weekly-banner.jpg)](https://github.com/tnfe/TNT-Weekly)

#### 近期文章

- 第一百二十八期

  1. [LowCodeEngine-一套面向扩展设计的企业级低代码技术体系](https://github.com/alibaba/lowcode-engine)
  2. [Windi CSS-下一代实用程序优先的 CSS 框架](https://github.com/windicss/windicss)
  3. [阿里 & 蚂蚁自研 IDE 研发框架 OpenSumi 正式开源](https://segmentfault.com/a/1190000041527234)
  4. [Zerker-一个轻量级且功能强大的 Flutter 图形动画库](https://github.com/flutterkit/zerker)
  5. [🎥 Create videos programmatically in React](https://github.com/remotion-dev/remotion)
  6. [What are wrapper objects for primitive values?](https://2ality.com/2022/02/wrapper-objects.html)
  7. [A Proposal For Type Syntax in JavaScript](https://devblogs.microsoft.com/typescript/a-proposal-for-type-syntax-in-javascript/)
  8. [ReScript on Deno: Declarative Command Line Tools](https://practicalrescript.com/rescript-on-deno-declarative-command-line-tools/)

## 🧰 [优秀工具箱大全](https://awesome-toolbox-chinese.bestxtools.com/)

很多程序员都喜欢做一个工具箱。平时也会经常用到各种工具。这里收集了一些国内外好用的工具箱。

链接: [https://github.com/bestxtools/awesome-toolbox-chinese](https://github.com/bestxtools/awesome-toolbox-chinese)

欢迎[点赞](https://github.com/bestxtools/awesome-toolbox-chinese)，收藏，[投稿](https://github.com/bestxtools/awesome-toolbox-chinese/issues)。

## 🔧 工具推荐

如果你有什么好玩的工具，可以是你做的或知道的，欢迎推荐。

要求：

- 在线工具
- 免费
- 无需注册

推荐方式：

- [BestXTools](https://discuss-cn.bestxtools.com/d/8) - <https://discuss-cn.bestxtools.com/d/8>
- [GitHub](https://github.com/bestxtools/weekly-cn/issues) - <https://github.com/bestxtools/weekly-cn/issues>
- [V2EX](https://v2ex.com/t/836201?r=BestXTools) - <https://v2ex.com/t/836201?r=BestXTools>

---

以上，便是本期全部内容。感谢你阅读到这里，下期见！

好工具周刊同时发布到三个平台，订阅方式提供多种选择。

- [BestXTools 社区（RSS）](https://discuss-cn.bestxtools.com/t/weekly)
- [GitHub（Watch）](https://github.com/bestxtools/weekly-cn)
- [竹白（邮箱，微信）](https://bestxtools.zhubai.love/)

欢迎交流，投稿，订阅。

---

[上一期内容](https://github.com/bestxtools/weekly-cn/blob/main/docs/issue-4.md) | [往期内容](https://github.com/bestxtools/weekly-cn) | [RSS 订阅](https://discuss-cn.bestxtools.com/t/weekly) | [邮箱订阅](https://bestxtools.zhubai.love/) | [微信订阅](https://discuss-cn.bestxtools.com/d/5/2) | [工具推荐](https://discuss-cn.bestxtools.com/d/8) | [评论](https://discuss-cn.bestxtools.com/d/13)

---

<div style="display: flex;justify-content: center;"><img width="300" src="https://cdn.jsdelivr.net/gh/bestxtools/weekly-cn@main/images/2022-03-02-16-19-29.png"></div>
