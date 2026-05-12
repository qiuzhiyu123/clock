# 横屏时钟小程序

模仿苹果无线充电时的时钟风格

## 使用方法

### 方法一：直接打开
1. 把 `index.html` 文件传到手机上
2. 用浏览器打开
3. 横屏使用

### 方法二：部署到网页（推荐）
1. 上传到任意静态托管服务（GitHub Pages、Vercel、Netlify 等）
2. 手机访问网址
3. 添加到主屏幕，像 App 一样使用

## 特点

- ✅ 纯黑背景
- ✅ 模仿苹果锁屏字体风格（细体、大字号）
- ✅ 横屏自适应
- ✅ 显示日期和星期
- ✅ 尝试保持屏幕常亮（需浏览器支持）
- ✅ 单文件，无需任何依赖

## 部署到 GitHub Pages

```bash
# 创建仓库
git init
git add index.html
git commit -m "Add clock app"
git branch -M main
git remote add origin https://github.com/你的用户名/clock-app.git
git push -u origin main

# 然后在 GitHub 仓库设置中开启 Pages
```

访问地址：`https://你的用户名.github.io/clock-app/`
