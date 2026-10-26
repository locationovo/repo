# 个人越狱源

[English](./README.md)

添加请到：[源主页](https://locationovo.github.io/repo)

## 概述

本仓库是一个托管于 GitHub Pages 的自动化越狱软件源。它通过 GitHub API 聚合来自各个子仓库 GitHub Releases 中分发的软件包。

### 架构说明

- **主仓库（当前仓库）**：托管索引和签名文件。从 Releases 拉取元数据。
- **Recipes**：从源码编译自定义插件，并上传 `.deb` 到 Releases。
- **Patched Legacy**：将旧版 rootful 插件修补以适配现代环境，并上传到 Releases。

**注意事项：**

1. **本 Git 仓库不直接存储任何 `.deb` 文件。** 软件包作为 GitHub Release 资产托管，并通过其 CDN 下载。
2. 历史包使用 `rootless-patcher` 进行修补。若修补失败或崩溃，将分发原始包。不保证兼容性，安装前请自行评估。

## 版权声明

本仓库收录的第三方插件及工具版权归原始作者所有。完整的许可证说明、免责条款及联系方式，请阅读 **[DISCLAIMER.md](./DISCLAIMER.md)**。