# 独立日志记忆

为 Agent 提供 retain、recall、forget；每条记录独立持久化，按 Agent 隔离并分页检索，不限制为固定总条数。

在 Agent 设置中选择日志记忆提供者。当前检索使用关键词匹配，并非向量检索或自动知识图谱。

## 安装与开发

在 Mewu 的插件市场搜索 **独立日志记忆**，核对本项目源码后安装。已有版本的发行资产保留在[社区市场发行页](https://github.com/abnste/mewu-plugins/releases)，不变更用户现有的更新来源。

本仓库根目录的 mewu-plugin.json 与 index.mjs 是可独立打包的完整插件源码，无须修改 Mewu 核心。[SDK](https://github.com/abnste/mewu_ai/tree/next/packages/sdk) · [打包与 GitHub 投稿](https://github.com/abnste/mewu_ai/tree/next/tools/extension-market)

## 许可

MPL-2.0，与 Mewu 一致。
