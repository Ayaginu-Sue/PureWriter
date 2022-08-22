# Pure Writer User Manual<!-- omit in toc -->

This is a manual for **Pure Writer**, which is about the features of the app and basic troubleshooting.

The manual contains several parts, including [Pure Writer Q&A](#pure-writer-qa), [Pure Writer Backup & Sync FAQ](#pure-writer-backup-sync-faq), [Pure Writer Markdown User Guide](#pure-writer-markdown-user-guide), [Pure Writer Markdown FAQ](#pure-writer-markdown-faq), [Pure Writer Desktop Alpha FAQ](#pure-writer-desktop-alpha-faq).

Please be sure to make use of in-page search. For desktop devices use Ctrl+F, and for mobile devices, you can find a corresponding feature somewhere in your browser's menu.

## Table of Contents<!-- omit in toc -->

- [Pure Writer Q&A](#pure-writer-qa)
  - [About different modes of Word Count](#about-different-modes-of-word-count)
  - [About landscape mode](#about-landscape-mode)
  - [Shortcut bar](#shortcut-bar)
    - [About shortcuts](#about-shortcuts)
  - [About cursor's position of text shortcuts](#about-cursors-position-of-text-shortcuts)
  - [Insert current time through text shortcuts](#insert-current-time-through-text-shortcuts)
  - [Hide status bar and its known issues](#hide-status-bar-and-its-known-issues)
  - [About formatting tools](#about-formatting-tools)
  - [Find & replace in texts](#find-replace-in-texts)
  - [Search Articles / Jump to Articles quickly](#search-articles-jump-to-articles-quickly)
  - [Is there a word limit for one single chapter?](#is-there-a-word-limit-for-one-single-chapter)
  - [How can I check the time created / modified of a chapter?](#how-can-i-check-the-time-created-modified-of-a-chapter)
  - [Opening external documents](#opening-external-documents)
  - [Cannot open / import a document that is too large](#canno-open-import-a-document-that-is-too-large)
  - [Custom font and font size](#custom-font-and-font-size)
  - [Change the transparency of the text](#change-the-transparency-of-the-text)
  - [Adjust the left and right margin of the text](#adjust-the-left-and-right-margin-of-the-text)
  - [Adjust line / paragraph spacing](#adjust-line-paragraph-spacing)
  - [Is it possible to justify the text?](#is-it-possible-to-justify-the-text)
  - [Legibility issues after changing themes / wallpapers](#legibility-issues-after-changing-themes-wallpapers)
  - [Is it possible to change the color of the text?](#is-it-possible-to-change-the-color-of-the-text)
  - [Redo content that was mistakenly undone](#redo-content-that-was-mistakenly-undone)
  - [Restore the content of an article back to an earlier version through History](#restore-the-content-of-an-article-back-to-an-earlier-version-through-history)
  - [Only one line / paragraph of the article can be clearly seen](#only-one-line-paragraph-of-the-article-can-be-clearly-seen)
  - [Is it possible to save the article as .docx or .epub?](#is-it-possible-to-save-the-article-as-docx-or-epub)
  - [Articles exported by this app cannot be displayed correctly in other softwares](#articles-exported-by-this-app-cannot-be-displayed-correctly-in-other-softwares)
  - [Clicking outline links in Time Machine only opens Books list](#clicking-outline-links-in-time-machine-only-opens-books-list)
  - [Typewriter Mode](#typewriter-mode)
  - [Read-only Mode](#read-only-mode)
  - [Turn on Read-only Mode](#turn-on-read-only-mode)
  - [Turn off Read-only Mode](#turn-off-read-only-mode)
  - [Insert a new article at different positions](#insert-a-new-article-at-different-positions)
  - [Options for the few people](#关于少数派选项)
  - [The interface gets abnormally color inverted](#the-interface-gets-abnormally-color-inverted)
  - ["This is a Pro feature" pop-ups](#this-is-a-pro-feature-pop-ups)
  - [Is there a huge feature loss without Pure Writer Pro?](#is-there-a-huge-feature-loss-without-pure-writer-pro)
  - [How does this app keep my custom wallpapers?](#how-does-this-app-keep-my-custom-wallpapers)
  - [Are wallpapers saved in backups?](#are-wallpapers-saved-in-backups)
  - [Is it possible to customize the background when saving articles as images?](#is-it-possible-to-customize-the-background-when-saving-articles-as-images)
  - [Something is wrong with Indent](#something-is-wrong-with-indent)
  - [No indentation when writing](#no-indentation-when-writing)
  - [Cannot save as .txt file, only .md is shown](#cannot-save-as-txt-file-only-md-is-shown)
  - [Use Markdown / LaTeX in the app](#use-markdown-latex-in-the-app)
  - [Markdown Panel](#markdown-panel)
  - [Is it possible to render Markdown in real time in this app?](#is-it-possible-to-render-markdown-in-real-time-in-this-app)
  - [It takes too much time to open the app](#it-takes-too-much-time-to-open-the-app)
  - [App freezes when switching to Trash or other books](#app-freezes-when-switching-to-trash-or-other-books)
  - [Is it possible to insert bold text or images in articles?](#is-it-possible-to-insert-bold-text-or-images-in-articles)
  - [The app automatically creates an article / prompts me to "Skip" on startup](#the-app-automatically-creates-an-article-prompts-me-to-skip-on-startup)
  - [Is there a limit to the number of devices that can log into a Pure Writer account at the same time?](#is-there-a-limit-to-the-number-of-devices-that-can-log-into-a-pure-writer-account-at-the-same-time)
  - [Pure Writer Pro is lost but I have paid for it on Google Play](#pure-writer-pro-is-lost-but-i-have-paid-for-it-on-google-play)
  - [Cannot use Enter to insert line breaks on Chromebooks or Android x86 devices](#cannot-use-enter-to-insert-line-breaks-on-chromebooks-or-android-x86-devices)
  - [Cannot customize some of the features in the app](#cannot-customize-some-of-the-features-in-the-app)
  - [Is there an iOS version of Pure Writer?](#is-there-an-ios-version-of-pure-writer)
  - [Is there a risk of articles being leaked by using Pure Writer?](#is-there-a-risk-of-articles-being-leaked-by-using-pure-writer)
- [Pure Writer Backup & Sync FAQ](#Pure Writer Backup & Sync FAQ)
  - [关于云备份](#关于云备份)
  - [为什么坚果云的 WebDAV 显示不能登录？](#为什么坚果云的-webdav-显示不能登录)
  - [如何配置云备份？](#如何配置云备份)
  - [如何在新设备中恢复旧设备中的文章？](#如何在新设备中恢复旧设备中的文章)
  - [为什么坚果云的 WebDAV 显示不能登录？](#为什么坚果云的-webdav-显示不能登录-1)
  - [错误提示：您的 WebDAV 配置不完整或不正确](#错误提示您的-webdav-配置不完整或不正确)
  - [错误提示：帐号和密码错误](#错误提示帐号和密码错误)
  - [错误提示：Error: Error contacting (403)](#错误提示error-error-contacting-403)
  - [坚果云提示 503 错误](#坚果云提示-503-错误)
  - [新设备恢复备份后为什么还是初始文章？](#新设备恢复备份后为什么还是初始文章)
  - [纯纯写作支持自动同步吗？](#纯纯写作支持自动同步吗)
  - [纯纯写作为什么没有全自动同步？](#纯纯写作为什么没有全自动同步)
  - [多设备使用时备份中的内容会自动合并吗？](#多设备使用时备份中的内容会自动合并吗)
  - [在多个设备上使用时，应该如何保证正在编辑的版本为最新？](#在多个设备上使用时应该如何保证正在编辑的版本为最新)
  - [备份包很大使坚果云流量迅速用完怎么办？](#备份包很大使坚果云流量迅速用完怎么办)
  - [在 Google Drive 找不到备份文件？](#在-google-drive-找不到备份文件)
  - [纯纯写作可以使用百度云/阿里云备份吗？](#纯纯写作可以使用百度云阿里云备份吗)
  - [关于使用其他云盘备份的统一回复](#关于使用其他云盘备份的统一回复)
  - [为什么不能关闭自动备份？](#为什么不能关闭自动备份)
- [纯纯写作 Markdown 使用指南](#pure-writer-markdown-user-guide)
  - [何谓 Markdown？](#何谓-markdown)
    - [注意事项](#注意事项)
  - [正文部分](#正文部分)
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
- [纯纯写作 Markdown 使用常见问题](#pure-writer-markdown-faq)
  - [关于纯纯写作 Markdown 的使用规范与兼容性测试](#关于纯纯写作-markdown-的使用规范与兼容性测试)
  - [Markdown 中文本高亮或其他部分代码为何无法使用？](#markdown-中文本高亮或其他部分代码为何无法使用)
  - [Markdown 的居中为何无法使用 center 代码？](#markdown-的居中为何无法使用-center-代码)
- [Pure Writer Desktop Alpha FAQ](#Pure Writer Desktop Alpha FAQ)
  - [关于纯纯写作测试版使用体验的重要说明](#关于纯纯写作测试版使用体验的重要说明)
  - [桌面版在哪里下载？](#桌面版在哪里下载)
  - [如何连接桌面版？](#如何连接桌面版)
  - [为什么桌面版打不开？](#为什么桌面版打不开)
  - [为什么手机与桌面版连接不上？](#为什么手机与桌面版连接不上)
  - [为什么桌面版与手机的连接经常断开？](#为什么桌面版与手机的连接经常断开)
  - [为什么开启自动连接后，仍然不能自动连接到桌面版？](#为什么开启自动连接后仍然不能自动连接到桌面版)
  - [桌面版文字有重影现象如何解决？](#桌面版文字有重影现象如何解决)
- [纯纯小八卦](#纯纯小八卦)
  - [为什么昵称开发者 Drakeet 为爪爪？](#为什么昵称开发者-drakeet-为爪爪)
  - [关于魔法代码](#关于魔法代码)
  - [纯纯写作的小彩蛋](#纯纯写作的小彩蛋)

# Pure Writer Q&A

## About different modes of Word Count

Word Count is originally designed for Chinese, and has 3 modes: Exclude spaces and line breaks; Include all symbols and text; Exclude all punctuations, spaces, and line breaks. These modes basically tells what they do, so nothing more on them.

However when writing English texts, if the counter counts letters instead of words, you can turn on "Count words individually" in the settings to go back to normal. In this case, you can only use Exclude spaces and line breaks for Chinese content if exists.

## About landscape mode

Pure Writer isn't really doing a good job in landscape mode when using phones, for their screens are too small. It's recommended to use Android tablets or Android desktops when using Pure Writer in landscape mode.

When using devices with a larger screen, you can open "Landscape settings & guidelines" on the right of the top bar. There are some optimization options for large screen devices in it.

Shortcut keys for shortcut entries: Press and hold the Ctrl or Alt key on the physical keyboard to use the first 10 shortcut entries.

**Turn on landscape mode**: Enable "Auto-rotate screen" (or disable "Orientation Lock"), then rotate your device to enable landscape mode.

Cannot find those two settings? Open the settings app on your phone, and find "Display" or "Display and Brightness", or something alike, and then you'll see "Auto-rotate screen" or "Orientation Lock". You can search the keyword if applicable.

When using Android tablets or Android desktops, resizing the window of the app may also enable landscape mode.

## Shortcut bar

Shortcut bar is a mini-bar just above your on-screen keyboard. You can customize the entries there, and even add your own text shortcuts, like inserting time and date, inserting names or inserting punctuations.

Click `⊕` or `⊕ Text Shortcut` to create your own text shortcuts, or just add an entry that we've already provided for you. Hold existing shortcuts to sort, modify or delete them. The position where your cursor is in the "Shortcut content" field will be the cursor's position when inserting the text shortcut.

Click `⌘` (when using Markdown, `M↓`) to open Formatters menu (or Markdown Panel when using Markdown).

Note that when you've selected some texts, and that the shortcut you are going to use has a cursor position inside the shortcut content, the content will be added before and after the selected texts, instead of replacing them, which might be different from other softwares. This is a feature for situations like when you want to add quotes or parentheses before and after certain sentences or paragraphs.

To disable shortcut bar, open settings and disable it in Options for the few people.

### About shortcuts

`⊕ Text Shortcut` currently provides some of the options that we've already provided for you, like Undo and Redo, Indent, Format, Scroll to bottom, Scroll to top, Copy selected or current full text, Search Articles / Jump to articles quickly, Cursor Joy-Con (when enabled in Options for the few people). You can choose Text Shortcut or other provided options for each entry when creating or editing.

We still want to improve the shortcut bar, so if there's anything you want to suggest, be sure to tell us.

## About cursor's position of text shortcuts

Again, each shortcut entries consists of two parts: Shortcut content (required) and Shortcut description. The final position of the cursor is determined by the cursor's position in the Shortcut content field when setting.

For example, if the Shortcut content field is `【｜】`, where `|` represents your cursor and `【` `】` being full-width brackets, then clicking on the entry will insert the `【】`, with cursor in the middle; if the Shortcut content field is `【】｜`, where `|` represents your cursor (again), then clicking on the entry will insert the `【】`, with the cursor after them.

## Insert current time through text shortcuts

In this case, Shortcut content field must follow the format of `${<format>}`.

There is a cheatsheet for the actual time format, but don't worry if you cannot understand, as there are some **examples** after the sheet.

![Cheatsheet](https://github.com/Ayaginu-Sue/PureWriter/blob/main/Image/time_shortcut.jpg)

Here are some examples:

**Insert time in 12-hour format**: `${GG yyyy-MM-dd E aa hh:mm:ss.SSS(z)}`

**Example output**: AD 2022-08-22 Mon PM 06:59:50.093(GMT+08:00)

**Insert time in 24-hour format**: `${GG yyyy-MM-dd E HH:mm:ss.SSS(z)}`

**Example output**: AD 2022-08-22 Mon 19:01:49.443(GMT+08:00)

For more, check this link: [Customizing Formats](https://docs.oracle.com/javase/tutorial/i18n/format/simpleDateFormat.html).

## Hide status bar and its known issues

Hide status bar, or Status bar focus mode, can hide most of the icons from the status bar, preventing them from disturbing you.

You can turn it on or off under "Spacings & Margins" menu, which is on the right of "Paragraph Spacing" option. Some devices (e.g. Xiaomi and Redmi devices) don't support it due to their system limitations, so on these devices the option will be hidden.

The experience may vary due to different system implementations on different devices, so if your exact device runs into problem with this on, you can only turn it off as we can't do anything about it.

## About formatting tools

Formatting tools, or formatters, helps to make your article consistent in a certain format.

Currently we provide these options: Leave a blank line between paragraphs; Remove all blank lines between the paragraphs; Insert a space between East Asian and Latin text; Insert indentation at the start of all paragraphs; Remove indentation; some Chinese options that provide a machine transliteration between Simplified Chinese and Traditional Chinese.

These are helpful when you are editing a long article; don't hesitate just because the name "Format" looks like the option to erase all your content on a disk.

## Find & replace in texts

Click "more" icon on the top bar of the editor, then click "Find & Replace" in the menu.

The "Find" field is the content you would like to search, and the "Replace" field is the content you want to use to replace the search result. Leave the "Replace" field blank if only searching for content. Select the results below the two fields you would like to replace when using "Replace" field.

Currently we provide some options like "Current Chapter", "Current Book", "All Books" and "Ignore Case" for filtering the search result. Buttons below these options basically do what they say, currently "Replace", "Select All", "Inverse All", "Hide Keyboard" and "Search Articles / Jump to Articles quickly".

**For searching for an article, use "Search Articles / Jump to Articles quickly" instead.**

## Search Articles / Jump to Articles quickly

This helps you to search for **articles with certain content** in the book when you happens to forget the exact article name, not search keywords in articles, thus this only displays the first occurence of the searched content in one article.

**Usage**: Enter the keywords or relevant content in the article that you would like to jump to. Multiple keywords or relevent content are seperated by **line breaks**. Only the first occurence of the keyword in one article is shown.

This can also be used as title name search or chapter name search, as it would also search the title anyway. Though there isn't a direct way to "search title name", by writing titles in a certain format (e.g. "Chapter X ..."), you can search for keyword in titles (e.g. "Chapter") at the same time to achieve a similar goal.

**Regular Expressions (Regex)**: You can search in regular expressions. Search the Web for a tutorial on Regex if you're interested.

## Is there a word limit for one single chapter?

There is **basically no word limit in a single chapter**. That is, the sky (your device's performance) is the limit!

In theory, Pure Writer can handle an article of 100 million Chinese characters without lagging, and that in reality, on developer's device, Pure Writer can handle an article of 10 million Chinese characters without lagging. Don't take out the test on your own though, as it may dramatically increase the size of the backup, causing Cloud Backup to fail. YOU HAVE BEEN WARNED.

In daily use, keep the word count **under 20 thousand (20,000)** for one chapter to get a smoother writing experience. Some low-end devices may start to lag when editing a chapter for more than 10 thousand words, but even for them, just viewing the article won't cause any lagging issue.

## How can I check the time created / modified of a chapter?

- Open the hamburger menu, click "More" icon, then tap "Zoom in".
- In the hamburger menu, click "Sort type" icon, tap "Type of time displayed", then select the option you want.

## Opening external documents

The app supports to open external plain text or Markdown documents.

Generally you can select one of these documents, and then select "Open with", and then "Pure Writer" in the Files app. If you are using other file manager apps, look up on their documentation for similar options.

## Cannot open / import a document that is too large

Previously, Pure Writer will lag or "freeze" when opening a large plain text file, and thus some users may report that "The app freezes" or "The phone isn't responding when using the app", which isn't true as the app is actively processing the file. Now, Pure Writer will refuse to import large files by opening external documents. If you still want to import a large file, copy & paste the content into the editor instead.

**Files that are too large are basically over 300 KiBs. This value may vary depending on your device's performance.**

## Custom font and font size

This is a Pro feature, but unpaid users can still try this feature for free.

Android 10 and below: Place your TTF file under `/Documents/PureWriter/App`. Turn on "Custom font" in the settings and then restart the app.

Android 11 and above: Turn on "Custom font", select "Select font", then choose the font file.

For font size, see other settings. You can adjust title font size and content font size in the settings.

## Change the transparency of the text

Tap "more" icon on the top bar, tap "Spacing & Margins", then adjust "Text color Alpha / transparency (%)".

## Adjust the left and right margin of the text

Tap "more" icon on the top bar, tap "Spacing & Margins", then adjust "Left Margin" and "Right Margin".

## Adjust line / paragraph spacing

Tap "more" icon on the top bar, tap "Spacing & Margins", then adjust "Line spacing" and "Paragraph spacing".

## Is it possible to justify the text?

Android native TextView doesn't support justifying the text (align both ends of the text). While WebView can do this, the performance is pretty bad, so Pure Writer choose TextView.

We can do nothing about this, as it's an issue of Android itself, and thus should be solved by Google.

## Legibility issues after changing themes / wallpapers

Under "Themes & Wallpapers", select "Fixed, don't switch automatically", then choose "Force Black Text Color" or "Force White Text Color", depending on your wallpaper. No other colors are available.

## Is it possible to change the color of the text?

Currently, only black and white text color are supported, and we don't plan to support more colors for texts.

If you want to change the color of a certain part of texts, use Markdown and relevant HTML tags.

## Redo content that was mistakenly undone

Tap "more" icon on the top bar, then select "redo" icon at the bottom of the menu.

The menu will disappear after tapping "redo", thus user can clearly see how their article will change.

Redo button is also available in shortcut bar. See relevant paragraphs for more information.

## Restore the content of an article back to an earlier revision through History

Tap "more" icon on the top bar, then select "History".

In History, you can see the history of the article (obviously), and selecting on a certain entry will allow you to preview the selected revision and decide if the article should be restored to that revision.

## Only one line / paragraph of the article can be clearly seen

"Typewriter Mode" is on. Turn it off by tapping "more" icon on the top bar, then selecting "Typewriter Mode".

## Is it possible to save the article as .docx or .epub?

Currently we don't support these, sorry. There is a plan for saving articles as .docx files, but it's of low priority. Other formats like .epub require more work and changes in the code base, so support for these formats are not guaranteed to come in later versions.

## Articles exported by this app cannot be displayed correctly in other apps

The app exports files in text encoding of UTF-8, thus it means that other apps you use may not support or fail to recognize the file as UTF-8 text encoding. Change the text encoding to UTF-8 in that app, or use an app that supports UTF-8.

## Clicking outline links in Time Machine only opens Books list

Outlines are no longer there, for you can just create another book as your outline. The Books list pops out to tell you that you can create another book as your outline, and then open that book in Editor 2 to work just as fine as the original outline.

## Typewriter Mode

When turned on, the current paragraph is highlighted, allowing the user to focus more on the current text, and to a certain extent, avoid people behind the user to see all the text.

If you accidentally turned it on, just turn it off by tapping "more" icon on the top bar, then selecting "Typewriter Mode".

## Read-only Mode

It's also known as "Reading Mode", for you can easily navigate through the article without accidental deletion of the text, thus ensuring that the content is **SAFE**.

For Advanced read-only mode:

When the cursor is not visible, you need to double-click the editor to show the cursor;

When the cursor IS visible, click the editor once to show the cursor;

When the cursor IS visible but the keyboard is collapsed, Go Back (either by tapping the Go Back button or swipe from the edge of the screen if applicable) and then you are now at Read-only Mode again.

## Turn on Read-only Mode

Read-only Mode is under the bottom-right corner menu `⊕`, click or hold the button to turn on Read-only Mode in the list.

## Turn off Read-only Mode

Double-clicking the editor will show the cursor and start editing, thus temporarily allow you to write.

Click or hold the button of the bottom-right corner menu `⊕` to turn off Read-only Mode in the list.

## Insert a new article at different positions

There are three related options in the bottom-right corner menu `⊕`: Insert a new article at the bottom of the article list; Insert a new article at the bottom of current Folder; New article after the current article. Hold the button to see these options.

## Options for the few people

"Options for the few people" are some options that developers don't recommend to change but have to provide for user requests. Options there includes Smooth cursor (default on), Align title to center (default on), Shortcut bar (default on), Comma to full stop when entering a newline (default off) and so on.

## The interface gets abnormally color inverted

This happens in devices that provides a "more powerful dark mode" that forces apps to invert colors, thus causing colors of some parts that are already inverted to be inverted again (thus causing situations like white text on white background). Pure Writer cannot do anything about it if the device doesn't provide a way to stop forcing some of the apps to invert colors.

Solutions:

- In phone's settings app, exclude Pure Writer from the dark mode.
- Do not use the dark mode provided by Pure Writer.
- Report it to the device's manufacturer, so that they provide a way to disable forcing invert colors for certain apps.

## "This is a Pro feature" pop-ups

Custom wallpapers, Preview (including Markdown Quick Preview), Export, Material Design 2, Find & Replace, Export this Book, Editor 2, and Custom font are so-called Pro features that can be used without any limit by purchasing Pure Writer Pro.

Some of these provide trials for unpaid users, at the cost of displaying a pop-up every time they use.

If purchased, but still experiencing pop-ups, go to "Pure Writer Pro", then check if your Pure Writer account or Google account is logged in. If not, log in again, and open Google Play to make sure that your Google account is logged in.

## Is there a huge feature loss without Pure Writer Pro?

There **ISN'T**. The core features of Pure Writer are free, which includes excellent editor experience and Cloud Backup. Most of the features can be used without paying anything and, there aren't any third party advertisements even when unpaid.

Each year, Pure Writer will offer a discount on November 11. You can wait for the discount if you don't feel so hasty to buy a Pro at the current price. There might be some other discounts from time to time, so stay tuned.

## How does this app keep my custom wallpapers?

In "Themes & Wallpapers", the app will remember the wallpaper that the user once used, so that if they want to change it back, it wouldn't be a trouble.

The app keeps two of the most recent custom wallpapers. Hold the item of old wallpapers to delete them.

## Are wallpapers saved in backups?

Backup includes settings, which indeed includes the URL to the image or RGB value, and these wallpapers can be restored through backups. But if you choose "Local image", the exact image will not be included in the backup and you cannot recover that wallpaper solely through Pure Writer backups.

## Is it possible to customize the background when saving articles as images?

**Nope.**

Well, the article can get quite long, and thus custom background images had to be stretched, certainly not what users are expecting. There might be some solutions tho:

1. Use some color gradient when the custom background image isn't long enough. However images vary and thus cannot really achieve a universal good result.
2. Tile the image, just like wallpapers on desktops. Well, again, images vary, and when the image is overly complicated, the final image could be quite large in file size, thus is harder to download and may get compressed on social media.

## Something is wrong with Indent

There are two reasons, most frequent though: Custom font and wrong languages.

- Custom font may not contain the glyph for the indent, or the glyph is wrong, in which cases the indent may not be long enough (indent displayed as two half-width spaces but expected two full-width spaces), or the indent is shown as tofus or dots.

  Pure Writer uses two full-width spaces (U+3000) for indentation in Chinese. Some fonts however may set the character's width half as it should be, or even totally change the glyph.

  **Solution**: Change to another font (or disable custom font) that can display the character U+3000 normally. Or, you can manually fix the problem by editing the font file if you know how to do that.

- You changed the language, in the app or through system settings.

  Pure Writer is international, and thus has different indentation rules for different languages. For example, in English the indentation is 4 half-width spaces, while in Japanese and Korean the indentation is 1 full-width space and so on.

  **Solution**: Change the language back, or change the app's language according to your text.

## No indentation when writing

- Is Markdown mode on? Turn it off as Markdown doesn't support the indentation provided by the app.
- If Markdown mode is INDEED OFF, go to settings and be sure the "Indent" option is on.

## Cannot save as .txt file, only .md is shown

Articles with Markdown mode on are exported as .md, which is expected.

To save articles as .txt files, tap `M↓` icon on the top bar to turn Markdown mode off.

## Use Markdown / LaTeX in the app

Pure Writer supports Markdown and certain HTML tags (like underline, `<u>Text</u>`), as well as LaTeX formulas, both inline and display style. However, the positions of the LaTeX formulas may be a bit too close to the bottom of a line than what you will expect.

To turn on Markdown / LaTeX, tap `TXT` icon on the top bar, and make it `M↓`.

To preview, tap the `M↓` button on the left of the `⊕` button.

Wanna try Markdown? read about the brief introduction written by the developers: [Simple Markdown Guide](https://writer.drakeet.com/markdown), or just read the part [Pure Writer Markdown User Guide](#pure-writer-markdown-user-guide) in this manual.

更多关于 Markdown 使用中的问题请参考：[纯纯写作 Markdown 使用常见问题](#pure-writer-markdown-faq)。

## Markdown Panel

Markdown Panel整合了一些常用的 Markdown 符号，Markdown 写作者可以使用它更方便地输入 Markdown 符号。

在 Markdown 模式下点击快捷输入列最左端的`M↓`图标即可打开 Markdown 快捷输入页面；而非 Markdown 模式下需要打开格式化选项后向左移动到 Markdown 快捷输入页面。

在此处，你可以快捷输入部分 Markdown 标签，如加粗、斜体、插入图片等，不过此页面的东西**不支持修改**。

## Is it possible to render Markdown in real time in this app?

纯纯写作曾经尝试过支持 Markdown 实时渲染，但是测试后发现，现今移动设备的性能尚不能满足预期，因此，在移动设备的性能达标之前，纯纯写作将不会提供这个功能。

## It takes too much time to open the app

出现此情况一般是因为在纯纯写作中打开了过长的文章。由于手机的性能有限，所以打开很长的文章时会有一定的等待时间。

纯纯写作是编辑器，而非阅读器，请尽量避免使用纯纯写作打开过长的文章。如果发现因过长的文章导致启动缓慢，请彻底删除外部导入的超大文章。

## App freezes when switching to Trash or other books

**如果此条目未能解决该问题，请向开发者（邮箱：drakeet@drakeet.com）写邮件反馈。**

这一般是由于废纸篓中储存的文章过多，超出了手机的运算能力引起的。此时纯纯写作**并没有卡顿**，而是在加载废纸篓中的文章，因此应用无法做出任何应答，会让人误以为应用卡死，请稍作等待至全部文章加载完成，打开后请尽量删除或清空废纸篓中的内容，以避免再次卡顿。

**请注意，此时切勿退出应用，否则可能导致下次打开应用时闪退。**
发生闪退的解决方法：

1. 确保有做过备份，如未进行云备份则在本地备份文件夹 `Documents/PureWriter/backups/Auto` 或自己设定的备份文件夹中复制并保留未打开废纸篓时的备份包（非最新备份包，建议多保存几个，以备不时之需）。
2. 卸载纯纯写作并重新安装。
3. 通过本地或云端保留的备份包恢复发生闪退前的备份。
4. 此时即可重新进入废纸篓页面并等待其页面开启。

**此情况也可能发生于切换到其他书籍或超长文章时，多发生在「打开不常打开却经常向其中移动内容的书籍」或「由高配手机切换到低配手机、且用户有非常巨大的文章」时。**

## Is it possible to insert bold text or images in articles?

纯纯写作是一个纯文本编辑器，它致力于提供优秀的纯文本写作体验和辅助。图片属于富文本内容，无法在纯文本中直接表达，但可以使用 Markdown 用纯文本来描述富文本内容，纯纯写作支持 Markdown。

而且如果支持富文本或图片，则会使得编辑器的复杂度大幅上升，复杂就意味着容易出错且难以做到完美，专注才能做到极致。

所以很抱歉，纯纯写作从一开始就没有计划支持富文本，以后也不会计划做相关支持。

希望能得到你的理解。

如果你打算尝试 Markdown，你可以在这里获得来自开发者的简要介绍：[Markdown简明教程](https://writer.drakeet.com/markdown)，也可以在本教程中阅览[纯纯写作 Markdown 使用手册](#纯纯写作-Markdown-使用手册)。

## The app automatically creates an article / prompts me to "Skip" on startup

此情况一般是正在使用的某个需要辅助权限/无障碍权限的 启动跳过 类软件造成的。要避免出现此情况请关闭相关应用或将纯纯写作设置为跳过白名单。

关于辅助权限，其实很危险，而且将严重影响系统性能。建议普通用户尽量避免使用需要无障碍权限的应用（或服务），无障碍服务本质上是为了服务盲人等不方便操作的用户，滥用此功能可能导致手机性能的损耗甚至个人信息的丢失。

**外链：**[Android 无障碍服务导致的整机卡顿案例分析](https://www.androidperformance.com/2019/01/21/android-performance-case-jank-accessbility/)

**增补：** 纯纯写作在版本 14.9.5 更新中已禁止 启动跳过 类软件点击创建新文章。

## Is there a limit to the number of devices that can log into a Pure Writer account at the same time?

目前一个纯纯写作账号最多只能同时在 3 个设备上登录，如果在第 4 个设备上登录，则之前最早登录的设备会被退出登录。

## Pure Writer Pro is lost but I have paid for it on Google Play

这是系统中谷歌账户的缓存过期失效了，请重新确保你的系统中登录了已付费的谷歌账号。

付费状态的缓存可能会定期失效，必须保持登录谷歌账号才能一直保持激活状态，以避免有人恶意借用账号或刷退款。

当遇到失去谷歌激活时**最有效直接的方法**是：退出所有谷歌账号，只登录已付费纯纯写作的谷歌账号，然后打开纯纯写作，以便准确识别是否付费，并且产生新的缓存。

## Cannot use Enter to insert line breaks on Chromebooks or Android x86 devices

这一般是系统的问题，许多系统修改了换行的键位，请尝试使用 Ctrl+Enter 或者 Shift+Enter 换行，许多系统采用此键位作为换行的热键。

如果不能成功建议先在网络上查找一下你所使用系统的换行方式。

## Cannot customize some of the features in the app

如果什么都开放给用户自定义，只会使得软件设置页面变得密密麻麻，像飞机仪表盘一样，令人无所适从，心生恐惧，同时也会使得更关键的设置项可达性下降。好的用户体验应该是帮用户考虑好、设计好，开箱即用。另外，如果什么都允许修改，则很多用户会把纯纯写作改得很难看、变成杀马特风格，这是开发者与大多数用户所不愿意见到的。

## Is there an iOS version of Pure Writer?

**没有。**

纯纯写作是由 Drakeet 一个人独立开发的，目前的目标是不断把 Android 端做到极致。纯纯写作现在没有 iOS 版的计划，因为优秀的编辑器应该是最难做的产品，若要将纯纯写作复刻到 iOS 上工作量巨大而且难点众多，你会发现许多优秀的 iOS 编辑器同样没有 Android 版，这不是没有原因的，因为复刻的工作量实在太大了，而且纯纯写作目前还比较小众，并不值得去开发 iOS 版，十分抱歉。

## Is there a risk of articles being leaked by using Pure Writer?

**纯纯写作不会窃取用户的文章。**

窃取用户的文章对纯纯写作并没有什么实际用处，是毫不值得且败坏声誉的行为。

纯纯写作并没有对用户的备份包做特别的保护和加密，因为这样会严重影响打开与编辑文章的速度，占用手机的性能；纯纯写作的文章备份会且仅会保存在至多两个地方——本机的公用备份文件夹（其中手动备份与自动备份的位置不同）与用户自己设定的云盘中对应的文件夹（如果没有设置云备份则不会在任何云端保存，但文章在换机、遗失、损坏的时候可能会丢失），除此之外不会另作他用。因此在一定程度上对备份包的加密是无意义的，如果有人想要窃取你的文章，并且能从你的手机本机/云盘供应商那里获取到你的备份包，那么对于此人来说加密也是形同虚设的。

注意：纯纯写作不能保证纯纯写作破解版中文章的安全，请使用正版纯纯写作，纯纯写作的免费版是完全足够普通用户正常使用的。

# Pure Writer Backup & Sync FAQ

## 关于云备份

纯纯写作支持云备份，它非常简单，一劳永逸，万无一失。云备份非常重要，因为即使纯纯写作已经提供了多重防范与保护，却仍然有人因为不愿意进行云备份而在手机丢失或刷机时失去全部的文章。没有人能够保证你的手机不会损坏或丢失，而一旦手机损坏或丢失，你的文章备份将不复存在，追悔莫及。

纯纯写作尊重并保护用户的隐私，因此服务端不会储存用户的任何隐私信息，用户的文章并不会存储在用户掌控之外的位置。

WebDAV 云备份相当简单，你可以访问[《纯纯写作-自动备份与云备份教程》](https://writer.drakeet.com/backups)来了解纯纯写作的自动备份和云备份功能，并获得注册坚果云的教程。

云备份账号与纯纯写作的账号不是绑定的，纯纯写作的账号仅与激活状态绑定。恢复备份即可恢复纯纯写作的激活状态，但登录纯纯写作账号无法恢复文章备份。

如果用户不设置云备份，则应手动将本地备份保存在可以信任的位置，以便不时之需。

## 为什么坚果云的 WebDAV 显示不能登录？

如果登入坚果云的 WebDAV 时显示【您的 WebDAV 设置不完整或不正确】及【Error Connect】错误提示，这是因为使用了坚果云的密码为 WebDAV 密码，现在坚果云已经不支持直接使用坚果云账号密码作为 WebDAV 密码，所以必须要在坚果云中创建「应用密码」，使用应用密码才能连通 WebDAV。

**注意**：多次重复设定密码为账号密码将可能使坚果云账号被封，请点击坚果云邮件提供的链接解封。

出现此问题的用户请按照云备份教学为纯纯写作配置第三方应用密码：[**《纯纯写作自动备份与云备份教学》**](https://writer.drakeet.com/backups)

## 如何配置云备份？
在纯纯写作的设置页面内打开【备份、云备份、云同步】页面。
想了解更多或了解关于坚果云的备份配置可以访问[云备份与自动备份教程](https://writer.drakeet.com/backups)

## 如何在新设备中恢复旧设备中的文章？

当切换设备后，可以使用两种方式恢复你的备份：通过云备份恢复或通过本地备份恢复。

- 通过云备份恢复
  
  在确保新设备的【备份、云备份、云同步】页面中已配置完成云备份后，点击【恢复备份】（此选项亦可以在应用主页右上角云图标的弹出菜单中找到），在弹出页面中根据书籍、文章数量，备份时间，备份机型来选择想要恢复的备份。一般选择来自旧设备的最新备份并进行覆盖备份恢复即可。

- 通过本地备份恢复
  
  没有进行云备份，并拒绝纯纯写作云备份提醒的用户，请经常手动保存本地备份至可信任的位置。

  若旧设备仍可使用，可以在旧设备的【备份、云备份、云同步】页面点击【立即备份到本机储存空间】以进行一次手动备份，在对应的储存目录中找到生成的 .pwb 档，将其发送到新设备中，并通过纯纯写作打开，即可恢复本地备份。
  
  若旧设备已经无法使用且未使用云备份的用户，在更换设备后，可以将手动保存的最新备份放置于新设备纯纯写作备份文件夹内，然后从纯纯写作中手动恢复备份；也可以将备份包放在手机上后使用纯纯写作直接打开备份包。
  
  如果没有使用云备份，旧设备无法使用，且没有自行保存本地备份，将**无法恢复文章**。

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

该错误可以参考坚果云官方的相关文档 [WebDAV 常见问题答疑](https://content.jianguoyun.com/1112.html)。

> 此种情况是由于短时间内请求了太多次同步导致的，关闭同步后六小时再重新启用同步即可。\
> 访问频率限制：由于 WebDAV 协议比较占用系统资源，免费版用户限制访问频率为每 30 分钟不超过 600 次请求。付费用户限制访问频率为每 30 分钟不超过 1500 次请求。

## 新设备恢复备份后为什么还是初始文章？

请注意选择**来自旧设备的时间和体积正确**的备份，不要选择你当前新安装而触发生成的空备份。

## 纯纯写作支持自动同步吗？

纯纯写作不支持全自动同步，但支持半自动同步与手动同步。

当开启同步功能后，在不同的设备之间同步时会自动合并更新文章内容。关于同步时机、注意事项等内容请在应用内右上角云图标中阅读《关于云同步》。

## 纯纯写作为什么没有全自动同步？

完全自动化的云同步必然要伴随着同步冲突、同步失败、覆盖丢失等问题，这基本上是无解的，特别是要在手机上处理冲突……想想最经得起考验的 git，都需要很多程序员参手和繁琐解决各种冲突，因此完全自动化的云同步可以说几乎不可能，除非各个端能够保持高速实时连接，瞬间同步……

## 多设备使用时备份中的内容会自动合并吗？

纯纯写作支持手动「合并备份」，如果想要纯纯写作自动合并云端的变化，请在【备份、云备份、云同步】页面中开启云同步功能。

**云同步功能请在确认已经详细阅读并同意《关于云同步》之后使用。**

## 在多个设备上使用时，应该如何保证正在编辑的版本为最新？

- 仅使用云备份时

  在每次切换设备时，都进行一次恢复云备份的操作。在点击恢复备份时，比较推荐使用合并备份。
  
  如果您在多个设备上使用纯纯写作，可以通过合并备份来比较方便地相互合并内容，不过建议还是以一个设备为主。
  
  由于云备份的文件在云端文件夹中保留的数量有限，因此当一个设备连续多次进行云备份时（当多应用协同编辑文档时，很容易出现这种情况），另一台设备的云备份有可能会被自动清理掉。

- 使用云同步时
  
  使用云同步前需注意详细阅读并理解《关于云同步》。

  根据手动同步和半自动同步选择的不同，文章将在不同设备间进行云同步。手动同步需要手动点击位于编辑器底部的同步按钮以进行同步；半自动同步则会在文字有变更且收起键盘时自动进行同步，两次同步的间隔至少为 6 秒。

## 备份包很大使坚果云流量迅速用完怎么办？

- 可以进入废纸篓彻底删除之前删除的文章，由于暂时没有全选与清空废纸篓功能，此操作需要手动进行。
  
  **需要注意的是，撤销此操作需要恢复备份。**

- 网络等条件允许的话，也可以尝试使用其他无流量限制的 WebDAV 服务，如 [Teracloud](https://teracloud.jp/)、[Box](https://www.box.com/)、[Yandex disk](https://disk.yandex.com/)、自行搭建的 WebDAV 等。
  
  **其他的 WebDAV 服务经常会受网络限制等情况无法使用或连接，严重时可能造成无法进行云端备份，请仔细考察其限制后慎重选择。**

- 开通坚果云专业版。
  并非打广告，有需求的可以考虑开通坚果云会员。

- 其它方法有待补充。

## 在 Google Drive 找不到备份文件？

Google Drive 不支持用户对应用建立的云备份文件进行修改，因此即使应用内显示备份成功，用户仍无法在 Google Drive 上找到对应的文件夹。

由于上述原因，当用户使用 Google Drive 时，将**无法使用云读写**，请根据自己的情况与需求进行选择。

## 纯纯写作可以使用百度云/阿里云备份吗？

**不可以。**

百度云目前已不再公开提供 API 服务，只对部分厂商特别提供，阿里云目前未提供任何公开的 API 供第三方应用接入，使用非公开的 API 可能构成侵权行为，因此纯纯写作无法提供接入百度与阿里的云服务的功能。

## 关于使用其他云盘备份的统一回复

目前纯纯写作支持使用 WebDAV、Dropbox 和 Google Drive 同步。

目前国内可以稳定公开免费使用的支持 WebDAV 的仅有坚果云一家，国外可以选择的有日本的 TeraCloud、俄罗斯的 Yandex Disk 以及美国的 Box 云盘，由于众所周知的原因，这些国外云盘在国内使用的体验只能说见仁见智。如果是要求每次使用都进行备份的用户、需要完全绝不丢失的用户、不能承担丢失部分文章风险的用户、网络条件会经常变化的用户等，还请**谨慎选择**国外云盘。

由于众所周知的原因，中国大陆部分用户使用 OneDrive 云服务的速度并不理想，因此纯纯写作在无法保证不会因此造成文章丢失的情况下，将不会支持使用 OneDrive 备份。

微云、百度网盘、阿里云盘、微盘等国内网盘通常是不开放的网盘，并不提供（或仅对部分厂商提供）第三方应用可使用的 API 接口，并且可能还存在许多其他影响使用的因素（如限速等），因此纯纯写作暂不会接入国内的其他网盘。

## 为什么不能关闭自动备份？

本地自动备份无法关闭，否则纯纯写作将无法保证您的文本安全。但您可以放心，纯纯写作不会无限地备份导致您的手机剩余存储空间不断缩小，它会帮助您自动维持 25 份最新自动备份文件，过旧的备份版本将被删掉。当然，您手动点击纯纯写作的【立即备份】而产生的备份不会纳入在内，它们会永久存储于你的手机之中，除非你自行去把它们删除。

# 纯纯写作 Markdown 使用指南

## 何谓 Markdown？

Markdown 是一种用纯文本表达富文本内容的标记语言。它简单易学，纯纯写作支持 Markdown(MD)，您可以点击顶栏右侧的`TXT`将其切换为`M↓`以启用 Markdown。

纯纯写作提供了 Markdown 快捷输入面板，你可以点击快捷输入栏左侧的`M↓`图标使用它们。

### 注意事项

1. **空格**在 Markdown 中是重要的组成成分，不可缺失。

2. Markdown 所使用的标记多为**半角**，请勿与全角混淆。

3. Markdown 下默认**无法使用缩进**，有需要缩进的段落请手动插入缩进。

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

表格的基本构成部件是竖形制表符`|`、空格、冒号`:`和短连接线/减号`-`四个部件，制表符分隔表格的每一栏，空格确定表格内的文本内容，冒号确定表格中文本的位置，短连接线则负责标记表头与辅助确定表格中文本的位置。

实例：

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
- 如果有标题中有空格，`#` 中的空格应当删去。（在某些规范中应被替换为 `%20` 或 `-`）
- 目前版本仅能在预览（预览&另存为）页面实现跳转，在即时预览中无法实现。
- 在纯纯写作中可能会出现无法跳转或跳转到浏览器的情况，由于种种原因的限制，目前该问题无法解决。

### 分割线

分割线是由至少三个的短连接线/减号`-`构成的，占单独一行。

需要注意的是，在文本与其下方的分割线之间应该加入一个空行，否则分割线上的文本会被识别为标题。

### 改变字符颜色

纯纯写作可以通过 HTML 的`<font color="|">|</font>`来改变字符的颜色，格式为`<font color="颜色色号或常见颜色的英语单词">需要改变颜色的文本</font>`。

举例：`<font color="black">黑色文字</font>`、`<font color="#000000">黑色文字</font>`

注意：改变字体颜色与字符居中暂时**无法嵌套**；改变字体颜色在许多地方可能造成冲突而**无法显示**（如表格），**请谨慎使用**。

### 输入标记字符

如果你需要输入标记字符的本体，那你就需要看一下这一条了，Markdown 通过反斜线`\`来输入标记字符。

举例说明：`\*斜体\*`在 Markdown 中将会被渲染为`*斜体*`。

### 关于其他 HTML 代码

在 Markdown 中可以使用相当一部分 HTML 代码，而纯纯写作也对其做了一定的支持。如之前介绍的下划线`<u>|</u>`（`<ins>|</ins>`）、上下角标`<sup>|</sup>`、`<sub>|</sub>`等。

需要注意的是，纯纯写作的 Markdown 编辑器并非真正的 HTML 编辑器，因此并非所有 HTML 代码都能在纯纯写作的 Markdown 模式下使用并得到渲染。有相关需求的用户可以自行实验纯纯写作是否对其进行了支持。

### 代码块

Markdown 中可以通过使用` ```|``` `来包含多行代码，使用`` `|` ``来包含行内代码。

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

纯纯写作的 Markdown 遵循 CommonMark 的规范，参考链接：[CommonMark Spec](https://spec.commonmark.org/0.29/)

关于纯纯写作中的 Markdown 可以使用 CommonMark 提供的官方测试器进行测试：[CommonMark 规范测试器](https://spec.commonmark.org/dingus/)

## Markdown 中文本高亮或其他部分代码为何无法使用？

文本高亮的常见代码`==|==`并非 Markdown 原生的代码，而是其他第三方应用加入的代码，纯纯写作不支持这些非原生的代码。如果有需要可以尝试使用行内代码块（其代码为：`` `行内代码块` ``，纯纯写作中提供了快捷输入）代替，需要注意的是，行内代码块里不会渲染加粗、斜体、删除线、下划线等代码。

## Markdown 的居中为何无法使用 center 代码？

纯纯写作的居中与左右对齐只能使用 `<p align="center/left/right">|</p>` 代码来完成。因为 `<center>|</center>` 代码会出现无法正确渲染换行等 bug，所以纯纯写作取消了对此代码的支持。

# Pure Writer Desktop Alpha FAQ

## 关于纯纯写作测试版使用体验的重要说明

**⚠️ 纯纯写作的桌面版仍在测试中，目前的使用体验非常初级，只提供了局域网内双向即时同步编辑当前文章的功能，因此请不要对其抱有太高的期望，以免过度失望。如果您打算*仅仅*因为这个桌面版而付费，我强烈建议您重新考虑这件事情。勿谓言之不预。⚠️**

## 桌面版在哪里下载？

纯纯写作桌面版会在[纯纯写作桌面版下载](http://writer.drakeet.com/desktop) 、Telegram 频道、官方 QQ 群、微信群和公众号中更新，可以通过相关渠道进行下载。

除此之外请不要轻易相信由第三方提供的版本，因使用未知来源的版本造成的档案丢失、内容被泄漏等问题，恕难提供帮助。

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

## 桌面版文字有重影现象如何解决？

可以尝试修改 Nvidia 控制面板的刷新率设置为固定刷新率以解决该问题。

# 纯纯小八卦

## 为什么昵称开发者 Drakeet 为爪爪？

因为 Drakeet 的前三个字母 dra 的读音是爪，取叠音就为爪爪(DraDra)。

## 关于魔法代码

在纯纯写作的时光机中存在一些隐藏的魔法代码，在时光机中输入魔法代码的话，可能会产生一些有趣的效果。

## 纯纯写作的小彩蛋

目前已证实存在的彩蛋有两个。

- 在会员页面进行一定次数的某些重复操作后，可以见到纯纯写作曾经设计过但最终放弃的一个图标和一个弹窗彩蛋。
  
  这个彩蛋的图标如今也被应用于纯纯写作在安卓 12 的启动动画中。
  
- 在纯纯写作中，使用默认的霞鹜文楷字体，复制或输入 （U+E003）即可见到这个彩蛋。
  
  该字符在当前页面中可能无法正常显示，将它复制到纯纯写作中后套用霞鹜文楷即可正常显示。
