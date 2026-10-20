# 儿童身高记录 PWA

功能：按日期记录身高和备注；孩子昵称、出生日期和目标身高；成长概览与趋势图；编辑/删除历史；cm/in 单位切换；JSON 导入导出；本地保存与离线缓存。

## 发布到 GitHub Pages
1. 解压 ZIP。
2. 将 `index.html`、`manifest.webmanifest`、`sw.js`、`icon-192.png`、`icon-512.png`、`README.md` 上传到公开仓库根目录。
3. Settings → Pages → Deploy from a branch → `main` → `/(root)` → Save。
4. 等待 Your site is live，然后在 iPhone Safari 打开网址，分享 → 添加到主屏幕。

数据仅保存在当前设备浏览器本地，不会自动上传。请定期导出 JSON 备份。清除网站数据可能导致记录丢失。本工具仅用于记录，不提供医学诊断或生长百分位评估。
