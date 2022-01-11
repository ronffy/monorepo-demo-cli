# 基于 Lerna 管理 packages 的 monorepo 项目最佳实践

## 介绍

- monorepo: 单体式仓库，把所有相关 package 都放在一个仓库里管理，每个 package 独立发布。

- lerna: 管理 monorepo 项目的工具。

- yarn workspace: 管理多 package.json 的依赖安装，在工作区之间创建软连接依赖。

- commitizen、cz-lerna-changelog: 在 git commit message 中加下 package 选项。


## 参考文章

- https://juejin.cn/post/6844903911095025678
- https://zhuanlan.zhihu.com/p/71385053
- https://classic.yarnpkg.com/blog/2017/08/02/introducing-workspaces/
