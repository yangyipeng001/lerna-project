# lerna demo

# 命令
## yarn workspace
单个package工作区
```bash
# packageA 安装 axios
yarn workspace packageA add axios

# packageA 移除 axios
yarn workspace packageA remove axios
```

root package
```bash
# root package 安装 commitizen
yarn add -W -D commitizen

# root package 移除 commitizen
yarn remove -W commitizen
```


# 资料
[基于 Lerna 实现 Monorepo 项目管理](https://juejin.cn/post/7030207667457130527)