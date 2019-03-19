---
layout: post
title: "Vim基础"
data:  2019-03-02
categories: Tips
tags: Vim
---

* content
{:toc}
*本文持续更新*

## 常用基本操作

| 按键    | 操作                      |
| ------- | ------------------------- |
| i/I     | 当前字符前插入/行首插入   |
| a/A     | 当前字符后插入/行末插入   |
| Esc     | 进入命令行操作模式        |
| !       | 强制执行                  |
| :q      | 退出                      |
| :w      | 保存文件                  |
| :wq/:x  | 保存并退出   |
| o/O     | 当前行下/上新增一行并插入 |
| h/j/k/l | 左/下/上/右               |
| x/X | 删除当前光标/之前一个字符 |
| r/R | 单字替换/一直替换 |
| s/S | 删除单字/删除单行并进入编辑模式 |
| $/0 | 进入行末/进入行首 |
| e/b | 移动到下一个词尾/移动到上一个词首 |
| ^ | 移动至行字首 |
| H/M/L | 移至窗口第一行/中间/最后一行 |
| G | 移至文件最后一行 |
| :n | 进入第n行 |
| n+/n- | 进入所在行之后/前n行 |
| d/y/p | 剪切/复制/黏贴 |
| dd/yy | 删除/复制单行 |
| u/U | 撤销之前一次/所有操作 |
| Ctrl+r | 恢复撤销 |
| /字符串 | 向后查找 |
| ?字符串 | 往前查找 |
| n/N | 向下/上查找一个相同的字符串 |
| % | 查找“(”，“)”，“{”，“}”的配对符 |
| :e | 放弃所有修改并重新载入文件 |
| ZZ | 保存并退出 |
|  |  |

