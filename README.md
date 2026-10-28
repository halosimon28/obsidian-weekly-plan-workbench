# 周计划工作台

用于 Obsidian 的 Markdown-first 周计划工作台插件。

## 仓库说明

这是插件的公开发布仓库，仅用于提供安装文件和版本更新，不包含开发源码。

当前版本：`0.5.22`。

本次更新包含 0.5.21 和 0.5.22 的累计修复：修复整周复制的进度、同名文件和附件链接问题；保护保存期间收到的新配置；避免旧文件回退周状态；修复删除整周后的归档识别，并在返回插件时重新读取同步内容。手机和电脑请都更新到 0.5.22，完成后重新打开 Obsidian。

BRAT 更新插件程序，计划数据仍需通过已经配置的仓库同步服务传输。本版本已验证双电脑窗口与手机样式模拟，尚未验证手机真机或用户实际同步网络。

每个版本的运行文件位于 GitHub Releases：

- `main.js`
- `manifest.json`
- `styles.css`
- `versions.json`

## 推荐安装：BRAT

1. 在 Obsidian 社区插件中安装并启用 BRAT。
2. 打开“设置 → BRAT”。
3. 选择添加 Beta 插件。
4. 输入仓库：`halosimon28/obsidian-weekly-plan-workbench`。
5. 安装完成后，在 Obsidian 社区插件页面启用“周计划工作台”。

后续发布新版本后，在 BRAT 中检查更新即可，不需要重新复制插件文件。

## 手动安装

1. 从 Releases 下载当前版本的四个运行文件。
2. 放入 Obsidian 库目录：`.obsidian/plugins/weekly-plan-workbench/`。
3. 重启 Obsidian。
4. 在“设置 → 社区插件”中启用“周计划工作台”。

插件生成的计划、任务状态和成果附件均保存在用户自己的 Obsidian 库中，不会上传到此仓库。
