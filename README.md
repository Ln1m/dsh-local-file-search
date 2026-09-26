# dsh-local-file-search

![@ 菜单里的本机文件搜索界面示意](assets/dsh-local-file-search.png)

*界面示意：按官方主题变量渲染的版式，非实机截图。*

在对话框的 @ 列表里加一条「搜索本机文件」：全机一次性搜索。结果只进当前对话，不写进文件栏，也不进工作区索引。

## 装

```sh
dsh plugin --profile web add file:<本仓库>
```

装完重启 web 实例。
