# what_to_eat_today
choose what to eat today randomly

今天吃什么 - 随机选餐助手
一个简单有趣的随机选餐应用，帮你解决"今天吃什么"的经典难题！
功能特点
🎲 一键随机选择菜品
🔄 滚动动画效果，增加趣味性
📱 响应式设计，支持手机和电脑访问
🍽️ 内置20道家常菜选项
本地运行
直接在浏览器中打开 what_to_eat.html 文件即可使用。
部署到 GitHub Pages
方法一：通过 GitHub 网页界面部署
创建仓库
登录 GitHub，点击右上角 "+" → "New repository"
仓库名称填写：what-to-eat（或其他你喜欢的名字）
选择 "Public" 或 "Private"
勾选 "Initialize this repository with a README"
点击 "Create repository"
上传文件
进入仓库页面，点击 "Add file" → "Upload files"
拖拽或选择 what_to_eat.html 文件上传
在 "Commit changes" 中填写提交信息
点击 "Commit changes"
启用 GitHub Pages
进入仓库页面，点击 "Settings"
在左侧菜单中找到 "Pages"（在 "Code and automation" 部分）
在 "Build and deployment" 部分：
Source 选择：Deploy from a branch
Branch 选择：main（或 master）
Folder 选择：/(root)
点击 "Save"
等待部署完成
大约 1-3 分钟后，GitHub 会生成访问链接
在 Pages 设置页面会显示你的网站地址，格式类似：https://你的用户名.github.io/what-to-eat/
方法二：通过 Git 命令行部署
# 1. 克隆仓库（替换为你的仓库地址）
git clone https://github.com/你的用户名/what-to-eat.git
cd what-to-eat

# 2. 复制文件到仓库目录
cp /path/to/what_to_eat.html .

# 3. 提交并推送
git add what_to_eat.html
git commit -m "Add what to eat application"
git push origin main
然后按照方法一的步骤 3-4 启用 GitHub Pages。
方法三：创建完整的项目仓库（推荐）
如果你想创建一个包含 README 和其他配置文件的完整仓库：
# 1. 创建本地项目文件夹
mkdir what-to-eat
cd what-to-eat

# 2. 初始化 Git 仓库
git init

# 3. 复制项目文件
# 确保当前目录下有：what_to_eat.html, README.md, .gitignore

# 4. 提交文件
git add .
git commit -m "Initial commit"

# 5. 连接到 GitHub 仓库
git remote add origin https://github.com/你的用户名/what-to-eat.git
git branch -M main
git push -u origin main
自定义菜品
打开 what_to_eat.html，找到以下代码块修改菜品列表：
const dishes = [
    "红烧肉", "宫保鸡丁", "麻婆豆腐", // 添加或修改你喜欢的菜品
    // ...
];
技术栈
HTML5
CSS3 (渐变动画、响应式设计)
JavaScript (ES6)
License
MIT License
贡献
欢迎提交 Issue 和 Pull Request！
