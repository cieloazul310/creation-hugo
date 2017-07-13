+++
autoThumbnailImage = false
categories = ["hugo","Shortcodes"]
comments = true
#coverCaption = ""
#coverImage = "img/cover.jpg"
#coverMeta = ""
#coverSize = "full"
date = "2017-07-10T16:13:52+09:00"
draft = true
keywords = ["tech"]
metaAlignment = "center"
showDate = true
showPagination = true
showSocial = true
showTags = true
tags = ["hugo","Shortcodes","D3.js"]
#thumbnailImage = "img/cover.jpg"
thumbnailImagePosition = "left"
title = "D3.jsのチャートをiframeで表示するShortcodes"

+++

hugoには[Shortcodes]という簡易なコードで記事内にHTML要素を呼び出す機能があります。
Shortcodesで`<iframe>`を呼び出し、その中でD3.jsを表示するサンプルのコードを作成しました。

<!--more-->

## Shortcodesとは

hugoの記事はMarkdownファイルから生成されます。Markdownに対応していない動画の埋め込みでは、html要素を
Markdownの中に生のhtmlコードを書くことは可能ですが、何度もやるのは面倒です。
[https://www.youtube.com/watch?v=6WgBzTfN-LM](https://www.youtube.com/watch?v=6WgBzTfN-LM) というURLのYouTubeの動画を記事内に埋め込みたいときに、記事を構成するMarkdownファイルの中に、

{{< youtube 6WgBzTfN-LM >}}

と記述すると、以下のように表示されます。

{{< youtube 6WgBzTfN-LM >}}

[Shortcodes]: //gohugo.io/extras/shortcodes/
