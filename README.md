# MEM Talk｜与时代同行

> 与时代对话，与未来同行。
> Listen. Learn. Connect. Transform.

## 关于 MEM Talk

MEM Talk 是一个深度访谈项目，走近正在推动变化的人——企业管理者、技术专家、创业者、学者，以及每一个在时代浪潮中探索成长的实践者。

我们聊技术，也聊选择；聊产业，也聊人生；聊未来，也聊当下。

## 项目结构

```
mem-talk/
── index.html    # 单页站点（HTML + CSS + JS 一体化）
└── README.md     # 本说明文件
```

## 本地预览

直接双击 `index.html` 用浏览器打开，或使用任意静态服务器：

```bash
# 使用 Python 内置服务器
python3 -m http.server 8000

# 使用 Node.js
npx serve .
```

然后在浏览器访问 `http://localhost:8000`。

## 设计说明

- **配色**：清华紫色（#660874）为主色，金色（#C8A951）为点缀
- **字体**：Space Grotesk（英文标题）+ Noto Sans SC（中文）+ Playfair Display（装饰性英文）
- **动画**：Hero 区域金色粒子网络 + 滚动渐显效果
- **响应式**：适配桌面端和移动端

## 页面板块

| 板块 | 说明 |
|------|------|
| Hero | 品牌展示 + 粒子动画背景 |
| Manifesto | 项目初衷 + 三大关键词 |
| Topics | 六大话题卡片 |
| Voices | 嘉宾引言展示 |
| Tagline Banner | 品牌标语横幅 |
| Join | 联系方式 + 加入入口 |

## 部署

本项目为纯静态站点，可部署到任意静态托管服务：

- **GitHub Pages**：Settings → Pages → 选择 main 分支
- **Vercel / Netlify**：直接连接仓库即可自动部署
- **阿里云 OSS**：上传 index.html 并开启静态网站托管

## 联系方式

- 微信：yangxin_ryan
- 邮箱：yangxin812716131@163.com
- 小红书：沉迷AI的RyanYang

## License

© 2026 MEM Talk. All rights reserved.
