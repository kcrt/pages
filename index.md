---
title: "Nanoseconds Hunter"
permalink: /
---

## このサイトは何？

- [TAKAHASHI, Kyohei (kcrt)](https://profile.kcrt.net/) の個人サイトです。

## Programmer's Pocket Reference

- 初出：技術書典 7
- プログラマ向けの情報を集めたA5サイズのマニュアル本です。
- 何回やっても毎回ググってしまう内容や、ググってもなかなか正しい情報が出ないものを中心に、約200ページ書き下しています。
- [サポートページ](/ppr)

## 最近の記事

{% for post in site.posts limit:5 %}

- [{{post.title}}]({{post.url}}) - {{post.date}}

{% endfor %}

- [すべての記事を表示...](/allposts)
