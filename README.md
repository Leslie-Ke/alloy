# AlloyTeam 官网仿制项目

[![GitHub部署状态](https://img.shields.io/badge/GitHub%20Pages-在线浏览-success)](https://leslie-ke.github.io/alloy/)
[![Bootstrap版本](https://img.shields.io/badge/Bootstrap-5.3-7952B3)](https://getbootstrap.com/)

基于Bootstrap实现的AlloyTeam官网仿制项目，用于前端技术学习与实践。

![网站预览](./assets/uploads/banner_1.jpg)

> 🔔 声明：本项目为个人学习作品，非腾讯官方出品  
> 原官网地址：[https://www.alloyteam.com/](https://www.alloyteam.com/)

## 🚀 项目亮点
- **精准复刻**：1:1 还原原站核心视觉效果
- **移动优先**：完美适配手机端操作
- **轻量高效**：使用少量JS框架
- **交互细节**：
  - 导航栏动态下划线
  - 卡片悬停立体效果
  - 轮播图响应式高度
- **模块化设计**：
  - 导航栏
  - 轮播系统
  - 开源项目展示区
  - 技术作品陈列区

## 🛠️ 技术实现
| 技术点         | 实现方案                     |
|----------------|----------------------------|
| 响应式布局     | Bootstrap Grid + Flexbox    |
| 动态导航栏     | Bootstrap Navbar组件改造    |
| 轮播系统       | Bootstrap Carousel定制      |
| 悬停动画       | CSS3 Transform + Transition|
| 图标系统       | Bootstrap Icons + PNG Sprite|

## 📂 项目结构
```text
alloy/
├── index.html            # 主入口文件
├── README.md             # 项目说明文档
├── favicon.ico           # 网站图标
├── Bootstrap/            # Bootstrap框架文件
│   ├── css/              # Bootstrap样式文件
│   ├── js/               # Bootstrap脚本文件
│   └── font/             # 图标字体文件
├── assets/               # 静态资源
│   ├── images/           # 项目图片资源
│   └── uploads/          # 轮播图素材
├── css/                  # 自定义样式
│   └── index.css         # 主样式文件
└── less/                 # LESS预处理器文件
    └── (可添加.less源文件)
```
## 🚀 快速启动

### 方式一：直接运行
```bash
# 克隆项目到本地
git clone https://github.com/你的用户名/alloy-website-clone.git

# 进入项目目录
cd alloy-website-clone

# 使用任意方式打开：
# 方式1: 直接双击index.html
# 方式2: 使用VS Code的Live Server扩展
# 方式3: 执行Python简易服务器（需Python环境）
python -m http.server 8000
```

### 方式二：部署到你的仓库
1. 在你的GitHub创建新仓库
2. 本地初始化并关联：
```bash
git clone https://github.com/leslie-ke/alloy.git
cd alloy
git remote set-url origin https://github.com/你的用户名/你的仓库名.git
git push -u origin main
```
3. 开启GitHub Pages：  
仓库设置 → Pages → 选择 main 分支 → /root 目录 → Save

## 🛠️ 项目迁移指南

### 步骤1：克隆基础项目
```bash
git clone https://github.com/leslie-ke/alloy.git
```

### 步骤2：修改项目归属
```bash
# 进入项目目录
cd alloy

# 移除原有远程仓库
git remote remove origin

# 添加你的远程仓库
git remote add origin https://github.com/你的用户名/新仓库名.git

# 推送到你的仓库
git push -u origin main
```

### 步骤3：自定义内容
1. 替换`assets/images/`中的品牌图片
2. 修改`index.html`中的导航链接
3. 更新`index.css`中的主题颜色
4. 添加你自己的项目展示内容

## 🤝 参与改进指南

### 贡献流程
1. Fork本仓库
2. 创建特性分支：
```bash
git checkout -b feature/新功能名称
```
3. 开发并测试修改
4. 提交更改：
```bash
git add .
git commit -m "描述你的修改"
git push origin feature/新功能名称
```
5. 发起Pull Request

### 推荐改进方向
- **功能增强**
  - 添加页面加载动画
  - 实现更多响应式断点
  - 集成轻量级JS特效
- **内容优化**
  - 补充项目描述文案
  - 增加团队成员介绍
  - 更新技术博客模块
- **体验提升**
  - 优化移动端点击区域
  - 增加Prefetch预加载
  - 实现平滑滚动效果

## 💻 开发环境配置
1. 安装VS Code编辑器
2. 推荐扩展：
   - [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
   - [CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)
3. 浏览器调试工具：
   - Chrome DevTools
   - Firefox Responsive Design Mode

---

> 如果对本项目有任何问题或需要补充实际截图和调整任何内容，请随时告知！ 🚀  
> 最后如果你喜欢我的项目请给收藏或关注我🌟
