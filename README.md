# 名人打卡地图 AI 项目

## 简介
本项目通过 Trae（AI）自动生成，以“名人打卡点地图”为主题，采用 Vue3+Vite+Tailwind 构建，自动集成高德地图。

## 主要功能
- 城市选择与名人列表
- 名��详情页（“古人朋友圈”对话展示）
- 打卡存档与分享功能
- 点位地图总览

## 技术选型
- Vue 3 + Vite
- Tailwind CSS
- AMap JS API（高德）

## 目录结构建议

```
├── src/
│   ├── assets/               # 静态素材、LOGO
│   ├── components/           # 页面组件
│   ├── data/celebrities.js   # 名人打卡点数据
│   ├── views/                # 页面/路由视图
├── .agents/skills/           # AI 代理技能目录
├── memory/                   # 进度/临时记录
```

## 本地开发
1. 安装 Node.js (推荐 v18+)
2. 安装依赖：`npm install`
3. 启动开发：`npm run dev`

## 部署上线（GitHub Pages 推荐）
- 构建：`npm run build`
- 静态资源上传到 GitHub Pages/Vercel/阿里云 OSS

## 参与与技能积累
所有定制功能、AI 任务与技能沉淀于 .agents/skills/，支持长期演进
