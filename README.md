# OnePic - 网页截图浏览器扩展

一键将任意网页保存为高质量图片的浏览器扩展工具，支持全页面截图和自定义区域选择。

## ✨ 功能特性
- **快速截图** 点击图标即刻生成网页图片
- **多种模式** 
  - 可视区域截图
  - 完整网页长截图
  - 自定义选区截图
- **格式支持** PNG/JPEG 格式输出
- **智能处理** 自动处理浮动元素和懒加载内容
- **快捷操作** 支持快捷键触发截图（默认 Ctrl+Shift+S）

## 📦 安装方式

### 浏览器商店安装（推荐）
暂无

### 手动安装（开发模式）
1. 克隆仓库
```bash
git clone https://github.com/SoneyChan7/one_pic.git
```
2. 打开浏览器扩展管理页面
   - Chrome: 访问 `chrome://extensions/`
   - Firefox: 访问 `about:debugging#/runtime/this-firefox`
3. 启用"开发者模式"
4. 点击"加载已解压的扩展程序"，选择项目目录

## 🖥️ 使用说明
1. 点击浏览器工具栏中的相机图标
2. 选择截图模式：
   - 📷 当前视图
   - 🌐 完整页面
   - ✂️ 自定义选区
3. 调整截图参数（可选）：
   - 图片质量（60%-100%）
   - 是否包含滚动条
   - 延时截图（等待元素加载）
4. 点击保存按钮下载图片

## 🛠️ 开发指南
```bash
# 安装依赖
npm install

# 开发模式（实时编译）
npm run dev

# 构建生产版本
npm run build
```
项目使用以下技术栈：
- Vue.js 3 组件开发
- Browser Extension API
- html2canvas 网页渲染
- Webpack 打包工具

## 🤝 参与贡献
欢迎通过 Issue 提交建议或 PR 参与开发：
1. Fork 项目仓库
2. 创建特性分支（`git checkout -b feature/awesome`）
3. 提交修改（`git commit -m 'Add awesome feature'`）
4. 推送分支（`git push origin feature/awesome`）
5. 发起 Pull Request

## 📄 许可证
本项目采用 [MIT 许可证](LICENSE)

---

> 注意：首次使用时会请求网页访问权限，截图包含敏感信息时请谨慎分享。本插件不会收集任何用户数据。

*由 [你的名字/团队名] 使用 ❤️ 构建 - 让网页保存更简单* 

（建议在README中添加实际截图示例和配置说明，可根据项目进展补充更多技术细节）
