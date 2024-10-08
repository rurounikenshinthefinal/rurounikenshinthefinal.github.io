---
title: "찾아오시는 길"
description: "서울 중구 무교로 16 대한체육회관"
# linkTitle:
date: 2023-12-01T11:47:31+08:00
draft: false
noindex: false
featured: true
pinned: false
nav_weight: 2
nav_icon:
  vendor: fas
  name: location-arrow
  # className: text-primary
series:
  - About
categories:
tags:
  - 위치
  - 진료시간
images:
  - https://example-images.razonyang.com/speed.webp?width=1920&height=1280
  # - https://simg.pstatic.net/static.map/v2/map/staticmap.bin?crs=EPSG:4326&amp;baselayer=bl_vc_bg&amp;overlayers=ol_vc_an&amp;scale=2&amp;caller=mw_smart_booking&amp;overlayers=ol_vc_an&amp;center=126.9794111,37.567342&amp;markers=type:c|size:mid|label:hospital|pos:126.9794111 37.567342&amp;level=16&amp;w=335&amp;h=170&amp;lang=ko
# menu:
#   main:
#     weight: 100
#     params:
#       icon:
#         vendor: bs
#         name: book
#         color: '#e24d0e'
authors:
  - HB
  - HugoMods
---

你可以毫不费力地从[新手主题](https://github.com/hbstack/theme)迁移至卡片主题。

## 导入卡片主题模块

{{< bs/alert danger >}}
{{< markdownify >}}
你需要将 `github.com/hbstack/theme-cards` 模块置于顶部，以确保卡片主题获得更高的优先权。
{{< /markdownify >}}
{{< /bs/alert >}}

{{< bs/config-toggle "hugo" >}}
module:
  imports:
    - path: github.com/hbstack/theme-cards
{{< /bs/config-toggle >}}

## 调整参数

若要使首页幻灯片占据整行，可以通过调整置顶文章的位置为 `list`。

{{< bs/config-toggle "params" >}}
hb:
  blog:
    home:
      pinned_posts_position: list
{{< /bs/config-toggle >}}
