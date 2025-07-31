# GitHub Pages 部署指南

## 快速部署步骤

### 1. 创建GitHub仓库
1. 登录GitHub账户
2. 点击右上角 "+" 号，选择 "New repository"
3. 仓库名称建议：`wz222-portfolio` 或 `dna-researcher-portfolio`
4. 选择 "Public"（公开）
5. 不要初始化README文件（我们已经有自己的README）
6. 点击 "Create repository"

### 2. 上传文件
将以下文件上传到仓库：
- `index.html` - 主页面文件
- `profile-photo.jpg` - 个人头像
- `README.md` - 项目说明
- `.gitignore` - Git忽略文件

### 3. 启用GitHub Pages
1. 进入仓库设置（Settings）
2. 左侧菜单找到 "Pages"
3. Source选择 "Deploy from a branch"
4. Branch选择 "main" 或 "master"
5. 点击 "Save"

### 4. 访问网站
几分钟后，您的网站将在以下地址可用：
`https://[您的用户名].github.io/[仓库名]/`

## 文件说明

- **index.html** - 网站主页面，包含所有功能和样式
- **profile-photo.jpg** - 个人头像图片
- **README.md** - 项目介绍和说明文档
- **.gitignore** - Git版本控制忽略文件配置

## 自定义修改

### 更换头像
1. 准备新的头像图片
2. 重命名为 `profile-photo.jpg`
3. 上传替换原文件

### 修改个人信息
编辑 `index.html` 文件中的相应部分：
- 个人姓名和简介
- 研究方向
- 发表论文
- 联系方式

### 修改颜色主题
在 `index.html` 的CSS部分修改颜色变量：
```css
:root {
    --primary-bg: #0a0a0a;        /* 主背景色 */
    --accent-color: #00ffaa;      /* 主要强调色 */
    --accent-secondary: #00ccff;  /* 次要强调色 */
}
```

## 注意事项

1. **文件大小** - GitHub Pages对单个文件有大小限制，图片建议压缩到合理大小
2. **更新频率** - 修改文件后，GitHub Pages可能需要几分钟才能更新
3. **HTTPS** - GitHub Pages自动提供HTTPS支持
4. **自定义域名** - 可以在设置中配置自定义域名

## 故障排除

### 网站无法访问
- 检查仓库是否为公开
- 确认GitHub Pages已启用
- 等待几分钟让部署完成

### 图片无法显示
- 确认图片文件名正确
- 检查图片文件是否已上传
- 验证文件路径是否正确

### 样式问题
- 清除浏览器缓存
- 检查CSS语法是否正确
- 确认所有文件都已上传

---

如有问题，请检查GitHub Pages的部署日志或联系技术支持。 