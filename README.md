# 纯纯写作使用手册<!-- omit in toc -->

本手册专为**纯纯写作**编写，主要用于纯纯写作中特色功能的介绍与日常使用时的问题自检与修复。

本手册正文分为 [纯纯写作 Q&A](#纯纯写作%20Q&A)、[纯纯写作云备份常见问题](#纯纯写作云备份常见问题)、[纯纯写作 Markdown 使用指南](#纯纯写作%20Markdown%20使用指南)、[纯纯写作 Markdown 使用常见问题](#纯纯写作%20Markdown%20使用常见问题)、[纯纯写作桌面测试版常见问题解答](#纯纯写作桌面测试版常见问题解答) 五个部分，除此之外，正文之后还有彩蛋 [纯纯小八卦](#纯纯小八卦)。

在使用中，请善用网页内搜索，电脑端可使用 Ctrl+F 打开网页搜索，手机端请在网页菜单中自行寻找网页搜索。

原则上，GitHub 版本将不会再接受改动范围较小的 Pull request，对手册中的内容有疑问可以发起 Issue。

## 目录<!-- omit in toc -->

- [纯纯写作 Q&A](#纯纯写作-qa)
  - [字数统计的不同种类](#字数统计的不同种类)
  - [关于横屏下的使用](#关于横屏下的使用)
  - [快捷输入栏的用法简介](#快捷输入栏的用法简介)
  - [关于快捷输入项光标落点](#关于快捷输入项光标落点)
  - [如何通过快捷输入项插入当前时间？](#如何通过快捷输入项插入当前时间)
  - [状态栏专注模式的简介与问题](#状态栏专注模式的简介与问题)
  - [关于格式化选项（段间空行/缩进/中英文本间空格）](#关于格式化选项段间空行缩进中英文本间空格)
  - [如何查找/替换文本？](#如何查找替换文本)
  - [搜寻文章/快速跳转到某文章 如何使用？](#搜寻文章快速跳转到某文章-如何使用)
  - [单个篇章有字数限制吗？](#单个篇章有字数限制吗)
  - [如何查看篇章的建立/更新时间？](#如何查看篇章的建立更新时间)
  - [如何打开外部文档？](#如何打开外部文档)
  - [为什么不能打开/导入太大的文档？](#为什么不能打开导入太大的文档)
  - [为什么默认字体不是系统字体？](#为什么默认字体不是系统字体)
  - [如何修改字体与字号？](#如何修改字体与字号)
  - [如何使文字变为半透明？](#如何使文字变为半透明)
  - [为什么文字左右边距不一样了？](#为什么文字左右边距不一样了)
  - [行/段间距怎么调整？](#行段间距怎么调整)
  - [文字为什么不能两端对齐？](#文字为什么不能两端对齐)
  - [修改背景后字体颜色不是很明显怎么办？](#修改背景后字体颜色不是很明显怎么办)
  - [纯纯写作能够修改字体颜色吗？](#纯纯写作能够修改字体颜色吗)
  - [如何重做被误撤销的内容？](#如何重做被误撤销的内容)
  - [码字的时候只有一段/一行高亮是怎么回事？](#码字的时候只有一段一行高亮是怎么回事)
  - [可以导出除 .png 图片/ .txt 文档/ .md 文档之外的格式吗？](#可以导出除-png-图片-txt-文档-md-文档之外的格式吗)
  - [为什么篇章目录里的内容变成了标题或文本的前一行？](#为什么篇章目录里的内容变成了标题或文本的前一行)
  - [打字机模式是什么？](#打字机模式是什么)
  - [什么是只读模式？](#什么是只读模式)
  - [如何打开只读模式？](#如何打开只读模式)
  - [如何退出只读模式？](#如何退出只读模式)
  - [如何在其他位置插入新文章？](#如何在其他位置插入新文章)
  - [关于【少数派选项】](#关于少数派选项)
  - [在使用中出现异常的反色该怎么办？](#在使用中出现异常的反色该怎么办)
  - [为什么会出现【此功能为高级功能】弹窗？](#为什么会出现此功能为高级功能弹窗)
  - [不购买纯纯写作的高级版可以正常使用吗？](#不购买纯纯写作的高级版可以正常使用吗)
  - [自定义的稿纸为何不会消失？](#自定义的稿纸为何不会消失)
  - [恢复备份时，会恢复稿纸吗？](#恢复备份时会恢复稿纸吗)
  - [纯纯写作可以自定义导出图片的背景吗？](#纯纯写作可以自定义导出图片的背景吗)
  - [缩进宽度出现问题是怎么回事？](#缩进宽度出现问题是怎么回事)
  - [码字时为什么没有缩进了？](#码字时为什么没有缩进了)
  - [导出文本时格式为什么是 .md？](#导出文本时格式为什么是-md)
  - [纯纯写作中可以使用 Markdown/LaTeX 吗？](#纯纯写作中可以使用-markdownlatex-吗)
  - [Markdown 的快捷输入页面](#markdown-的快捷输入页面)
  - [切换到废纸篓或某书籍时卡顿（卡死）怎么办？](#切换到废纸篓或某书籍时卡顿卡死怎么办)
  - [可以在纯纯写作中加粗文字/插入图片吗？](#可以在纯纯写作中加粗文字插入图片吗)
  - [为什么打开纯纯写作时提示“跳过”或自动创建新文章？](#为什么打开纯纯写作时提示跳过或自动创建新文章)
  - [为何 Google Play 售价与国内售价不同？](#为何-google-play-售价与国内售价不同)
  - [谷歌商店购买与支付宝购买的区别是什么?](#谷歌商店购买与支付宝购买的区别是什么)
  - [想从 Google Play 购买却无法启用谷歌支付？](#想从-google-play-购买却无法启用谷歌支付)
  - [Google Play 购买的会员为什么有时会失去激活？](#google-play-购买的会员为什么有时会失去激活)
  - [在谷歌商店买过纯纯写作，但新设备无法使用谷歌怎么办？](#在谷歌商店买过纯纯写作，但新设备无法使用谷歌怎么办)
  - [可以从第三方购买纯纯写作激活码吗？](#可以从第三方购买纯纯写作激活码吗)
  - [为什么在 Chrome OS 设备、Fyde OS 设备或某些 Android x86 设备上无法用回车换行？](#为什么在-chrome-os-设备fyde-os-设备或某些-android-x86-设备上无法用回车换行)
  - [为什么不能自定义所有设置项？](#为什么不能自定义所有设置项)
  - [纯纯写作有 iOS 版本吗？](#纯纯写作有-ios-版本吗)
  - [使用纯纯写作有文章被窃取的风险吗？](#使用纯纯写作有文章被窃取的风险吗)
  - [为什么之前囤积的激活码不能使用了？](#为什么之前囤积的激活码不能使用了)
- [纯纯写作云备份常见问题](#纯纯写作云备份常见问题)
  - [为什么坚果云的 WebDAV 显示不能登录？](#为什么坚果云的-webdav-显示不能登录)
  - [云备份真的有必要吗？](#云备份真的有必要吗)
  - [为什么坚果云的 WebDAV 显示不能登录？](#为什么坚果云的-webdav-显示不能登录-1)
  - [错误提示：您的 WebDAV 配置不完整或不正确](#错误提示您的-webdav-配置不完整或不正确)
  - [错误提示：帐号和密码错误](#错误提示帐号和密码错误)
  - [错误提示：Error: Error contacting (403)](#错误提示error-error-contacting-403)
  - [坚果云提示 503 错误](#坚果云提示-503-错误)
  - [新设备恢复备份后为什么还是初始文章？](#新设备恢复备份后为什么还是初始文章)
  - [纯纯写作支持自动同步吗？](#纯纯写作支持自动同步吗)
  - [纯纯写作为什么没有自动同步？](#纯纯写作为什么没有自动同步)
  - [多设备使用时备份中的内容会自动合并吗？](#多设备使用时备份中的内容会自动合并吗)
  - [备份包很大使坚果云流量迅速用完怎么办？](#备份包很大使坚果云流量迅速用完怎么办)
  - [Google Drive 找不到备份文件？](#google-drive-找不到备份文件)
  - [纯纯写作可以使用百度云备份吗？](#纯纯写作可以使用百度云备份吗)
  - [关于使用其他云盘备份的统一回复](#关于使用其他云盘备份的统一回复)
  - [为什么不能关闭自动备份？](#为什么不能关闭自动备份)
- [纯纯写作 Markdown 使用指南](#纯纯写作-markdown-使用指南)
  - [何谓 Markdown？](#何谓-markdown)
    - [注意事项](#注意事项)
  - [正文部分](#正文部分)
    - [目录](#目录)
    - [标题](#标题)
    - [加粗/斜体/粗斜体](#加粗斜体粗斜体)
    - [删除线/下划线](#删除线下划线)
    - [有序列表](#有序列表)
    - [无序列表](#无序列表)
    - [引用](#引用)
    - [脚注](#脚注)
    - [角标](#角标)
    - [文字居左/居中/居右](#文字居左居中居右)
    - [插入图片](#插入图片)
    - [插入链接](#插入链接)
    - [插入表格](#插入表格)
    - [选择框](#选择框)
    - [页内快速跳转](#页内快速跳转)
    - [分割线](#分割线)
    - [改变字符颜色](#改变字符颜色)
    - [输入标记字符](#输入标记字符)
    - [关于其他 HTML 代码](#关于其他-html-代码)
    - [代码块](#代码块)
- [纯纯写作 Markdown 使用常见问题](#纯纯写作-markdown-使用常见问题)
  - [关于纯纯写作 Markdown 的使用规范与兼容性测试](#关于纯纯写作-markdown-的使用规范与兼容性测试)
  - [Markdown 的文本高亮（或其他一些代码）为何无法使用？](#markdown-的文本高亮或其他一些代码为何无法使用)
  - [Markdown 的居中为何无法使用 center 代码？](#markdown-的居中为何无法使用-center-代码)
  - [Markdown 导出图片或预览时有些地方未能正常显示？](#markdown-导出图片或预览时有些地方未能正常显示)
- [纯纯写作桌面测试版常见问题解答](#纯纯写作桌面测试版常见问题解答)
  - [关于纯纯写作测试版使用体验的重要说明](#关于纯纯写作测试版使用体验的重要说明)
  - [桌面版在哪里下载？](#桌面版在哪里下载)
  - [如何连接桌面版？](#如何连接桌面版)
  - [为什么桌面版打不开？](#为什么桌面版打不开)
  - [为什么手机与桌面版连接不上？](#为什么手机与桌面版连接不上)
  - [为什么桌面版与手机的连接经常断开？](#为什么桌面版与手机的连接经常断开)
  - [为什么开启自动连接后，仍然不能自动连接到桌面版？](#为什么开启自动连接后仍然不能自动连接到桌面版)
- [纯纯小八卦](#纯纯小八卦)
  - [为什么昵称开发者 Drakeet 为爪爪？](#为什么昵称开发者-drakeet-为爪爪)
  - [有人说开发组有四个成员，分别是谁呢？](#有人说开发组有四个成员分别是谁呢)
  - [纯纯写作的小彩蛋](#纯纯写作的小彩蛋)

# 纯纯写作 Q&A

## 字数统计的不同种类

在中文使用下，纯纯写作的字数统计有三种模式，分别是不包含空格与换行，包含所有符号和文字，排除所有标点符号、空格和换行符。很好理解，这里不多赘述。

在英文使用下，如果发现自己的字数统计将一个字母统计成了一个字而非一个单词一个计数，可以在设置项中打开【视一个单词为一个计数】，即可使用单词计数，但针对中文的字数统计选项将失效，将被默认为【不包含空格和换行】。

## 关于横屏下的使用

目前纯纯写作对横屏使用的兼容不是非常友好，如果要横屏使用的话最建议的还是使用平板电脑或电脑安卓系统。

横屏的打开方式：关闭系统的【方向锁定】，旋转你的手机变为横屏。

如果你找不到这个设定，请打开手机的【设置】，在其中找到有【显示】或【显示与亮度】字样的设置，找到【关闭竖屏锁定】或【自动旋转屏幕】，打开它。

使用平板电脑的桌面模式或电脑安卓系统，可以通过拖拽边框使其成为横屏显示。

## 快捷输入栏的用法简介

快捷输入栏是纯纯写作键盘上方的一个小栏。在此栏目中，用户可以自行设定快捷输入内容（比如时间日期、人物名字或常用的标点符号等）或快捷工具。

点击【⊕】或【⊕ 建立快捷输入项】即可建立新的快捷输入项或快捷工具，长按已有的快捷输入项即可对它进行排序、修改或删除。移动【内容】中的光标位置，即可设定插入此内容后光标的落点。

值得注意的是，不同于其他地方，当你选中一段文字并插入一个光标落点在文本中间的快捷输入项时，此项目会出现在选中文本的两侧，而非替换掉这段文字；在写作时，此法可以快速为忘记加引号、括号的句子或段落添加符号。

目前快捷输入栏已经与快捷工具栏合并，仍使用旧版快捷输入栏的应用可以自行升级应用至最新版本。

---

在纯纯写作后续的更新中，仍会对快捷输入栏进行了多项优化与调整，以下将简要介绍其最近的修改：

**加入了快捷工具**，可以通过【建立快捷输入项】来建立位于快捷输入栏的快捷工具，目前支持的快捷工具有 重做、段首缩进、格式化选项一键排版、聚焦到文末、聚焦到顶部、复制当前选中文本或全文、搜索文章/快速跳转至某文章、快捷移动光标（需在少数派选项中单独开启），用户可以自行设定；

**将撤销与粘贴功能固定在快捷输入栏左半部分**，在编辑和修改文章时更加方便（原重做位置没有变化）；

**将快捷移动光标默认固定在快捷输入栏右侧，并修改其使用逻辑**，需要点击以打开快捷移动光标面板，并通过按住按钮移动手指来移动光标。

**到目前版本为止，纯纯写作的快捷输入栏暂不支持主动关闭。**

## 关于快捷输入项光标落点

快捷输入项由「内容」与「简短描述」两部分组成，快捷输入项的光标落点取决于「内容」一栏中的光标位置。

如「内容」中为`【｜】`，则点击快捷输入项后光标会落在`【】`之间，如「内容」中为`【】｜`，则点击快捷输入项后光标会落在`【】`之后。

## 如何通过快捷输入项插入当前时间？

设置此项目需要使用`${<format>}`的格式，在【快捷输入项】的【内容】中添加相应内容。

先放一张快捷输入时间的表格，如果看不懂的话可以略过它直接使用后面给的**万金油公式**。

![对照表格与示例](https://github.com/Ayaginu-Sue/purewriter/blob/main/Image/time_shortcut.jpg)

附赠几个万金油公式，可以复制后依据自己的需求增删：

**12 小时计时法**：`${GG yyyy-MM-dd E aa hh:mm:ss.SSS(z)}`

**输出格式为**：纪元 年-月-日 星期 上/下午 12 小时计时:分:秒.千分之一秒（时区信息）

**24 小时计时法**：`${GG yyyy-MM-dd E HH:mm:ss.SSS(z)}`

**输出格式为**：纪元 年-月-日 星期 24 小时计时:分:秒.千分之一秒（时区信息）

**想输出汉字内容也可以直接用汉字**，如：

**12 小时计时法**：`${GG纪年 yyyy 年 M 月 d 日E aa hh 时 mm 分 ss 秒 SSS 毫秒 时区：z}`

**24 小时计时法**：`${GG纪年 yyyy 年 MM 月 dd 日EEEE HH 时 mm 分 ss 秒 SSS 毫秒 时区：z}`

**注意：使用单个字母表示时，“04”将显示为“4”，同理，“星期二”也将显示为“周二”。**

关于图片中内容更详细的描述可以查看链接：[Customizing Formats](https://docs.oracle.com/javase/tutorial/i18n/format/simpleDateFormat.html)

## 状态栏专注模式的简介与问题

状态栏专注模式是用于隐藏状态栏的大多数通知图标的功能。

它的位置在【行间距|左右边距】的菜单中段间距开关的右侧。小米/红米手机用户因为 MIUI 的魔改所以不能隐藏状态栏图标。

这个功能在不同机型上的适配程度不同，效果也会因为 ROM 的升级等情况有所差异，因此在某些机型上并不能成功设置该模式，还请理解。

## 关于格式化选项（段间空行/缩进/中英文本间空格）

格式化选项是用于快速为全文赋予统一格式的选项内容。

在其中，你可以在段与段之间增加或删去多余的空行、在中英文之间插入空格以便阅读、增添缩进或删去段首的空格。

格式化选项在长篇的文段编辑中是很有用的，请不要因为“格式化”三个字就感到恐惧，放心使用吧。

## 如何查找/替换文本？

在主页面点击右上角三个点，在弹出菜单中选择【查找&替换】（【寻找&取代】），上输入栏为想要查找的内容，下输入栏为想要替换的内容。若只需要进行查找，则不需要在下栏中输入内容；进行替换时则需要选中要进行替换的部分后点击替换。

在输入框下面的选择栏第一栏可以选择不同的查找模式与范围，目前提供的有：“目前篇章”、“目前书”、“全部书”、“忽略大小写”；第二栏则是一些功能按键，如：“全选”、“反选”、“取代”、“收起软键盘”及【搜寻文章/快速跳转到某文章】面板的开关。

**如要进行文章检索，请使用【搜寻文章/快速跳转到某文章】功能。**

## 搜寻文章/快速跳转到某文章 如何使用？

该功能主要的作用是在书籍中搜索**带有特定内容的文章**，**而非在文章内搜索相关内容**，因此在单个文章中出现多个关键词时只会显示文中的第一个关键词，同一篇文章中即使有多个关键词也只会显示一个搜索结果。

**简单用法：**输入记忆中那篇文章中的相关内容，即可搜索具有该内容的文章。当有**多个关键字/词**时，可以通过**换行**输入多个关键字/词进行搜寻，但其结果中只会高亮显示第一个关键字/词。

此搜索方式可以用于章节名/标题搜索，输入相关文章的标题即可搜索具有该内容的文章。虽然目前不支持“仅搜索标题”功能，但可以利用一并搜索标题中使用的特殊字符（如空格、“章”）达到类似的效果。

**正则表达式（正规表示式）**：可以利用正则表达式对文章内容进行搜索，由于正则表达式使用者较少，这里不提供教程，感兴趣的可以在网络上查询。

## 单个篇章有字数限制吗？

纯纯写作完全克服了单章字数有限制这一技术难题，实现了**单章节无限字数**，单个章节的字数只由你个人的意愿和手机的性能决定。

经测试，纯纯写作可以做到浏览千万字的文章不卡顿，理论上可以做到浏览一亿字不卡顿（此数据为开发者实验所得。请注意，随意实验将使坚果云流量被迅速耗尽）。

在实际使用中如果要进行编辑，建议将单个章节的字数控制在**两万以下**，以获得流畅的使用体验。因为由于手机性能限制，部分设备单篇章字数超过一万后编辑时会有略微卡顿，浏览时不会受到影响。

## 如何查看篇章的建立/更新时间？

- 在篇章目录侧栏的顶部点击【更多】图标，点击【放大】。
- 在篇章目录侧栏的顶部点击【排序规则】图标，点击【显示时间类型】并选择所需的显示类型。

## 如何打开外部文档？

纯纯写作支持打开外部的 TXT/Markdown 文档。

一般可以从系统文件管理器的【第三方应用打开】中找到【用纯纯写作打开】，部分管理器可能不显示【用纯纯写作打开】，可以替换其他文件管理器打开。

## 为什么不能打开/导入太大的文档？

由于手机的性能限制，纯纯写作在打开某些较大的 TXT 文档时会有卡顿的现象，让许多用户误认为应用或系统卡死。因此，纯纯写作主动禁止了用户导入太大的文档，用户仍然可以通过复制粘贴的方式导入进去。

**太大的文档一般是 300KiB 以上的文档，根据手机的性能不同也有所不同。**

## 为什么默认字体不是系统字体？

纯纯写作默认为用户提供了「霞鹜文楷」免费字体，可以在设置中关闭「免费的内建霞鹜文楷」来使用系统字体或自定义字体。

## 如何修改字体与字号？

自定义字体是高级功能，但是免费用户可以免费体验该功能。

安卓 11 以下版本系统设置方式：将你所中意的字体的 TTF 档案放置在储存目录的 `/Documents/PureWriter/App` 文件夹下，在设定中打开【自定义字体】后，退出纯纯写作重新进入即可装载自定义字体。

安卓 11 及以上版本系统设置方式：在设定中打开【自定义字体】后，点选【选取字体】，在弹出的界面中选择中意的字体即可。

在设定中有修改标题与正文字号的选项，请在设定中修改。

## 如何使文字变为半透明？

点击主页右上角的三个点，在下方弹出的菜单中点选【行间距|左右边距】，即可修改文字的透明度。

## 为什么文字左右边距不一样了？

点击主页右上角的三个点，在下方弹出的菜单中点选【行间距|左右边距】，即可修改文字的左右边距。

## 行/段间距怎么调整？

点击主页右上角的三个点，在下方弹出的菜单中点选【行间距|左右边距】，即可修改文字的行间距和段间距。

## 文字为什么不能两端对齐？

Android 的原生 TextView 无法实现文本的两端对齐，只有 WebView 可以做到，但是 WebView 的性能很差，因此纯纯写作选择了使用 TextView。性能与两端对齐，二者不可得兼。

此问题向纯纯反馈是没有作用的，纯纯写作不会也无法修复安卓系统的问题，请向 Google 官方反馈该问题。

## 修改背景后字体颜色不是很明显怎么办？

点击主页右上角的三个点，在下方弹出的菜单中点选【行间距|左右边距】，即可强制修改字体颜色（仅限黑白）。

## 纯纯写作能够修改字体颜色吗？

目前纯纯写作只支持强制切换黑白字体，不可以修改字体颜色，也并无支持相关功能的计划。

如有特殊需求，可以使用 Markdown 实现相关功能。

## 如何重做被误撤销的内容？

点击右上角菜单，在弹出的菜单底部有重做按钮。

在点击一次重做之后，设置菜单将消失，为用户多次点击重做提供足够的视野。

17.0 版本后用户也可以通过快捷工具栏进行撤销和重做操作，在快捷输入栏中建立相关工具即可使用。

## 码字的时候只有一段/一行高亮是怎么回事？

出现此情况应该是不慎打开了打字机模式，在页面右上角的菜单中可以关闭它。

## 可以导出除 .png 图片/ .txt 文档/ .md 文档之外的格式吗？

暂时不支持导出其他格式的档案，有计划支持导出 .docx 和 .pdf 档，但是目前优先级不是很高。

## 为什么篇章目录里的内容变成了标题或文本的前一行？

点击篇章目录右上角的三个点，在弹出菜单中点击放大就可以恢复原状了。

## 打字机模式是什么？

在打字机模式下，将只会高亮显示当前正在编辑的一段文字，可以让用户更加专注于当前的文字，并且也可以在一定程度上躲过来自身后的窥视者。

如果错误打开了打字机模式可以在右上角的菜单中关闭它。

## 什么是只读模式？

只读模式可以近似为阅读模式，在此模式下，你可以随意滑动、翻阅你的文章而无需担心误触带来的文字误删除、缺失等问题，确保内容**安全无虞**。

目前只读模式变更为了**高级只读模式**，以下是它的特性简介：

当光标不可见时，需要双击编辑器才能加入光标；

当光标可见时，只需要单击编辑器就可以加入光标；

当光标可见而输入法面板已经收起，可以点按返回来隐藏光标重新进入只读模式。

## 如何打开只读模式？

只读模式被收集在了右下角 `⊕` 的菜单中，点击或长按（依个人设定有所不同）右下角的 `⊕` 符号即可在弹出的项目列表中点选开启只读模式。

## 如何退出只读模式？

若要临时离开只读模式进行编辑，可以双击编辑器打破只读并插入光标。

若要关闭只读模式则点击或长按（依个人设定有所不同）右下角的 `⊕` 符号即可在弹出菜单中关闭只读模式。

## 如何在其他位置插入新文章？

在其他位置插入新文章（文章列表底部、卷末尾、当前文章后）被统一收集在了右下角 `⊕` 的位置，长按右下角的 `⊕` 符号即可弹出该项目列表。

## 关于【少数派选项】

【少数派选项】或称【强迫症选项】，其中将提供一些开发者本不愿提供，但用户呼声特别大的配置项，如关闭顺滑光标、关闭标题居中等。

## 在使用中出现异常的反色该怎么办？

一般此问题常出现于国产手机厂商的系统中，此问题是由国产系统的深色模式的强制反色造成的，目前纯纯写作无法完全规避该问题。

目前能提供的解决方法：

- 在手机系统设置中关闭系统对纯纯写作的强制深色。
- 尽量避免在使用纯纯写作时打开深色模式。
- 向相关系统厂商提出建议修改并优化相关功能，要求厂商开放拒绝被系统强制深色模式的接口等。

## 为什么会出现【此功能为高级功能】弹窗？

自定义稿纸、预览（包括 Markdown 快捷预览）、导出、Material Design 2 主题、查找与替换、合并成书导出、第二编辑器、自定义字体等功能是高级功能，付费用户可以使用。

其中部分功能允许免费用户试用，但是在试用时会弹出【此功能为高级功能】的弹窗或半屏提示，不影响正常使用此功能。

若你已是付费用户但仍会显示这个弹窗，请进入高级版页面检查你的纯纯写作账号或谷歌账号是否在登入中，若未登入请重新登入或进入谷歌商店验证你的谷歌账号。

## 不购买纯纯写作的高级版可以正常使用吗？

**可以**，纯纯写作的核心功能都是免费的，包括优秀的编辑器体验与万无一失的云备份。你可以在纯纯写作中免费使用大部分功能，纯纯写作也不会通过为免费版用户插入广告获得其他收益。

每年的双十一都会有降价活动，如果不着急的话可以等待双十一的活动或者不定时的抽奖与活动。

## 自定义的稿纸为何不会消失？

在新版的纯纯写作中，应用会在稿纸页面自动记忆用户上次使用过的稿纸，以方便用户快速修改稿纸。目前阶段纯纯写作允许同时记忆两张自定义稿纸，当用户设定新的稿纸时，旧的稿纸就会被覆盖。

长按自定义稿纸项目即可对其进行删除。

## 恢复备份时，会恢复稿纸吗？

纯纯写作的备份包中会自动备份用户稿纸的图床链接或 RGB 颜色值。如果在设定稿纸时使用的是 RGB 颜色值或图床链接，则恢复备份时会恢复原稿纸，如使用本地图片做稿纸则不会保留。

## 纯纯写作可以自定义导出图片的背景吗？

**目前不能。**

抱歉，因为文章的长度可能很长很长，而背景图片的长度是固定的，如果拉伸，会很难看、扭曲。待解决方案：

1. 可以尝试超出长度使用渐变过渡，但用户图片千奇百怪，很难真正适配好。
2. 使用重复平铺，但同样可能不协调，而且如果图片过于复杂，容易导致生成的长图片体积成倍增加，这将很不利于传播和遭到许多平台压缩。

## 缩进宽度出现问题是怎么回事？

缩进显示出现问题一般有两种可能的原因：字体改变和应用（系统）语言非中文。

- 最常见的情况是由修改字体导致的问题，常见的表现有显示的缩进长度不够（一般为半角空格，即缩进只有一个汉字字符宽度）或显示为错误符号、圆点、方框等。

  纯纯写作的缩进内容是两个全角空格，而部分字体在制作时将全角空格（U+3000）制作为半角空格的宽度或其他内容，导致所显示的缩进内容并非全角空格而是其他字符。

  **解决办法**：这种情况只有切换全角空格显示正常的字体可以解决，请自行切换系统字体或参考本 Q&A 中的内容切换第三方字体；有技术条件的用户可以自行修改字体中的全角空格使其符合规范。

- 另一种情况是由于修改应用或系统语言导致的。

  纯纯写作是面向全世界用户发布的，其缩进规则也会根据不同地区用户的使用习惯，如英语环境下的缩进为四个半角空格，日、韩语环境下缩进为一个全角空格等。

  **解决办法**：将应用语言或系统语言切换为简体中文或繁体中文。

## 码字时为什么没有缩进了？

- 你有可能打开了 Markdown 模式，此模式下将会自动停止缩进，关闭 Markdown 后则会恢复正常。
- 如果没有打开 Markdown ，请进入设定，检阅是否开启了“段首缩进”。

## 导出文本时格式为什么是 .md？

.md 格式是 Markdown 文档的导出格式。

若要导出 TXT 文字文档，请回到码字页面唤起输入法，在快捷输入项右侧点击 MD 开关以关闭 Markdown。

## 纯纯写作中可以使用 Markdown/LaTeX 吗？

纯纯写作支持使用 Markdown 和一部分 HTML 标签（如下划线 `<u>文字</u>`），而 LaTeX 支持插入行间公式和行内公式，但目前 LaTeX 部分的文字会有一定下沉。

需要启用 Markdown/LaTeX 时请在顶栏右侧点按 `TXT` 按钮使之变为 `M↓`。

在使用 Markdown 时若要获得预览效果，可以点击右下角加号旁的图标切换预览状态。

如果你打算尝试 Markdown，你可以在这里获得来自开发者的简要介绍：[Markdown简明教程](https://writer.drakeet.com/markdown)，也可以在本手册中阅览[纯纯写作 Markdown 使用指南](#纯纯写作%20Markdown%20使用指南)。

更多关于 Markdown 使用中的问题请参考：[纯纯写作 Markdown 使用常见问题](#纯纯写作%20Markdown%20使用常见问题)。

## Markdown 的快捷输入页面

Markdown 的快捷输入页面整合了一些常用的 Markdown 符号，Markdown 写作者可以使用它更方便地输入 Markdown 符号。

在 Markdown 模式下点击快捷输入列最左端的 M↓ 图标即可打开 Markdown 快捷输入页面；而非 Markdown 模式下需要打开格式化选项后向左移动到 Markdown 快捷输入页面。

在此处，你可以快捷输入部分 Markdown 标签，如加粗、斜体、插入图片等，不过此页面的东西**不支持修改**。

## 切换到废纸篓或某书籍时卡顿（卡死）怎么办？

**如果此条目未能解决该问题，请向开发者（邮箱：drakeet@drakeet.com）写邮件反馈。**

这一般是由于废纸篓中储存的文章过多，超出了手机的运算能力引起的。此时纯纯写作**并没有卡顿**，而是在加载废纸篓中的文章，因此应用无法做出任何应答，会让人误以为应用卡死，请稍作等待至全部文章加载完成，打开后请尽量删除或清空废纸篓中的内容，以避免再次卡顿。

**请注意，此时切勿退出应用，否则可能导致下次打开应用时闪退。**
发生闪退的解决方法：

1. 确保有做过备份，如未进行云备份则在本地备份文件夹 `Documents/PureWriter/backups/Auto` 或自己设定的备份文件夹中复制并保留未打开废纸篓时的备份包（非最新备份包，建议多保存几个，以备不时之需）。
2. 卸载纯纯写作并重新安装。
3. 通过本地或云端保留的备份包恢复发生闪退前的备份。
4. 此时即可重新进入废纸篓页面并等待其页面开启。

**此情况也可能发生于切换到其他书籍或超长文章时，多发生在「打开不常打开却经常向其中移动内容的书籍」或「由高配手机切换到低配手机、且用户有非常巨大的文章」时。**

## 可以在纯纯写作中加粗文字/插入图片吗？

纯纯写作是一个纯文本编辑器，它致力于提供优秀的纯文本写作体验和辅助。图片属于富文本内容，无法在纯文本中直接表达，但可以使用 Markdown 用纯文本来描述富文本内容，纯纯写作支持 Markdown。

而且如果支持富文本或图片，则会使得编辑器的复杂度大幅上升，复杂就意味着容易出错且难以做到完美，专注才能做到极致。

所以很抱歉，纯纯写作从一开始到以后都没有计划支持富文本。

希望能得到你的理解。

如果你打算尝试 Markdown，你可以在这里获得来自开发者的简要介绍：[Markdown简明教程](https://writer.drakeet.com/markdown)，也可以在本教程中阅览[纯纯写作 Markdown 使用手册](#纯纯写作%20Markdown%20使用手册)。

## 为什么打开纯纯写作时提示“跳过”或自动创建新文章？

此情况一般是正在使用的某个需要辅助权限/无障碍权限的 启动跳过 类软件造成的。要避免出现此情况请关闭相关应用或将纯纯写作设置为跳过白名单。
关于辅助权限，其实很危险，而且将严重影响系统性能。建议普通用户尽量避免使用需要无障碍权限的应用（或服务），无障碍服务本质上是为了服务盲人等不方便操作的用户，滥用此功能可能导致手机性能的损耗甚至个人信息的丢失。
**外链：**[Android 无障碍服务导致的整机卡顿案例分析](https://www.androidperformance.com/2019/01/21/android-performance-case-jank-accessbility/)
**增补：** 纯纯写作在版本 14.9.5 更新中已禁止 启动跳过 类软件点击创建新文章。

## 为何 Google Play 售价与国内售价不同？

Google Play 没有订阅制，因此如果唯一的可选内购价格非常高，会导致很多人别无选择而无法使用纯纯写作。因此在对 Google Play 用户支持订阅制之前，纯纯写作在 Google Play 价格会低于国内买断价。

另外，之前的很长时间里，纯纯写作的 Google Play 价格一直是国内的两倍，因此现在也相当于反过来平衡。

还请各位手下留情，不要因此给这个应用打差评，如果你喜欢纯纯写作，这是在伤害它，这是不公平的评分，使人沮丧和失去开发下去的动力。

## 谷歌商店购买与支付宝购买的区别是什么?

1. 谷歌暂未加入订阅制度，所以价格相较于国内稍便宜。
2. 从谷歌商店付费购买的用户高级版会绑定在谷歌账号上，而非通过邮箱和账号系统绑定，二者不可互相转换，因此在用户换机的时候新机必须可以正常安装并使用谷歌框架**（因此华为手机/pad 用户或有换华为手机意向的用户请谨慎购买）**，且必须在新机保持登入自己的谷歌账户才可以使用高级版。
3. 谷歌购买时需采用谷歌商店下载的应用版本、且日后的更新也应跟随谷歌商店所推送的版本进行更新，防止因应用版本高于谷歌商店版本造成的购买失败、激活验证失败的情况。由于谷歌审核“歧视”小众应用，纯纯写作在谷歌商店的更新较为缓慢，其更新策略也与国内应用商店不同，因此容易造成版本差距，如果某段时间的更新较为激进的话甚至可能产生两到三个版本的落差，这一点需要注意。
4. 用户需要保持经常登录谷歌商店，防止因太长时间未验证购买而造成失去激活。
5. 谷歌商店购买的可以免于同时登录设备的限制，在无限台设备同时使用高级版，而通过账号系统绑定的高级版只能同时有 3~4 台设备使用。不过这一条对于大多数普通用户来说并没有什么实际意义。

## 想从 Google Play 购买却无法启用谷歌支付？

谷歌购买时需采用谷歌商店下载的应用版本、且日后的更新也应跟随谷歌商店所推送的版本进行更新，防止因应用版本高于谷歌商店版本造成的购买失败、激活验证失败等情况。

除此之外，无法启用谷歌支付还有很多其他原因，诸如 Google Play 未获得屏幕上层显示权限等，请善用搜索引擎解决该问题。

## Google Play 购买的会员为什么有时会失去激活？

这是系统中谷歌账户的缓存过期失效了，请重新确保你的系统中登录了已付费的谷歌账号。

付费状态的缓存可能会定期失效，必须保持登录谷歌账号才能一直保持激活状态，以避免有人借用账号或恶意刷退款。

当遇到失去谷歌激活时**最有效直接的方法**是：退出所有谷歌账号，只登录已付费纯纯写作的谷歌账号，然后打开纯纯写作，以便准确识别是否付费，并且产生新的缓存。

## 在谷歌商店买过纯纯写作，但新设备无法使用谷歌怎么办？

如果你无法登陆 Google 服务，则无法激活纯纯写作，所有你在 Google Play 上付费的应用都是这样的。并不是纯纯写作才这样。因此您应该向该设备反馈，让其保留谷歌服务，至少可自行安装。

如果你打算从 Google Play 转回国内账号，需要补差价，并且因为谷歌需要抽成 30%，所以你需要补的差价为：
128 -（你的谷歌付费价格 × 70%）

建议尝试通过其他手段在手机上安装谷歌服务，否则不仅仅是纯纯写作，任何你在 Google Play 上购买的应用内容都会失效，无能为力。

## 可以从第三方购买纯纯写作激活码吗？

纯纯写作高级版的官方购买渠道只有应用内付费和谷歌商店，官方授权的经销商有少数派、数码荔枝与 Price Tag。

请不要随意相信愿意给你低价的非官方或官方授权的出售者，这可能有封号危险，甚至可能泄漏你的个人信息或者导致文章丢失。

## 为什么在 Chrome OS 设备、Fyde OS 设备或某些 Android x86 设备上无法用回车换行？

这一般是系统的问题，许多系统修改了换行的键位，请尝试使用 Ctrl+Enter 或者 Shift+Enter 换行，许多系统采用此键位作为换行的热键。

如果不能成功建议先在网络上查找一下你所使用系统的换行方式。

## 为什么不能自定义所有设置项？

如果什么都开放给用户自定义，只会使得软件设置页面变得密密麻麻，像飞机仪表盘一样，令人无所适从，心生恐惧，同时也会使得更关键的设置项可达性下降。好的用户体验应该是帮用户考虑好、设计好，开箱即用。另外，如果什么都允许修改，则很多用户会把纯纯写作改得很难看、变成杀马特风格，这是开发者与大多数用户所不愿意见到的。

## 纯纯写作有 iOS 版本吗？

**没有。**

纯纯写作是由 Drakeet 一个人独立开发的，目前的目标是不断把 Android 端做到极致。纯纯写作现在没有 iOS 版的计划，因为优秀的编辑器应该是最难做的产品，若要将纯纯写作复刻到 iOS 上工作量巨大而且难点众多，你会发现许多优秀的 iOS 编辑器同样没有 Android 版，这不是没有原因的，因为复刻的工作量实在太大了，而且纯纯写作目前还比较小众，并不值得去开发 iOS 版，十分抱歉。

## 使用纯纯写作有文章被窃取的风险吗？

**纯纯写作不会窃取用户的文章。**

窃取用户的文章对纯纯写作并没有什么实际用处，是毫不值得的且败坏声誉的行为。

纯纯写作并没有对用户的备份包做特别的保护和加密，因为这样会严重影响打开与编辑文章的速度，占用手机的性能；纯纯写作的文章备份会且仅会保存在至多两个地方——本机的公用备份文件夹（其中手动备份与自动备份的位置不同）与用户自己设定的云盘中对应的文件夹（如果没有设置云备份则不会在任何云端保存，但文章在换机、遗失、损坏的时候可能会丢失），除此之外不会另作他用。因此在一定程度上对备份包的加密是无意义的，如果有人想要窃取你的文章，并且能从你的手机本机/云盘供应商那里获取到你的备份包，那么对于有如此背景实力的人来说加密也是形同虚设的。

注意：纯纯写作不能保证纯纯写作破解版中文章的安全，请使用正版纯纯写作，纯纯写作的免费版是完全足够普通用户正常使用的。

## 为什么之前囤积的激活码不能使用了？

纯纯写作原则上是不允许囤码的，因此每隔一段时间会集中销毁所有此前购买的且未曾激活过的激活码，如果你的激活码是由正规渠道购买的，请回到原渠道反馈该问题，一般会根据原订单给予原价退款。

# 纯纯写作云备份常见问题

## 为什么坚果云的 WebDAV 显示不能登录？

如果登入坚果云的 WebDAV 时显示【您的 WebDAV 设置不完整或不正确】及【Error Connect】错误提示，这是因为使用了坚果云的密码为 WebDAV 密码，现在坚果云已经不支持直接使用坚果云账号密码作为 WebDAV 密码，所以必须要在坚果云中创建「应用密码」，使用应用密码才能连通 WebDAV。

**注意**：多次重复设定密码为账号密码将可能使坚果云账号被封，请点击坚果云邮件提供的链接解封。

出现此问题的用户请按照云备份教学为纯纯写作配置第三方应用密码：[**《纯纯写作自动备份与云备份教学》**](https://writer.drakeet.com/backups)

## 云备份真的有必要吗？

**这非常重要**。

因为即使纯纯写作已经提供了多重防范与保护，但仍然有人因为不愿意进行云备份而在手机丢失或刷机时失去全部的文章。没有人能保证你的手机不会损坏或丢失，一旦手机损坏或丢失，你的文章备份将不复存在，追悔莫及。

WebDAV 云备份相当简单，你可以访问这个页面来了解纯纯写作的自动备份和云备份功能，其中有注册坚果云的教程：[纯纯写作-自动备份与云备份教程](https://writer.drakeet.com/backups)

## 为什么坚果云的 WebDAV 显示不能登录？

如果登入坚果云的 WebDAV 时显示【您的 WebDAV 设置不完整或不正确】及【Error Connect】错误提示，这是因为使用了坚果云的密码为 WebDAV 密码，现在坚果云已经不支持直接使用坚果云账号密码作为 WebDAV 密码，所以必须要在坚果云中创建「应用密码」，使用应用密码才能连通 WebDAV。

**注意**：多次重复设定密码为账号密码将可能使坚果云账号被封，请点击坚果云邮件提供的链接解封。

出现此问题的用户请按照云备份教学为纯纯写作配置第三方应用密码：[《纯纯写作自动备份与云备份教学》](https://writer.drakeet.com/backups)

## 错误提示：您的 WebDAV 配置不完整或不正确

请检查你的 WebDAV 配置中是否少输入或错输入了某些部分。

## 错误提示：帐号和密码错误

- 请检查你的账号或密码中是否有少输入或错输入了某些部分。
- 请检查在输入 WebDAV 帐号或密码时是否有多余的空格或换行，在复制粘贴时很容易出现这种问题，请尝试删除已经输入的配置内容重新手动输入。
- 若检查无问题，可以去查看 WebDAV 帐号是否被封停。

## 错误提示：Error: Error contacting (403)

出现 403 forbidden 的原因大多数是坚果云的流量耗尽了，除此之外可能的原因有且仅有账号密码错误和账号被坚果云锁定，请在确认账号密码正确后自行登录坚果云查找原因。

## 坚果云提示 503 错误

该错误可以参考坚果云的相关文档 [WebDAV 常见问题答疑](https://content.jianguoyun.com/1112.html)。

> 此种情况是由于短时间内请求了太多次同步导致的，关闭同步后六小时再重新启用同步即可。\
> 访问频率限制：由于 WebDAV 协议比较占用系统资源，免费版用户限制访问频率为每 30 分钟不超过 600 次请求。付费用户限制访问频率为每 30 分钟不超过 1500 次请求。

## 新设备恢复备份后为什么还是初始文章？

注意选择**正确的时间和体积**的备份，不要选择你当前新安装又触发而生成的空备份。

## 纯纯写作支持自动同步吗？

纯纯写作暂不支持自动同步，只支持进行云备份。

不同的云备份之间不会自动进行合并，且新设备不会自动同步其他设备的变化，但可以手动进行覆盖或合并备份。建议使用时以一个设备为主，其他设备手动从云端拉取备份。

## 纯纯写作为什么没有自动同步？

云同步必然要伴随着同步冲突、同步失败、覆盖丢失等问题，这基本上是无解的，特别是要在手机上处理冲突……想想最经得起考验的 git，都需要很多程序员参手和繁琐解决各种冲突，因此完全自动化的云同步可以说几乎不可能，除非各个端能够保持高速实时连接，瞬间同步……

目前对于云同步的支持已经提上日程，有望在 20.0 提供。

## 多设备使用时备份中的内容会自动合并吗？

在 19.10.0 版本更新后，纯纯写作支持「合并备份」，在点击恢复备份时，可以选择覆盖或合并。

如果您在多个设备上使用纯纯写作，现在可以比较方便地相互合并内容了，不过建议还是以一个设备为主，之后纯纯写作将提供更多多设备同步支持。

由于云备份的文件只会在云端文件夹中保留 25 份，因此当一个设备连续多次进行云备份时（当多应用协同编辑文档时，很容易出现这种情况），另一台设备的云备份有可能会被自动清理掉。

## 备份包很大使坚果云流量迅速用完怎么办？

- 可以尝试在【备份与云备份】设置中选择【资料库文件瘦身，删除历史记录】以清空备份中储存的历史记录。长期不清理历史记录会积累过多的历史版本，导致备份包变大。
  **历史记录即右上角菜单中【历史记录】选项所存储的内容，其中存储了本篇文章自创建以来的所有历史版本。**

- 可以进入废纸篓彻底删除之前删除的文章，由于暂时没有全选与清空废纸篓功能，此操作需要手动进行。
  **注意，撤销此操作需要恢复备份。**

- 网络等条件允许的话，也可以尝试使用其他的 WebDAV 服务，如 [Teracloud](https://teracloud.jp/)、[Box](https://www.box.com/)、[Yandex disk](https://disk.yandex.com/)、[城通网盘](https://www.ctfile.com/)、自行搭建的 WebDAV 等。
  **其他的 WebDAV 服务经常会受网络限制等情况无法使用或连接，严重时可能造成无法进行云端备份，请仔细考察其限制后慎重选择。**

- 开通坚果云专业版。
  并非打广告，有需求的可以考虑开通坚果云会员。

- 其它方法有待补充。

- 坐等 20.0 的自有云备份。
  ~~#DrakeetFlag~~

## Google Drive 找不到备份文件？

Google Drive 不支持用户对应用建立的云备份文件进行修改，因此即使应用内显示备份成功，用户仍无法在 Google Drive 上找到对应的文件夹。

由于上述原因，当用户使用 Google Drive 时，将**无法使用云读写**，请根据自己的情况与需求进行选择。

## 纯纯写作可以使用百度云备份吗？

**不可以。**

百度云是封闭的、不允许第三方接入（尽管有人破解出其私有 API，但使用此类接口可能要被百度告的），而且百度云还有速度限制，诸多原因，无法接入。

## 关于使用其他云盘备份的统一回复

目前纯纯写作支持使用 WebDAV、Dropbox 和 Google Drive 同步。

目前国内可以稳定公开免费使用的支持 WebDAV 的仅有坚果云一家，国外可以选择的有日本的 TeraCloud、俄罗斯的 Yandex Disk 以及美国的 Box 云盘，由于众所周知的原因，这些国外云盘在国内使用的体验只能说见仁见智。如果是要求每次使用都进行备份的用户、需要完全绝不丢失的用户、不能承担丢失部分文章风险的用户、网络条件会经常变化的用户等，还请**谨慎选择**国外云盘。

对于 OneDrive，曾经由于众所周知的原因，导致中国大陆的部分用户同步速度并不理想，因此纯纯写作在无法保证不会因此造成文章丢失的情况下，并没有支持使用 OneDrive 备份。近期有提供相关功能的计划，有望在 20.0 版本实现。

微云、百度网盘、微盘等国内网盘通常是不开放的网盘，并不提供（或很少提供）第三方应用可使用的链接途径，并且还存在许多其他原因（如限速等），因此纯纯写作暂不会选择国内的其他网盘。

## 为什么不能关闭自动备份？

本地自动备份无法关闭，否则纯纯写作将无法保证您的文本安全。但您可以放心，纯纯写作不会无限地备份导致您的手机剩余存储空间不断缩小，它会帮助您自动维持 25 份最新自动备份文件，过旧的备份版本将被删掉。当然，您手动点击纯纯写作的【立即备份】而产生的备份不会纳入在内，它们会永久存储于你的手机之中，除非你自行去把它们删除。

# 纯纯写作 Markdown 使用指南

## 何谓 Markdown？

Markdown 是一种用纯文本表达富文本内容的标记语言。它简单易学，纯纯写作支持 Markdown(MD)，您可以点击`快捷输入栏` 顶部的 `M↓` 勾选启用。

纯纯写作提供了许多 Markdown 快捷输入项，你可以点击`快捷输入栏`右侧的`小键盘图标`使用它们。

### 注意事项

1. **空格**在 Markdown 中是重要的组成成分，不可缺失。

2. Markdown 所使用的标记多为**半角**，请勿与全角混淆。

3. Markdown 下**无法使用缩进**，有需要缩进的段落请手动插入缩进。

4. Markdown 并无完全统一的规范，纯纯写作遵循并实现了 CommonMark 的 Markdown 标准，某些第三方的 Markdown 在纯纯写作中**可能无法使用**（如`==高亮文本==`）。

5. 标题、列表、引用文本、表格、选择框、分割线等部件**无法在行内使用**，必须在**行首**才可以使用并渲染。

6. 一个你不一定发现的纯纯写作小知识：选中一些文本后，使用纯纯写作内部的快捷输入项或快捷 Markdown 标记，当快捷输入的内容光标位置在插入项中的时候（如插入括号并设定插入后光标在括号中），将会直接插入在选中文字的前后，而非替换掉这段文字。

7. 默认情况下 Markdown 规定，两段之间必须**空一行**或者在**段尾部空两格**，才能真正在渲染时换行，比如：

   ```md
   第一行
   
   第二行
   ```

   如果在纯纯写作设置页面开启 `GFM Line Breaks` 则只需要一个换行即可获得渲染时换行。因为`GFM Line Breaks`是默认打开的，因此本教程默认是依据打开 `GFM Line Breaks` 开关书写的。

8. 在本指南中，除表格部份外，均使用竖形制表符`|`代指光标落点。

## 正文部分

### 目录

Markdown 的目录可以通过`[TOC]`生成，但纯纯写作暂不支持目录自动生成，近期内无相关支持计划。

### 标题

Markdown 的标题是用井号`#`加空格来表示的，而`#`的多少就代表着标题的层级，从少到多一共有六个层级。

标题的文字内容填充在空格后面。举例如：

```md
# 一级标题

## 二级标题

### 三级标题

#### 四级标题

##### 五级标题

###### 六级标题
```

标题实际上应该在前后都插入相同数量的井号`#`（如：`## 二级标题 ##`），纯纯写作中无需这样做。

另一种标题样式是由至少三个等于号`=`组成一级标题或至少三个短连接线/减号`-`组成二级标题，此样式应当插入在对应标题文本下方的一行。

需要注意的是，在文本与短连接线之间不可以有空行，否则会被识别为分割线。

### 加粗/斜体/粗斜体

这三个东西放在一起说，主要是因为它们所主要使用的标记符号是一样的，都是星号`*`或者下划线`_`，区别只在于符号的多少。

斜体是由前一后一两个星号或下划线组成的：`*斜体文本*`、`_斜体文本_`

加粗通常是由前二后二四个星号或下划线组成的：`**加粗文本**`、`__加粗文本__`

而粗斜体以此类推，是由前三后三六个星号或下划线组成的：`***粗斜体文本***`、`___粗斜体___`

纯纯写作中未提供下划线式的快捷输入项，因此建议使用星号来加粗或斜体。

### 删除线/下划线

删除线与下划线都是文字加线，就放在一起说了。

删除线是由前二后二四个波浪线组成的：`~~删除线文本~~`

而在 Markdown 中是无法直接插入下划线的，因此就需要使用行内的 HTML 标记`<u>|</u>`来插入下划线。

将文字插入在`<u>|</u>`标记中即可实现下划线的效果，示例：`<u>下划线文本</u>`

### 有序列表

有序列表的标记方式较为简单，数字加句点加空格即可：`1. 第一点`

换行即可自动补全下一行的序号。

### 无序列表

无序列表有三种可以使用的方式，纯纯写作提供了其中常见的两种并对其提供了自动填充。

第一种是短连接线/减号`-`加空格：`- 减号列表`

第二种是星号`*`加空格：`* 星号列表`

除此之外，纯纯写作未提供快捷输入但是支持渲染的标记方式是加号`+`加空格：`+ 加号列表`

三者在实际使用上并没有什么区别。

值得注意的一点是，当在渲染连续的无序列表时，由同种标记组成的列表会距离较近，而不同标记组成的列表会距离较远，这一点在某些情况下会很实用。

有序列表和无序列表是可以互相嵌套的，可以通过在列表前加入至少两个空格来完成列表的嵌套。

### 引用

当需要引用一段话的时候，不妨试试引用标记，它是由大于号`>`加空格组成的：`> 被引用文本`

### 脚注

在需要添加脚注的文字后加上脚注名：`[^脚注名]`。 然后在文本的任意位置空一行(一般在最后)添加脚注：`[^脚注名]:脚注内容`，即可插入脚注。

注意：在脚注的冒号`:`后不应加入空格。

纯纯写作的脚注无法以小窗口打开，而是会直接跳转至浏览器，因此该功能目前实用性较差。

### 角标

Markdown 并未原生支持上下角标，但是在纯纯写作中可以通过 HTML 代码来实现这样的效果。

上角标的代码为：`<sup>|</sup>`；下角标的代码为：`<sub>|</sub>`。

举例：`引文<sup>[1]</sup>`、`C<sub>2</sub>H<sub>5</sub>OH`。

### 文字居左/居中/居右

Markdown 无法直接实现文字居中，因此使用了 HTML 代码`<p align="">|</p>`，纯纯写作默认提供的是`<p align="center">|</p>`居中，但是通过修改相应的位置代码就可以做到左中右都支持，左中右分别是 left, center, right。

文字位置的格式是：`<p align="位置">需要修改位置的文字</p>`

纯纯写作**无法使用**`<center>|<\center>`代码居中。

### 插入图片

插入图片是一个相对重要的功能，它的格式是：`![]()`。

前面的方括号填写的是图片名称，而后面括号填写的是图片位置。当你使用网络图片时应该填写它的网络位置，当你使用本地图片时应该用图片选择器选中或填写它的本地位置。

需要注意的是，在使用网络图床时，要注意保护个人隐私，选择值得信任的图床；在使用本地图片时，该图片不可以被移动或删除，否则将无法正常显示，同时该图片也无法随着 Markdown 文档一同分享与同步。

### 插入链接

与插入图片类似，其格式为：`[]()`。

在前面的方括号中输入链接描述，在后面的圆括号中输入链接即可，如：`[POPO 原創市集](https://www.popo.tw/index.html)`

### 插入表格

纯纯写作提供了快捷插入三列四行表格的快捷输入项。

在 Markdown 下的表格并没有 excel 那样非常多的格式，只有简单的几列几行的表格。

表格的基本构成部件是竖形制表符`|`、空格、冒号`:`和短连接线/减号`-`四个部件，制表符分隔表格的每一栏，空格确定表格内的文本内容，冒号确定表格中文本的位置，短连接线则负责标记表头与辅助确定表格中文本的位置。不多解释，直接上实例：

```md
| 左对齐 |  居中  | 右对齐 |
| :----- | :----: | -----: |
| left   | center |  right |
| left   | center |  right |
| left   | center |  right |
```

其实际显示效果为：

| 左对齐 |  居中  | 右对齐 |
| :----- | :----: | -----: |
| left   | center |  right |
| left   | center |  right |
| left   | center |  right |

需要注意的地方：

1. 插入表格时，表格的上一行必须为空行，否则表格不会被成功渲染。

2. `:---`代表内容和标题栏左对齐、`:--:`代表内容和标题栏居中、`---:`代表内容和标题栏右对齐。

3. `|`与`-`之间的多余空格会被忽略，不影响布局。

4. 内容和`|`之间的多余空格会被忽略，因此为了美观可以使用空格来对齐不同行的单元格，表头处`-`的数量至少要有一个。

5. 每行第一个`|`和最后一个`|`可以省略，因此在输入表格后的内容时应该多空一行，以防止下一行被认为是表格中的内容。

### 选择框

Markdown 的选择框是由短连接线/减号`-`与方括号`[]`组成的，通过在方括号中输入空格或字母 `x` 来确定是否选中该选择框。选择框的顺序是短连接线、空格、前方括号、空格或字母 `x`、后方括号、空格加需要选择的文本，这些内容缺一不可，纯纯写作的 Markdown 快捷输入项中已经提供了相应选择框的快捷输入方式，可以有效避免输入错误。

举例：`- [ ] 未选中`、`- [x] 选中`

### 页内快速跳转

页内的快速跳转需要有标题（h1~h6）支持。

插入到某个标题的跳转链接，即可在预览页面实现页内跳转。

其格式为：

```md
# title1

...

[Back to title 1](#title1)
```

此时在即时预览页面 Back to title 1 会显示为蓝色，点击它即可跳转至对应位置。

**注意：**

- 前面标题中井号 `#` 后有空格，而在跳转链接的括号中，井号 `#` 后无空格。
- 如果有标题中有空格，`#` 中的空格应当删去。（在某些规范中应被替换为 `%20`）
- 目前版本仅能在预览（预览&另存为）页面实现跳转，在即时预览中无法实现。

### 分割线

分割线是由至少三个的短连接线/减号`-`构成的，占单独一行。

需要注意的是，在文本与其下方的分割线之间应该加入一个空行，否则分割线上的文本会被识别为标题。

### 改变字符颜色

纯纯写作可以通过 HTML 的`<font color="">|</font>`来改变字符的颜色，格式为`<font color="颜色色号或常见颜色的英语单词">需要改变颜色的文本</font>`。

举例：`<font color="black">黑色文字</font>`、`<font color="#000000">黑色文字</font>`

注意：改变字体颜色与字符居中暂时**无法嵌套**；改变字体颜色在许多地方可能造成冲突而**无法显示**（如表格），**请谨慎使用**。

### 输入标记字符

如果你需要输入标记字符的本体，那你就需要看一下这一条了，Markdown 通过反斜线`\`来输入标记字符。

举例说明：`\*斜体\*`在 Markdown 中将会被渲染为`*斜体*`。

### 关于其他 HTML 代码

在 Markdown 中可以使用相当一部分 HTML 代码，而纯纯写作也对其做了一定的支持。如之前介绍的下划线`<u>|</u>`（`<ins>|</ins>`）、上下角标`<sup>|</sup>`、`<sub>|</sub>`等。

除此之外，还有相当一部分 HTML 代码是纯纯写作所支持的。有相关需求的用户可以自行实验纯纯写作是否对其进行了支持，本教程中便不再赘述。/

### 代码块

写作的时候一般用不上的东西，技术大佬应该不屑于看我这入门教程，就在最后简单说一下，Markdown 通过使用` ```|``` `来包含多行代码，使用`` `|` ``来包含行内代码。

纯纯写作支持代码高亮，在开头的` ``` `后输入语言名字即可。

举例：

````md
​```js

windows.addEventListener('load', function(){

console.log('windows loaded');

​```

​```python

def myfun(x):

    return(x**2)

​```
````

更多更全的 Markdown 使用指南可以参考[Markdown 编辑器语法指南](https://segmentfault.com/markdown)

# 纯纯写作 Markdown 使用常见问题

## 关于纯纯写作 Markdown 的使用规范与兼容性测试

纯纯写作的 Markdown 遵循 CommonMark 的 0.29 版本，参考链接：[CommonMark Spec](https://spec.commonmark.org/0.29/)

关于纯纯写作的 Markdown 可以使用该测试器进行测试：[CommonMark Markdown 标准测试器](https://spec.commonmark.org/dingus/)

## Markdown 的文本高亮（或其他一些代码）为何无法使用？

文本高亮的常见代码`==|==`并非 Markdown 原生的代码，而是其他第三方应用加入的代码，纯纯写作不支持这些非原生的代码。如果有需要可以尝试使用行内代码块（其代码为：`` `行内代码块` ``，纯纯写作中提供了快捷输入）代替，需要注意的是，行内代码块里不会渲染加粗、斜体、删除线、下划线等代码。

## Markdown 的居中为何无法使用 center 代码？

纯纯写作的居中与左右对齐只能使用 `<p align="center/left/right">|</p>` 代码来完成。因为 `<center>|</center>` 代码会出现无法正确渲染换行等 bug，所以纯纯写作取消了对此代码的支持。

## Markdown 导出图片或预览时有些地方未能正常显示？

新版的 Markdown 渲染器仍然有很多的小问题需要修复，还请理解开发者。如果介意的话可以在预览页面点击右上角的三个点切换旧版渲染器，此时，第三方字体将不能在预览与导出图片中显示。

# 纯纯写作桌面测试版常见问题解答

## 关于纯纯写作测试版使用体验的重要说明

**⚠️ 纯纯写作的桌面版仍在测试中，目前的使用体验非常初级，只提供了双向即时同步编辑当前文章这个功能，因此请不要对其抱有太高的期望，以免过度失望。如果您打算*仅仅*因为这个桌面版而付费，我强烈建议您重新考虑这件事情。请勿谓言之不预。⚠️**

## 桌面版在哪里下载？

[纯纯写作桌面版下载](http://writer.drakeet.com/desktop_zh) 与 Telegram 频道是目前纯纯写作桌面版的官方指定下载位置，考虑到 GitHub 和百度网盘的下载速度可能会较慢，在官方 QQ 群群文件中也有群友上传的版本。

除此之外请用户不要轻易相信由第三方提供的版本，因使用未知来源的版本造成的档案丢失、内容被泄漏等问题，恕难提供帮助。

## 如何连接桌面版？

保持手机与电脑处于同一个 WIFI 网络或热点下，打开手机版后点击右上角的云图标，点击“连接纯纯写作桌面版”，将显示的 IP 地址输入于桌面版中的输入栏中，即可与桌面版即时连线，双向同步编辑目前文章。

- 若您看到多行 IP 地址，请逐一尝试连线它们。
- Windows 版存放路径中不能包含中文目录，否则将会无法使用！

## 为什么桌面版打不开？

- 纯纯写作桌面版目前仅有 64 位元的版本，请首先检查电脑控制面板中的“系统”确认自己是否是 32 位元作业系统。
- 请确认安装了你当前所使用系统的对应版本。
- Windows 版的存放路径不能含有中文目录，请检查你的存放路径是否有中文。

## 为什么手机与桌面版连接不上？

- 请检查你的设备是否在同一网络下。
- 检查你的 IP 地址是否已经正确输入。
- 检查电脑的防火墙是否阻止了桌面端纯纯写作连接网络（或公共网络），如果有，请允许纯纯写作连接至网络。
- 检查你所使用的 WIFI 网络是否打开了 AP 隔离，许多公共场所（如学校、企业、餐饮店等）的 WIFI 网络会打开 AP 隔离，防止用户之间互相连接造成关键资料遗失。此时可以通过手机/电脑开启热点，另一设备连接热点以解决该问题。

## 为什么桌面版与手机的连接经常断开？

此情况一般是由手机息屏后自动清理后台应用或无线网络不稳定造成的，因此很难非常有效地避免此情况的发生。

目前纯纯写作电脑版在相当一部分机型下可以正常连接并使用，将来纯纯写作将尝试进一步加强与电脑端连接状态下的应用保活。以下提供几点可能有助于连接稳定的建议：

- 通过各种手段防止纯纯写作应用后台被清理，如：将纯纯写作后台挂锁、将纯纯写作列入耗电限制白名单、关闭息屏后自动清理后台功能 等。可以参考并借鉴 [Don’t kill my app!](https://dontkillmyapp.com/) 中的应对方法。
- 尽量保证无线信号的强度和连接稳定性，避免因距离路由器距离过远而导致连线不稳定。目前可以采用的解决方式是使用手机连接 WLAN（非必选，但此方式能节省流量且不会增加连线页面的 IP 数量）后开启热点，然后使用电脑连接热点，使二者保持较近距离。

## 为什么开启自动连接后，仍然不能自动连接到桌面版？

当你数次切换网络后，手机的 IP 地址可能会发生变化，导致不能自动连接到桌面版。

此时可以在手机的 WLAN 设置中选择 【静态 IP 地址】，这样当在此 WLAN 下使用时，将不再会无法自动连接桌面版。

# 纯纯小八卦

## 为什么昵称开发者 Drakeet 为爪爪？

因为 Drakeet 的前三个字母 dra 的读音是爪，取叠音就为爪爪(DraDra)。

## 有人说开发组有四个成员，分别是谁呢？

开发组四个成员包括 Drakeet（应用开发者、颜值担当、侍奉其他三位主子的苦劳力）、小白（颜值&卖萌担当、bug 生产者）、小迷雾（颜值&卖萌担当、bug 生产者）、瓜瓜（颜值&卖萌担当、iOS 版特约预定开发者，因为还不到两岁所以在绝赞拖更中）。

## 纯纯写作的小彩蛋

在会员页面有隐藏的小彩蛋，通过彩蛋可以见到纯纯写作曾经设计过但最终放弃的一个图标和一个弹窗彩蛋。
