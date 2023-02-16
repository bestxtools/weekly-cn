# [好工具周刊（第 47 期）: 我最喜欢且常用的浏览器插件 - Vimium, AdBlock, uBlacklist, Tampermonkey, Stylus, MarkDownload, Google 翻译](https://github.com/bestxtools/weekly-cn/blob/main/docs/issue-47.md)

发现并分享有趣，有创意，免费、好用的工具，每周四发布。由 [BestXTools](https://www.bestxtools.com/) 创作。

---

[上一期内容](https://github.com/bestxtools/weekly-cn/blob/main/docs/issue-46.md) | [下一期内容](https://github.com/bestxtools/weekly-cn/blob/main/docs/issue-48.md) | [往期内容](https://github.com/bestxtools/weekly-cn) | [RSS 订阅](https://discuss-cn.bestxtools.com/t/weekly) | [邮箱订阅](https://bestxtools.zhubai.love/?subscribe=1) | [微信订阅](https://discuss-cn.bestxtools.com/d/5/2) | [工具推荐](https://discuss-cn.bestxtools.com/t/tools) | [评论](https://discuss-cn.bestxtools.com/d/125/2)

---

《好工具周刊》从发布[第一期](https://discuss-cn.bestxtools.com/d/6)（2022 年 2 月 24 日发布）到现在马上就满一年了，往期推荐的都是免费的在线工具。新的一年，打算开始同时推荐一些其他类型的工具。

本期内容为我最喜欢且常用的浏览器插件。如果你是程序员，估计本期内容提到的插件都会知道。如果你有什么特别好用的插件，或关于这些插件的使用心得，欢迎在[评论](https://discuss-cn.bestxtools.com/d/125/2)里留言。

---

## 🌈 浏览器插件

### [Vimium - The Hacker's Browser](https://links.bestxtools.com/vimium.github.io/)

每次安装新的浏览器之后，第一件事情就是安装 Vimium 插件。这个插件提供非常多的键盘快捷键，很多都是与 **Vim** 编辑器一脉相承的。我想程序员们大部分都知道并使用这个插件，建议非程序员们也试一试这个插件。

随时按下 `?` 键，即可查看使用帮助。

我最常用的操作：

```
?       Show help
gg      Scroll to the top of the page
G       Scroll to the bottom of the page
d       Scroll a half page down
u       Scroll a half page up
yy      Copy the current URL to the clipboard
F       Open a link in a new tab
a       Open a link in a new tab & switch to it (自定义)
O       Open URL, bookmark or history entry in a new tab
T       Search through your open tabs (同时打开几十个标签页，用它可以方便切换)
H       Go back in history
L       Go forward in history
```

欢迎在[评论区](https://discuss-cn.bestxtools.com/d/93)交流使用心得或问题。

官网链接: [https://vimium.github.io/](https://links.bestxtools.com/vimium.github.io/)

安装链接:

- [Chrome, Microsoft Edge](https://chrome.google.com/webstore/detail/vimium/dbepggeogbaibhgnhhndojpepiihcmeb)
- [Firefox: Vimium-FF](https://addons.mozilla.org/zh-CN/firefox/addon/vimium-ff/)

源码: [https://github.com/philc/vimium](https://links.bestxtools.com/github.com/philc/vimium)

![Vimium - The Hacker's Browser](https://raw.githubusercontent.com/bestxtools/s2/main/images/2023-02-08-23-21-01.png)
![Vimium - The Hacker's Browser](https://raw.githubusercontent.com/bestxtools/s2/main/images/2023-02-08-23-21-02.png)

🔍 [#shortcuts](https://links.bestxtools.com/www.google.com/search?q=site%3Adiscuss-cn.bestxtools.com+shortcuts) [#快捷键](https://links.bestxtools.com/www.google.com/search?q=site%3Adiscuss-cn.bestxtools.com+%E5%BF%AB%E6%8D%B7%E9%94%AE)

### [AdBlock](https://links.bestxtools.com/getadblock.com/zh_CN/)

网页中太多广告时，会非常影响浏览体验，安装一个屏蔽广告的插件还是有帮助的。

电脑上屏蔽广告，我一般采用三个方法。

1. 修改 `hosts` 文件，把显示广告相关的域名全部屏蔽掉
2. 安装一个屏蔽广告的浏览器插件，比如 AdBlock
3. 安装 Stylus 浏览器插件，使用 CSS 把广告隐藏掉 （后面再做介绍）

官网链接: [https://getadblock.com/zh_CN/](https://links.bestxtools.com/getadblock.com/zh_CN/)

安装链接:

- [Chrome](https://chrome.google.com/webstore/detail/adblock-%E2%80%94-best-ad-blocker/gighmmpiobklfepjocnamgkkbiglidom)
- [Microsoft Edge](https://microsoftedge.microsoft.com/addons/detail/adblock-%E2%80%94-best-ad-blocker/ndcileolkflehcjpmjnfbnaibdcgglog)
- [Firefox](https://addons.mozilla.org/zh-CN/firefox/addon/adblock-for-firefox/)

![AdBlock](https://raw.githubusercontent.com/bestxtools/s2/main/images/2023-02-08-23-50-01.png)
![AdBlock](https://raw.githubusercontent.com/bestxtools/s2/main/images/2023-02-08-23-50-02.png)

🔍 [#屏蔽广告](https://links.bestxtools.com/www.google.com/search?q=site%3Adiscuss-cn.bestxtools.com+%E5%B1%8F%E8%94%BD%E5%B9%BF%E5%91%8A)

### [uBlacklist](https://links.bestxtools.com/iorate.github.io/ublacklist/docs)

使用搜索引擎得到的结果，经常包含很多不喜欢的网站或内容农场的内容。使用这个插件可以自动隐藏这些网站的内容。支持 Google, Bing, DuckDuckGo 等很多搜索引擎。

屏蔽内容农场的规则可以订阅别人管理的规则。在 GitHub 搜索 [uBlacklist](https://github.com/search?q=ublacklist)，会找到很多。

官网链接: [https://iorate.github.io/ublacklist/docs](https://links.bestxtools.com/iorate.github.io/ublacklist/docs)

安装链接:

- [Chrome, Microsoft Edge](https://chrome.google.com/webstore/detail/ublacklist/pncfbmialoiaghdehhbnbhkkgmjanfhe)
- [Firefox](https://addons.mozilla.org/zh-CN/firefox/addon/ublacklist/)

源码: [https://github.com/iorate/ublacklist](https://links.bestxtools.com/github.com/iorate/ublacklist)

![uBlacklist](https://raw.githubusercontent.com/bestxtools/s2/main/images/2023-02-09-09-54-01.png)
![uBlacklist](https://raw.githubusercontent.com/bestxtools/s2/main/images/2023-02-09-09-54-02.png)
![uBlacklist](https://raw.githubusercontent.com/bestxtools/s2/main/images/2023-02-09-09-54-03.gif)

🔍 [#屏蔽内容农场](https://links.bestxtools.com/www.google.com/search?q=site%3Adiscuss-cn.bestxtools.com+%E5%B1%8F%E8%94%BD%E5%86%85%E5%AE%B9%E5%86%9C%E5%9C%BA) [#Block sites](https://links.bestxtools.com/www.google.com/search?q=site%3Adiscuss-cn.bestxtools.com+Block%20sites)

### [Tampermonkey (油猴)](https://links.bestxtools.com/www.tampermonkey.net/)

用户脚本是小型 JavaScript 程序，可用于向网页添加新功能或修改现有功能。使用这个插件，可以轻松在任何网站上创建、管理和运行这些用户脚本。写用户脚本比写浏览器扩展方便、容易很多。

官网链接: [https://www.tampermonkey.net/](https://links.bestxtools.com/www.tampermonkey.net/)

安装链接:

- [Chrome](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
- [Microsoft Edge](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd)
- [Firefox](https://addons.mozilla.org/zh-CN/firefox/addon/tampermonkey/)

![Tampermonkey (油猴)](https://raw.githubusercontent.com/bestxtools/s2/main/images/2023-02-09-10-15-01.png)
![Tampermonkey (油猴)](https://raw.githubusercontent.com/bestxtools/s2/main/images/2023-02-09-10-15-02.png)

🔍 [#用户脚本](https://links.bestxtools.com/www.google.com/search?q=site%3Adiscuss-cn.bestxtools.com+%E7%94%A8%E6%88%B7%E8%84%9A%E6%9C%AC) [#Userscripts](https://links.bestxtools.com/www.google.com/search?q=site%3Adiscuss-cn.bestxtools.com+Userscripts)

### [Stylus](https://links.bestxtools.com/add0n.com/stylus.html)

与用户脚本类似，Stylus 是一个调整网页外观的用户样式管理器。它可以让您轻松为许多热门网站安装主题和皮肤。这个插件比 Stylish 插件好用很多。

我用 Stylus 主要是隐藏一些不想看到的内容，比如广告、无关紧要的内容、搜索结果中一些网站的内容等。`:has` [这个 CSS 选择器](https://dto.pipecraft.net/search?q=%22CSS+Parent+Selector%22&what=stories&order=newest)非常有用。

例子:

```css
li:has(a[href*="csdn.net"]) {
  /* display: none !important; */
  opacity: 20%;
}
```

官网链接: [https://add0n.com/stylus.html](https://links.bestxtools.com/add0n.com/stylus.html)

安装链接:

- [Chrome, Microsoft Edge](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)
- [Firefox](https://addons.mozilla.org/zh-CN/firefox/addon/styl-us/)

源码: [https://github.com/openstyles/stylus](https://links.bestxtools.com/github.com/openstyles/stylus)

![Stylus](https://raw.githubusercontent.com/bestxtools/s2/main/images/2023-02-09-10-30-01.png)
![Stylus](https://raw.githubusercontent.com/bestxtools/s2/main/images/2023-02-09-10-30-02.png)

V2EX 使用自定义样式前
![Stylus](https://raw.githubusercontent.com/bestxtools/s2/main/images/2023-02-09-10-30-03.png)
V2EX 使用自定义样式后
![Stylus](https://raw.githubusercontent.com/bestxtools/s2/main/images/2023-02-09-10-30-04.png)

🔍 [#样式管理器](https://links.bestxtools.com/www.google.com/search?q=site%3Adiscuss-cn.bestxtools.com+%E6%A0%B7%E5%BC%8F%E7%AE%A1%E7%90%86%E5%99%A8) [#userstyles](https://links.bestxtools.com/www.google.com/search?q=site%3Adiscuss-cn.bestxtools.com+userstyles)

### [MarkDownload - Markdown Web Clipper](https://links.bestxtools.com/github.com/deathau/markdownload)

平时经常需要从网页中复制一些内容，包括文字和链接。过去是单独复制文字和链接，需要操作多次 Copy & Paste。安装这个插件以后，可以把网页内容以 Markdown 格式复制出来，变得非常方便、高效。

官网链接: [https://github.com/deathau/markdownload](https://links.bestxtools.com/github.com/deathau/markdownload)

安装链接:

- [Chrome](https://chrome.google.com/webstore/detail/markdownload-markdown-web/pcmpcfapbekmbjjkdalcgopdkipoggdi)
- [Microsoft Edge](https://microsoftedge.microsoft.com/addons/detail/markdownload-markdown-w/hajanaajapkhaabfcofdjgjnlgkdkknm)
- [Firefox](https://addons.mozilla.org/zh-CN/firefox/addon/markdownload/)

源码: [https://github.com/deathau/markdownload](https://links.bestxtools.com/github.com/deathau/markdownload)

![MarkDownload - Markdown Web Clipper](https://raw.githubusercontent.com/bestxtools/s2/main/images/2023-02-09-15-06-01.png)
![MarkDownload - Markdown Web Clipper](https://raw.githubusercontent.com/bestxtools/s2/main/images/2023-02-09-15-06-02.png)

🔍 [#Markdown Web Clipper](https://links.bestxtools.com/www.google.com/search?q=site%3Adiscuss-cn.bestxtools.com+Markdown%20Web%20Clipper)

### [Google 翻译](https://translate.google.com/)

翻译插件大部分人都会用。这个插件不算特别好用，毕竟是谷歌的翻译 API，凑合着用着。目前还没找到特别合适的翻译插件。打算今年做一个符合自己使用习惯的翻译插件。

安装链接:

- [Chrome, Microsoft Edge](https://chrome.google.com/webstore/detail/google-translate/aapbdbdomjkkjkaonfhkkikfgjllcleb)
- [Firefox](https://addons.mozilla.org/zh-CN/firefox/search/?q=google%20translate)

![Google 翻译](https://raw.githubusercontent.com/bestxtools/s2/main/images/2023-02-09-15-23-01.png)
![Google 翻译](https://raw.githubusercontent.com/bestxtools/s2/main/images/2023-02-09-15-23-02.png)

🔍 [#翻译](https://links.bestxtools.com/www.google.com/search?q=site%3Adiscuss-cn.bestxtools.com+%E7%BF%BB%E8%AF%91) [#translate](https://links.bestxtools.com/www.google.com/search?q=site%3Adiscuss-cn.bestxtools.com+translate)

---

## 🧰 [在线工具箱大全](https://awesome-toolbox-chinese.bestxtools.com/)

聚合了非常多的国内外优秀的在线工具箱，欢迎[点赞](https://github.com/bestxtools/awesome-toolbox-chinese)，收藏，[投稿](https://github.com/bestxtools/awesome-toolbox-chinese/issues)。

链接:

- [https://github.com/bestxtools/awesome-toolbox-chinese](https://github.com/bestxtools/awesome-toolbox-chinese)
- [https://😎🧰.bestxtools.com/](https://😎🧰.bestxtools.com/)

---

## 🌈 文章 & 资源分享

- **Product Hunt Golden Kitty Awards Winners 2022**  
   → [_producthunt.com_](https://www.producthunt.com/golden-kitty-awards/hall-of-fame)

- [**命令行的艺术**](https://dto.pipecraft.net/s/vzvmkx)  
   → [_github.com_](https://github.com/jlevy/the-art-of-command-line/blob/master/README-zh.md)

- [**半年历程两万周活 - Chrome 插件阶段总结**](https://dto.pipecraft.net/s/ilrxvb/chrome)  
   → [_toast.pub_](https://toast.pub/totoro/posts/peroidic-summary-on-washbaidu/)

- [**20 Things I've Learned in my 20 Years as a Software Engineer**](https://dto.pipecraft.net/s/4kypyz/20_things_i_ve_learned_my_20_years_as)  
   → [_simplethread.com_](https://www.simplethread.com/20-things-ive-learned-in-my-20-years-as-a-software-engineer/)

- [**Chromium 渲染流水线——字节码到像素的一生**](https://dto.pipecraft.net/s/2tr623/chromium)  
   → [_me.ursb.me_](https://me.ursb.me/archives/360.html)

- [**DTO Weekly Curations #4 - Side Project 指南 & 那些独立开发者都是怎么养活自己的？**](https://dto.pipecraft.net/s/wyrow2/dto_weekly_curations_4_side_project)  
   → [_tinyletter.com_](https://tinyletter.com/dto/letters/dto-weekly-curations-4-side-project)

更多文章推荐请访问 [**DTO** (Dev Topics Only)](https://dto.pipecraft.net/)。

### 🦞 About DTO

[**DTO**](https://dto.pipecraft.net/about) 是一个类似 [Hacker News](https://news.ycombinator.com/), [Lobsters](https://lobste.rs/) 的技术文章链接分享社区。

新开始了一个[《DTO 每周精选周刊》](https://tinyletter.com/dto)，发现并分享有价值的技术文章、资源，每周一发布。欢迎订阅。

---

## 🌈 工具推荐

如果你有什么好玩的工具，可以是你做的或知道的，欢迎推荐。

要求：

- 在线工具
- 免费
- 无需注册

推荐方式：

- [BestXTools](https://discuss-cn.bestxtools.com/d/8)
- [GitHub](https://github.com/bestxtools/weekly-cn/issues)

---

以上，便是本期全部内容。本期最喜欢的工具是哪一个，请在[评论区留言](https://discuss-cn.bestxtools.com/d/125/2)。感谢你阅读到这里，下期见！

好工具周刊同时发布到三个平台，订阅方式提供多种选择。

- [BestXTools 社区](https://discuss-cn.bestxtools.com/t/weekly) ([RSS](https://discuss-cn.bestxtools.com/atom/t/weekly/discussions))
- [GitHub（Watch）](https://github.com/bestxtools/weekly-cn)
- [竹白（邮箱，微信）](https://bestxtools.zhubai.love/?subscribe=1)

欢迎交流，投稿，订阅。

---

[上一期内容](https://github.com/bestxtools/weekly-cn/blob/main/docs/issue-46.md) | [下一期内容](https://github.com/bestxtools/weekly-cn/blob/main/docs/issue-48.md) | [往期内容](https://github.com/bestxtools/weekly-cn) | [RSS 订阅](https://discuss-cn.bestxtools.com/t/weekly) | [邮箱订阅](https://bestxtools.zhubai.love/?subscribe=1) | [微信订阅](https://discuss-cn.bestxtools.com/d/5/2) | [工具推荐](https://discuss-cn.bestxtools.com/t/tools) | [评论](https://discuss-cn.bestxtools.com/d/125/2)

---

原文链接: [https://github.com/bestxtools/weekly-cn/blob/main/docs/issue-47.md](https://github.com/bestxtools/weekly-cn/blob/main/docs/issue-47.md)
