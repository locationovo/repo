# 个人越狱源

[English](./README.md)

添加请到：[源主页](https://locationovo.github.io/repo)

## 镜像源声明

本仓库包含以下重建与重写的历史索引镜像：

- **Procursus**：重建了 `1500`、`1600`、`1700` 的 `iphoneos-arm64` 索引。
- **Bingner**：重写了 `550.58`、`800.00`、`1200.00`、`1443.00` 的索引，仅改写了 `Architecture` 与 `Filename` 字段。

**注意事项：**

1. 本仓库**仅镜像索引文件**（`Packages`、`Release` 等），不存储或分发任何原始 `.deb` 包体，客户端下载时直连官方源。
2. 索引中的 `Architecture` 字段已统一重写为 `iphoneos-arm64`，旨在配合现代包管理器进行研究性使用，安装前请自行评估兼容性。

## 版权声明

本仓库收录的第三方插件及工具版权归原始作者所有。完整的许可证说明、免责条款及联系方式，请阅读 **[DISCLAIMER.md](./DISCLAIMER.md)**。