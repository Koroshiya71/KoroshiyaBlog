---
layout: friends # 必须
title: 我的朋友们 # 可选，这是友链页的标题
---

{% issues sites | api=https://gitee.com/api/v5/repos/koroshiya/Blog-Friends/issues?access_token=15f2e7d0bbd428e4b92e437cd769911d&state=open&labels=active&sort=created&direction=desc&page=1&per_page=100 | group=group:计辩荣光,老友记 %}
