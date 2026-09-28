# dsh-local-file-search

[English](README.en.md) · 中文

![@ 菜单里的本机文件搜索界面实拍](assets/dsh-local-file-search.png)

*界面实拍：截自本机运行中的 DSH 实例，示例内容已脱敏。*

在对话框的 @ 列表里加一条「搜索本机文件」：全机一次性搜索。结果只进当前对话，不写进文件栏，也不进工作区索引。

## 装

```sh
dsh plugin --profile web add file:<本仓库>
```

装完重启 web 实例。
