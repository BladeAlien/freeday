# 开发规范

## 文档

文档采用 [markdown](https://github.github.com/gfm/) 编写

## 分支

采用 [pull requests](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) 开发方式，默认分支为 `master`，开发时建立新分支，`pr merge` 后删除

一次 `pr` 一般情况应当只有一次 `commit`，合入前需先 `rebase master`

## 目录规范

```
freeday
|-- front       前端代码
|-- back        后端代码
|-- api         接口
|-- docs        文档
`-- reference   参考
```
