---
title: "江疆｜Apple 软件工程师"
date: "2015-10-01"
categories: 
  - "interview"
tags: 
  - "mac"
  - "其实很特别"
  - "字体"
  - "developer"
---

### ![jiangjiang](/images/jiangjiang.jpg)

### 介绍一下你自己和所做的工作。

我叫[江疆](https://gist.github.com/jjgod/4109970)，软件工程师，以前开发过 [Qt](https://www.qt.io/) 和 [Opera](https://www.opera.com/)，目前在 [Apple](https://www.apple.com/) 做文本和字体相关的工作。

### 你都在使用哪些硬件？

没什么很特别的硬件。我每过一段时间就会尝试一些不同的硬件。

使用了一段而且觉得还不错的有：

- [Matias Ergo Pro](https://matias.ca/ergopro/pc/) 键盘。机械人体工学键盘，做工不错，还需要适应一下键位。
- [Freitag](https://www.freitag.ch/) 的包。轻便，防水，不怕脏。我用的是 [F14 Dexter](https://www.freitag.ch/Fundamentals/Messengers-Classic/DEXTER/pa/F14)。
- Handwers [Surface](https://www.handwers.com/en/mousepad-surface-bark) 鼠标垫。
- [Withings Activité](https://www2.withings.com/us/en/withings-activite.html) 手表。优点是很低调，也不用考虑充电的问题。
- Bonavita [温控水壶](https://bonavitaworld.com/products/10l-digital-variable-temperature-gooseneck-kettle)。用来烧水做咖啡或者泡茶，省掉了一直检查温度的麻烦。

### 软件呢？

软件也没什么特别的，都是大家会用到的那些。

我最近在尝试使用的等宽字体是 [Input Mono Condensed](https://input.fontbureau.com/)，它主要会用在写代码和浏览代码，我还习惯用等宽字体看和写邮件以及 IRC。

![Input Mono Condensed](/images/Input-Mono-Condensed-1024x340.png)

阅读字体是 [Alegreya Sans](https://www.huertatipografica.com/en/fonts/alegreya-sans-ht)，阅读的字体主要用在 RSS 阅读器（我个人使用的是 [ReadKit](https://readkitapp.com/)）、Safari Reader 的定制字体（[CustomReader](https://canisbos.com/customreader) 插件可以定制 Reader 模式的字体）这些需要阅读长文的地方。

![alegreya Sans ht](/images/alegreya-Sans-ht-1024x457.png)

具体与字体技术相关的开发调试工具我曾在[博客](https://blog.jjgod.org/2012/01/16/tools-for-a-typography-hacker/)中整理过一遍：

![UnicodeChecker](/images/UnicodeChecker.png)

[UnicodeChecker](https://earthlingsoft.net/UnicodeChecker/)。Mac OS X 下完美的 Unicode 字符查看工具，可以根据 UTF-16 编码 (10 进制、10 进制)、UTF-8 编码来查找，或者直接复制粘贴字符进去，可以选择不同的字体查看该字符对应的字形，包含完整的 Unicode 字符属性数据库，可以自动下载安装 Unihan 数据库。几乎是每次开发和调试问题的必备。Linux 下有 [gucharmap](https://live.gnome.org/Gucharmap) 实现类似的功能，但要弱很多。

[ttx](https://www.letterror.com/code/ttx/)。将 TrueType/OpenType 文件按照指定的表 dump 成 XML 格式，或者反过来，所以既可以查看也可以修改。非常方便分析 OpenType 的 GPOS/GSUB 特性查找表。这是一个命令行工具。更简单一点的 TTF/OTF 分析命令行工具还有 [lcdftypetools](https://www.lcdf.org/type/) 里的 [otfinfo](https://www.lcdf.org/type/otfinfo.1.html)，可以直接列出字体的特性，但没有细节显示。

![fontforge](/images/fontforge.png)

[FontForge](https://fontforge.sourceforge.net/)。大部分 TTX 的功能也都可以用 FontForge 实现，虽然界面是基于 Xlib 的相对老旧，但它的功能实在是强大，不过我一般也就用来编辑字体的 name table 和 OpenType feature。

[hb-view](https://cgit.freedesktop.org/harfbuzz/tree/util)。[harfbuzz-ng](https://freedesktop.org/wiki/Software/HarfBuzz) 提供的工具，可以用指定的字体、指定的 OpenType 特性，将 HarfBuzz 排版好的内容以 FreeType 渲染出来，方便对比测试特性字符串的布局正确性。当然，通常我还会用常见的浏览器、文本编辑器等来比较，尤其现在 Firefox 和 IE10 TestDrive 支持 OpenType 特性指定了，测试起来就更方便。

[fc-list](https://ftp.x.org/pub/X11R7.0/doc/html/fc-list.1.html), [fc-match](https://linux.die.net/man/1/fc-match)。[fontconfig](https://www.freedesktop.org/wiki/Software/fontconfig) 提供的工具，主要用来分析 Linux 下的字体匹配，在阅读它的[用户文档](https://www.freedesktop.org/software/fontconfig/fontconfig-user.html)之后，善用 `-v` 和 `-a` 参数，可以直接获得不少字体的信息。

[![Pixie](/images/Pixie.png)](https://blog.jjgod.org/wp-content/uploads/2012/01/Pixie.png)Pixie，Xcode 自带的屏幕放大镜，用来分析 subpixel antialiasing 非常给力。别的平台下当然也有类似的工具，比如我在 Linux 下用 KDE 的 [kmag](https://www.kde.org/applications/utilities/kmag/)。

[Kerning Game](https://type.method.ac/) 和 [letter shaping game](https://shape.method.ac/)。两个制作非常精良的字体相关 HTML5 小游戏，可以体验对字体间距形状把握，适合在开发之余放松一下大脑 😉

### 你最理想的工作环境是什么？

我对工作环境要求不高，不要太吵就行。

### 你平时获得工作灵感的方式有哪些？

休息一下，尝试和别人重新[描述一下问题](https://books.google.com/books?id=to6M9_dbjosC&pg=PA123&lpg=PA123)。

### 推荐一件生活中的利器给大家。

[AeroPress](https://aerobie.com/product/aeropress/)，做咖啡很方便。

![aeropress](/images/areopress-804x1024.jpeg)

 

加入[利器社群](https://liqi.io/community/)，你也可以分享自己的利器。
