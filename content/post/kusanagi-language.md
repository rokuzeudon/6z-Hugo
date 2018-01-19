+++
title = "KUSANAGIで構築したサイトが日本語訳されていない時にやること"
description = "管理画面はちゃんと日本語になっているのに、実際のサイトでは Recent Posts やら Leave a comment やらのままになっていた"
date = "2018-01-19T01:00:19+09:00"
categories = [ "memo" ]
tags = [ "KUSANAGI", "WordPress" ]
draft = false
+++

管理画面はちゃんと日本語になっているのに、実際のサイトでは Recent Posts やら Leave a comment やらのままになっていた。

理由探すのにかなり時間をかけてしまったが、単純だった。

管理画面 > KUSANAGI > **翻訳アクセラレーター** > **サイトに表示される翻訳された文章** の箇所が、初期で「**翻訳を停止**」になっている。これを「キャッシュを使用」に変更すると日本語訳されて、「最近の投稿」とか「コメントを残す」とか表示されるようになる。

そう初期設定しておいてほしい気がするが………？