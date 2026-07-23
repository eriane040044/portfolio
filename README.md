# 我的作品集网站

iOS 风格磨砂玻璃效果的个人作品集网站，支持散文、诗歌、获奖作品展示。

## ✨ 特性

- **iOS 风格 UI**：磨砂玻璃效果（backdrop-filter）、圆润设计
- **个人信息侧栏**：可编辑姓名、头衔、简介、邮箱、电话、所在地
- **教育经历管理**：支持添加、编辑、删除多条教育经历
- **作品管理**：支持添加、编辑、删除、筛选、查看详情
- **拖拽排序**：自定义作品排列顺序
- **数据本地保存**：所有数据存储在 localStorage，刷新不丢失
- **响应式布局**：适配桌面端和移动端
- **单文件部署**：只需部署一个 `index.html` 文件

## 🚀 快速开始

### 方式一：直接打开（最快）

双击 `index.html` 即可在浏览器中打开使用。

### 方式二：本地预览

```bash
# Python 3
python3 -m http.server 8000

# 或 Node.js
npx serve .
```

然后访问 http://localhost:8000

## 📦 部署到 GitHub Pages

### 步骤 1：在 GitHub 创建新仓库

1. 打开 https://github.com/new
2. 仓库名填：`portfolio`（或任意你喜欢的名字）
3. 选择 **Public**（公开，GitHub Pages 免费）
4. **不要**勾选 Add a README
5. 点击 **Create repository**

### 步骤 2：推送代码

在本地项目目录中执行：

```bash
git init
git add .
git commit -m "feat: 初始化个人作品集网站"
git branch -M main
git remote add origin https://github.com/你的用户名/portfolio.git
git push -u origin main
```

### 步骤 3：开启 GitHub Pages

1. 进入仓库页面 → **Settings** → **Pages**
2. **Source** 选择 `Deploy from a branch`
3. **Branch** 选择 `main`，文件夹选 `/ (root)`
4. 点击 **Save**
5. 等待 1-2 分钟，页面会显示访问地址：

```
https://你的用户名.github.io/portfolio/
```

把这个地址用浏览器打开，就是你的作品集网站了！

## 📝 使用说明

### 编辑个人信息

- 点击头像右下角的 ✏️ 按钮或点击个人简介区域
- 可以修改姓名、头衔、个人简介
- 点击邮箱/电话/所在地可单独修改

### 管理教育经历

- 鼠标悬停到教育经历条目上
- 出现 ✏️ 和 🗑️ 按钮可编辑/删除
- 点击「添加教育经历」可新增

### 添加作品

1. 点击右上角「添加作品」按钮
2. 填写标题、选择分类（散文/诗歌/获奖作品）、日期
3. 在文本框中粘贴或输入作品内容
4. 点击保存

### 作品筛选

- 点击顶部 Tab：全部 / 散文 / 诗歌 / 获奖作品

### 重新排序

1. 点击「重新排序」按钮
2. 拖拽卡片到你想要的位置
3. 再次点击「重新排序」退出排序模式

## 🛠 技术栈

- 纯 HTML + CSS + JavaScript
- 无任何外部依赖
- 使用 CSS `backdrop-filter` 实现磨砂玻璃效果
- 数据存储：`localStorage`

## 📄 许可

MIT License
