# SkillHub CLI Guide

`@astron-team/skillhub` 命令行工具的完整使用手册，Anthropic 风格的单文件静态页面。

**在线访问**：https://intelligent-guoxin.github.io/skillhub-cli-guide/

## 内容结构

| 章节 | 内容 |
|------|------|
| 01 环境准备与配置 | npm 全局安装、`SKILLHUB_REGISTRY` 环境变量（Linux/macOS · PowerShell · CMD） |
| 02 身份认证 | Token 登录、登录时指定 Registry、查看身份、登出 |
| 03 技能检索 | 关键字搜索、分页、JSON 输出 |
| 04 安装技能 | 自动探测、多 Agent、指定版本、命名空间、自定义目录、强制覆盖 |
| 05 查看与更新 | 已安装列表、更新、覆盖更新的两种等效方式 |
| 06 发布与移除 | 发布到命名空间、本地移除、远程删除 |
| 07 参数速查 | 全部 Flag 及其适用范围 |

## 本地预览

直接双击 `index.html` 即可，无需构建、无需安装依赖。

页面唯一的外部资源是 Google Fonts（Fraunces / Noto Serif SC / Inter Tight / JetBrains Mono）；
离线环境下字体会回退到系统字体，布局与功能不受影响。

## 特性

- 单文件、零依赖、零构建
- 每条命令支持一键复制（`file://` 协议下自动走 `execCommand` 兜底）
- 侧边目录随滚动高亮，顶部导航锚点跳转
- 响应式：<960px 自动隐藏侧栏

## 部署

GitHub Pages，从 `main` 分支根目录发布。更新内容后直接 push，约 1 分钟生效。
