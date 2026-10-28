# 周计划工作台

用于 Obsidian 的 Markdown-first 周计划工作台插件。

## 仓库说明

这是插件的公开发布仓库，仅用于提供安装文件和版本更新，不包含开发源码。

当前版本：`0.5.23`。

本次更新修复电脑与手机跨端同步时勾选状态不流转、已删步骤复活及落后索引覆盖计划结构的问题；修复共用固定任务显示、编辑卡片步骤配对、任务工作窗成果上传、周结顺延复盘及移动端移栏菜单，并补齐同步冲突保护与非法日期校验。手机和电脑请都更新到 0.5.23，完成后重新打开 Obsidian。

BRAT 更新插件程序，计划数据仍需通过已经配置的仓库同步服务传输。

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
