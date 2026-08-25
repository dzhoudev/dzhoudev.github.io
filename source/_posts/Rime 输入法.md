---
title: Rime 输入法
date: 2024-11-07 11:29:53
categories: win
tags:
  - 输入法
abbrlink: 7df1138c
---

[RIME | 中州韻輸入法引擎](https://rime.im/)

## [白霜词库](https://github.com/zjralhf/rime--)

```shell
# rime 用户文件夹
git clone --depth 1 https://github.com/gaboolic/rime-frost
# 更新
git pull
```
## 不同软件默认中英文

```yaml
patch:
  # 针对特定应用程序单独定制输入状态
  app_options:
    # 终端 / 编辑器：切换进入时默认进入英文（ascii_mode）
    Code.exe:
      ascii_mode: true
    WindowsTerminal.exe:
      ascii_mode: true
    cmd.exe:
      ascii_mode: true
    powershell.exe:
      ascii_mode: true
    idea64.exe:
      ascii_mode: true

    # 办公 / 聊天软件：切换进入时保持默认中文
    WINWORD.EXE:
      ascii_mode: false
    WeChat.exe:
      ascii_mode: false
```

## 主题配色

```yaml
mac:
    author: 'lamb'
    name: 'lamb'
    back_color: 0xffffff
    corner_radius: 5
    border_height: 4
    dborder_width: 4
    border_color: 0xe0e0e0
    border_color_width: 0
    candidate_format: '%c %@  '
    candidate_text_color: 0x333333
    font_face: PingFangSC
    font_point: 16
    text_color: 0x333333
    hilited_candidate_label_color: 0xffffff
    hilited_text_color: 0xffffff
    hilited_candidate_back_color: 0xD05B21
    hilited_corner_radius: 5
    horizontal: true
    inline_preedit: true
    label_color: 0x888888
    label_font_point: 12
```
