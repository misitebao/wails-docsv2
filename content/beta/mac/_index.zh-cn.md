+++
title = "Mac"
date = 2020-12-29T19:33:11+10:00
weight = 1
+++

## 测试版状态

Mac 版本的 v2 是最完整的版本，现在可以使用它来构建应用程序。缺少一些非关键功能。

### 命令行

| 命令     | 状态 | 笔记                                  |
| :------- | :--: | ------------------------------------- |
| init     |  ✓   |                                       |
| build    |  ✓   |                                       |
| doctor   |  ✓   |                                       |
| generate |  ✗   | Typescript generation is kinda broken |
| dev      |  ✓   |                                       |
| issue    |  ✗   | TBD                                   |
| update   |  ✗   | TBD                                   |

### 运行时

| 特征    | Go  | Javascript | 笔记        |
| :------ | :-: | :--------: | ----------- |
| Menu    |  ✓  |     ✗      | JS TBD      |
| Window  |  ✓  |     ✓      |             |
| Logging |  ✓  |     ✓      |             |
| Browser |  ✓  |     ✓      |             |
| Events  |  ✓  |     ✓      |             |
| Tray    |  ✓  |     ✗      | JS Menu TBD |
| System  |  ✓  |     ✓      |             |
| Dialog  |  ✓  |     ✓      |             |

## MacOS 版本支持

测试平台支持的最好方法之一是尝试运行位于`v2/test`中的 Kitchen Sink 应用程序。这是一个全面的测试应用程序，涵盖了 Wails 运行时的所有部分（Go 和 Javascript）。

| MacOS 版本 | 命令行 | 运行时 | 笔记                     |
| :--------- | :----: | :----: | ------------------------ |
| v11.1 beta |   ✓    |   ✗    | 在 JS 中没有实现右键菜单 |
|            |        |        |                          |
|            |        |        |                          |
