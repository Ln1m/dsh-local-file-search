# dsh-local-file-search

[中文](README.md) · English

![Machine-wide file search in the @ menu](assets/dsh-local-file-search.png)

*Mockup: layout rendered from the official theme tokens, not a screenshot of a running instance.*

Adds a "Search this machine" entry to the `@` list in the composer: one machine-wide search, whose hits go into the current conversation only — never into the file tree or the workspace index.

## Install

```sh
dsh plugin --profile web add file:<this repo>
```

Restart the web instance afterwards.
