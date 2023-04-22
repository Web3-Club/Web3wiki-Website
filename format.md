# wiki格式手册

在您提交贡献之前，Web3Club-Wiki编辑部 全体成员 感谢您为本Wiki做出自己的贡献！

在参与贡献之前，您需要阅读以下内容，保证自己的贡献内容符合以下规定：

## 文档引用与存储的格式

-   **文件名请务必都小写，以 `-` 分割。** 例如：`file-name.md`。

-   请务必确保文档中引用的 **外链** 图片已经全部转存到了 **本库内** 对应的 `images` 文件夹中（防止触发某些网站的防盗链），建议处理成 `MD 文档名称 + 编号` 的形式（可参考已有文档中图片的处理方式）。例如：本篇文档的文件名称为 format，则文档中引用的第一张图片的名字为 `format1.png`。

-   推荐使用 SVG 格式的图片，以获取较好的清晰度和缩放效果。

-   动图如果无法或者不会制作 SVG 格式的，则推荐使用 APNG 格式[^apng]的文件。Windows 用户可使用 [ScreenToGif](https://www.screentogif.com) 录制，Linux 用户可使用 [Peek](https://github.com/phw/peek) 录制，注意需要在设置里调整为录制 APNG。其他情况则推荐先制作为 MP4 等视频文件再转换为 APNG，如果使用 ffmpeg 则可以使用 `ffmpeg -i filename.mp4 -f apng filename.apng -plays 0` 转换。

-   同时具有源文件和导出图像的图片（例如 JPG 文件与 PSD 文件或者 SVG 图像与 TikZ TeX 源代码），建议将源文件以与图片相同的文件名保存于同一目录下。

-   请确保您的文档中的引用链接的稳定性。**不推荐** 引用 **自建** 服务中的资源。建议在添加时同时将该外链存于互联网档案馆，以防无法替代的链接失效。

-   站内链接请去掉网站域名，并且使用相对路径链接对应 `.md` 文件。例如，在本页面（`intro/format`）中链接杂项简介（`misc`），应使用 `[杂项简介](../misc/index.md)`。可以在链接中添加 hash 来链接到某一节，例如 [`[Pull Request 信息格式规范](./htc.md#pull-request-信息格式规范)`](./htc.md#pull-request-信息格式规范)，hash 的值可以通过位于每个标题右侧的按钮或者位于网页右侧的目录中的链接得到。

-   根据 2023年4月22日的公告 [《关于 “相关网页中文翻译” 界面的处理办法》](https://www.mubucm.com/doc/Il3SiRnCmC) 相关wiki知识点下的文章 原文（或经翻译完后） 需要嵌入到语雀平台的

## 标点符号的使用

-   请在每句话的末尾添加 **句号**。
-   请正确使用 **全角** 标点符号与 **半角** 标点符号。汉语请使用全角符号，英语请使用半角符号。中文中夹用英文时，请参考 [中文出版物夹用英文的编辑规范](https://www.nppa.gov.cn/nppa/contents/805/102791.shtml)。
-   由于 `“……”` 未区分全半角，请使用 `「……」` 作为全角引号，`"..."` 作为半角引号。
-   注意区分 **顿号** 与 **逗号** 的使用。
-   注意 **括号** 的位置。句内括号与句外括号的位置不同。
-   通常使用 **分号** 来表示列表环境中各复句之间的关系。
-   对于有序列表，推荐在每一项的后面添加 **分号**，在列表最后一项的后面添加 **句号**；对于无序列表，推荐在每一项的后面添加 **句号**。
-   注意区分各种不同的连接号，如 hyphen（一般使用 U+002D hyphen-minus（-），即键盘上的「减号」代替），U+2013 en dash（–）和 U+2014 em dash（—）。（英文中连接多个人名时，须用 en dash，但是极常误用为 hyphen。其他误用较为罕见，基本上只需记住这一点即可。）详见 [连接号 - 维基百科](https://zh.wikipedia.org/wiki/%E8%BF%9E%E6%8E%A5%E5%8F%B7)。

## 外部链接

-   [标点符号用法（GB/T 15834—2011）](http://www.moe.gov.cn/jyb_sjzl/ziliao/A19/201001/W020190128580990138234.pdf)
-   [维基百科：格式手册/标点符号](https://zh.wikipedia.org/wiki/Wikipedia:%E6%A0%BC%E5%BC%8F%E6%89%8B%E5%86%8C/%E6%A0%87%E7%82%B9%E7%AC%A6%E5%8F%B7)
-   [中文文案排版指北（简体中文版）](https://mazhuang.org/wiki/chinese-copywriting-guidelines/)
-   [中文文案风格指南 - PDFE GUIDELINE](https://pdfe.github.io/GUIDELINE/#/others/copywriter)
-   [中文出版物夹用英文的编辑规范](https://www.nppa.gov.cn/nppa/contents/805/102791.shtml)
