---
title: "逐音节歌词的使用与转换"
slug: how-to-use-syllable-lyrics
date: 2024-10-21 16:01
categories:
    - "教程"
tags:
    - "音乐"
    - "歌词"
    - "教程"
---

逐音节歌词的介绍，以及歌词使用、格式转换教程。

<!-- more -->

# 常见格式

## Apple 歌词文件

歌词文件使用 TTML 格式，并包含 Apple 特有做法的扩展。每份歌词文件包含一首歌曲的歌词。

了解详细，请参考由 Apple 提供的相关指南：

1. [Apple Music 风格指南 - 歌词准则](https://help.apple.com/itc/musicstyleguide/#/itc3ae5d4dea)

2. [Apple 视频和音频素材指南 - 歌词的 TTML 概述](https://help.apple.com/itc/videoaudioassetguide/#/itcd7579a252)

在 [逐音节歌词列表](/2024/05/01/lyrics-list) 提供的歌词文件大多提供此格式，并参照 Apple Music 风格指南的歌词准则调整。

## Lyricify Syllable

Lyricify Syllable 是 Lyricify 的逐音节歌词格式。

了解详细，请参考 [Lyricify Syllable 格式规范](https://github.com/WXRIW/Lyricify-App/blob/main/docs/Lyricify%204/Lyrics.md#lyricify-syllable-%E6%A0%BC%E5%BC%8F%E8%A7%84%E8%8C%83)。

在 [逐音节歌词列表](/2024/05/01/lyrics-list) 提供的歌词文件部分提供此格式，并参照 Apple Music 风格指南的歌词准则调整。

# 逐音节歌词的转换

推荐使用 [AMLL TTML Tool](https://steve-xmh.github.io/amll-ttml-tool/) 进行转换，本文将基于此工具介绍逐音节歌词的转换方法。

## 第一步：导入歌词

### 导入 Apple 歌词文件

在左上角的 `文件` 菜单，点击 `打开歌词` 或 `从剪切板打开歌词`。

### 导入其他格式

如 Lyricify Syllable、QRC、ESLyric，在左上角的 `文件` 菜单中的 `导入歌词…` 子菜单，选择对应的歌词格式导入。

## 第二步：导出歌词

### 导出 Apple 歌词文件

在左上角的 `文件` 菜单，点击 `保存歌词` 或 `保存歌词到剪切板`。

### 导出其他格式

如 Lyricify Syllable、QRC、ESLyric，在左上角的 `文件` 菜单中的 `导出歌词…` 子菜单，选择对应的歌词格式导出。

> 备注：LRC 不支持逐音节，只支持逐行。

# 逐音节歌词的使用

本文介绍通过以下两种应用使用逐音节歌词的方法。

## AMLL Player

1. 播放音乐。

2. 打开歌词界面。

3. 在歌词界面任意位置右键打开菜单。

4. 在弹出的菜单中点击 `编辑歌曲覆盖信息`。

5. 点击 `歌词`。

### 导入本地歌词

1. 在 `歌词格式` 中选择对应的格式。

2. 将对应的歌词数据复制进 `歌词数据` 一栏。

3. 点击 `保存`。

### 从数据库搜索导入

1. 点击 `从 AMLL TTML DB 搜索 / 导入歌词`。

2. 输入搜索关键词并导入。

3. 点击 `保存`。

## Lyricify for Spotify

### 使用本地歌词

> 需要先在 Spotify 的 `偏好设置` 中打开 `显示本地文件`！

1. 选择 `本地文件`。

2. 播放本地音乐。

3. 打开曲目管理。

4. 滑动到底部，在 `Lyricify 歌词库` 一栏点击 `导入 & 编辑`。

5. 在新弹出的窗口中填入 Lyricify Syllable。

6. 点击 `保存 (上传)`(永久) 或 `在主窗口中应用`(一次性)。

> 注意：你**不应该**`保存 (上传)`**错误的**歌词，或在非本地音乐**随意**`保存 (上传)`**歌词**，这可能导致你的 Lyricify 账号被封禁！

### 使用歌词库歌词

1. 播放音乐，Lyricify for Spotify 将会自动搜索歌词。