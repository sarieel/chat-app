# DeepSeek API 聊天应用

这是一个基于 HTML、CSS 和 JavaScript 的聊天应用，使用 DeepSeek 官方 API 提供对话功能。本应用可以部署在 GitHub Pages 上，并在 iOS 端通过 Safari 浏览器访问使用。

## 功能特性

- ✅ 美观的聊天界面
- ✅ 响应式设计，适配 iOS 设备
- ✅ 本地存储 API Key，无需每次输入
- ✅ 实时加载状态显示
- ✅ 错误处理和提示
- ✅ 支持回车键发送消息

## 部署到 GitHub Pages

### 步骤 1：创建 GitHub 仓库

1. 登录 GitHub 账号
2. 点击右上角的 "New" 按钮创建新仓库
3. 输入仓库名称（例如：`deepseek-chat-app`）
4. 选择 "Public" 公开仓库
5. 勾选 "Add a README file"（可选）
6. 点击 "Create repository" 按钮

### 步骤 2：上传文件

1. 克隆仓库到本地：
   ```bash
   git clone https://github.com/你的用户名/deepseek-chat-app.git
   cd deepseek-chat-app
   ```

2. 将 `index.html` 文件复制到仓库目录

3. 提交并推送代码：
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

### 步骤 3：启用 GitHub Pages

1. 进入仓库页面，点击 "Settings" 选项卡
2. 在左侧菜单中点击 "Pages"
3. 在 "Source" 部分，选择 "main" 分支，然后选择 "/ (root)" 目录
4. 点击 "Save" 按钮
5. 等待几分钟，GitHub 会生成部署链接
6. 复制生成的 URL（例如：`https://你的用户名.github.io/deepseek-chat-app/`）

## 在 iOS 端使用

### 方法 1：通过 Safari 浏览器访问

1. 在 iOS 设备上打开 Safari 浏览器
2. 输入 GitHub Pages 生成的 URL
3. 开始使用聊天应用

### 方法 2：添加到主屏幕（推荐）

1. 在 Safari 中打开应用
2. 点击底部的分享按钮（正方形带箭头）
3. 滑动找到并点击 "添加到主屏幕"
4. 输入应用名称（例如："DeepSeek Chat"）
5. 点击 "添加" 按钮
6. 现在应用会出现在主屏幕上，点击即可打开

## 获取 DeepSeek API Key

1. 访问 [DeepSeek 平台](https://platform.deepseek.com/)
2. 注册或登录账号
3. 点击 "API Keys" 选项
4. 点击 "Create new API key"
5. 复制生成的 API Key
6. 在应用中粘贴 API Key 并开始使用

## 技术实现

- **前端**：HTML5, CSS3, JavaScript (ES6+)
- **API**：DeepSeek Chat Completions API
- **存储**：localStorage（本地存储 API Key）
- **部署**：GitHub Pages

## 应用截图

### 桌面端

### iOS 端

## 注意事项

1. **API Key 安全**：API Key 存储在本地浏览器中，不会上传到服务器
2. **API 费用**：使用 DeepSeek API 可能会产生费用，请参考 [DeepSeek  pricing](https://platform.deepseek.com/pricing)
3. **网络要求**：需要网络连接才能使用 API 功能
4. **iOS 兼容性**：支持 iOS 12.0 及以上版本的 Safari 浏览器

## 常见问题

### Q: API 请求失败怎么办？
A: 请检查 API Key 是否正确，网络连接是否正常，以及 DeepSeek 平台的服务状态。

### Q: 在 iOS 上添加到主屏幕后，应用图标不显示怎么办？
A: 尝试重新添加，确保网络连接正常。

### Q: 聊天消息没有显示怎么办？
A: 检查 API Key 是否有效，以及是否有网络连接。

## 许可证

本项目采用 MIT 许可证。
