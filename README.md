# Super Donuts 网站项目

## 项目概述
Super Donuts是一个在线游戏网站，提供免费的甜甜圈冒险游戏体验。网站采用赛博朋克风格设计，支持PC和移动端访问。

## 功能特点
- 响应式设计，适配PC和移动端
- 内嵌游戏iframe，无需下载即可游玩
- 赛博朋克风格UI设计
- SEO优化，包含适当的标题、描述和标签结构
- 游戏介绍和操作指南

## 技术栈
- HTML5
- Tailwind CSS
- 响应式设计

## 页面结构
- 游戏标题和简介
- 游戏iframe嵌入区域
- 游戏介绍部分
- 游戏控制说明
- 游戏技巧指南
- 页脚信息

## 使用说明
1. 打开index.html文件即可访问网站
2. 点击"Play Now"可直接开始游戏
3. 查看"Controls"部分了解游戏操作方式
4. 阅读"Gameplay Tips"获取游戏技巧

## SEO优化
网站已针对"Super Donuts"关键词进行优化，包含:
- 优化的页面标题和描述
- 合理的H1、H2标签结构
- canonical标签
- 语义化HTML结构 

## 部署说明

### Cloudflare Pages 部署步骤：
1. 将项目推送到GitHub仓库
2. 登录Cloudflare控制台，进入Pages面板
3. 选择GitHub仓库并连接
4. 配置构建设置：
   - 构建命令：`npm run build`
   - 构建输出目录：`./`
5. 点击部署，完成后会自动分配*.pages.dev域名 