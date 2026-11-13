# Twinkle Stars · 打卡挑战

可爱的亲子连续打卡小工具：点亮金星、攒进度、兑奖励。  
纯前端单页（`index.html`），数据保存在浏览器 `localStorage`，无后端。

## 功能

- **宝宝页 / 家长页**（家长页带 PIN 童锁）
- **连续打卡**：点亮金星＝完成，再点＝取消当格；支持一键打满 / 一键清除
- **任务可配置**：任务名、奖励、开始日期、连续天数
- **宝宝资料**：昵称、性别、年龄（沟通文案与奖状按昵称动态生成）
- **皮肤**：蓝色 / 粉色 / 绿色 / 黄色 / 紫色
- **奖状**：完成后可预览并保存为图片

## 本地打开

用浏览器直接打开 `index.html`，或：

```bash
cd twinkle-stars
python3 -m http.server 8080
```

访问 `http://127.0.0.1:8080/`。

## GitHub Pages（推荐公开发布）

1. 在 GitHub 新建公开仓库：`twinkle-stars`
2. 推送本仓库 `main` 分支
3. Settings → Pages → Deploy from branch → `main` / root
4. 访问：`https://<你的用户名>.github.io/twinkle-stars/`

```bash
git remote add origin https://github.com/<你的用户名>/twinkle-stars.git
git branch -M main
git push -u origin main
```

## 说明

- 打卡数据仅存在各自设备的浏览器本地，不会上传到 GitHub
- 换浏览器 / 清站点数据会导致进度丢失
- 仓库为前端源码公开可见；页面本身也无涉密信息
