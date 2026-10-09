# 考研英语阅读真题打卡网站

包含 2007—2023 年 68 篇阅读的打卡主页，支持进度统计、浏览器本地保存、JSON 备份导入/导出。

## 发布到 GitHub Pages（免费）

1. 登录 GitHub，创建一个 **Public** 仓库，建议命名为 `kaoyan-reading-tracker`。
2. 将本文件夹中的所有内容上传到仓库根目录（确保 `index.html` 位于根目录，`.github/workflows/deploy.yml` 也一并上传）。
3. 打开仓库 **Settings → Pages**，将 Build and deployment 的 Source 设为 **GitHub Actions**。
4. 打开 **Actions** 标签，等待 `Deploy reading tracker to GitHub Pages` 工作流成功。
5. 页面会显示站点网址，通常格式为 `https://<你的GitHub用户名>.github.io/kaoyan-reading-tracker/`。

## 重要说明

- 这是纯静态网站，不需要服务器或 API 密钥。
- 打卡数据保存在当前浏览器的 `localStorage` 中；清除浏览器数据或更换设备不会自动同步。请定期使用“导出进度备份”。
- 仓库公开意味着网站源码公开；不要把私人信息放进仓库。
