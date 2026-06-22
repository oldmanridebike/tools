# ToolForge - 在线开发者工具箱

一个精心设计的在线开发者工具集合，提供 24 个实用工具，其中 12 个完全可交互。

## 功能特色

- **编码/解码**：Base64、URL 编解码、Unicode 转换
- **文本处理**：字数统计、大小写转换、文本对比、Markdown 预览
- **开发工具**：JSON 格式化、正则测试、JWT 解析、CSS/JS 压缩、Cron 表达式
- **时间转换**：Unix 时间戳与日期互转
- **安全/加密**：SHA 哈希生成器、MD5 计算、密码生成器
- **格式转换**：颜色转换（HEX/RGB/HSL）、二维码生成、YAML/JSON 互转
- **图片/媒体**：图片压缩
- **其他**：IP 查询、Whois 查询、DNS 查询

## 技术栈

- 纯 HTML / CSS / JavaScript，无框架依赖
- 深色主题 + 绿色强调色的现代工业风格
- 响应式设计，适配桌面和移动端
- Web Crypto API 实现哈希和密码生成
- Google Fonts（Outfit + IBM Plex Mono + Noto Sans SC）

## 使用方式

直接用浏览器打开 `index.html` 即可使用。

> 注意：哈希生成功能依赖 Web Crypto API，需通过本地服务器（如 `npx serve`）或 HTTPS 访问。

## 部署

项目已部署至 Vercel：https://toolweb-sigma.vercel.app

## License

MIT
