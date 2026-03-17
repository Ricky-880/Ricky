# 🌐 TikTok API 申请专用官网

这是八嘎为主人创建的 TikTok API 申请专用官网模板！

---

## 🚀 快速部署（3 种方法）

### 方法一：GitHub Pages（免费，推荐）

```bash
# 1. 创建 GitHub 仓库
# 访问 https://github.com/new
# 仓库名：globalcross-ecom

# 2. 上传文件
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/globalcross-ecom.git
git push -u origin main

# 3. 启用 GitHub Pages
# Settings → Pages → Source: main branch → Save
# 等待 2-5 分钟，网站上线！

# 4. 获取网址
# https://YOUR_USERNAME.github.io/globalcross-ecom/
```

### 方法二：Vercel（免费，更快）

```bash
# 1. 安装 Vercel CLI
npm install -g vercel

# 2. 部署
cd /home/admin/.openclaw/workspace/tiktok-website
vercel

# 3. 按提示操作
# - Login (GitHub/Google)
# - 确认部署
# - 获取网址（如：globalcross-ecom.vercel.app）
```

### 方法三：Netlify（免费，简单）

```bash
# 1. 访问 https://app.netlify.com/drop
# 2. 拖拽整个 tiktok-website 文件夹
# 3. 等待上传完成
# 4. 获取网址（如：globalcross-ecom.netlify.app）
```

---

## 📝 需要修改的内容

打开 `index.html`，搜索并替换以下内容：

| 原文 | 替换为 |
|------|--------|
| `GlobalCross E-commerce` | 你的公司英文名 |
| `contact@globalcross-ecom.com` | 你的邮箱 |
| `privacy@globalcross-ecom.com` | 你的隐私邮箱 |
| `[Your City, Country]` | 你的城市/国家 |
| `[Your Business Address]` | 你的地址（可选） |

---

## ✅ 部署后检查清单

- [ ] 网站可以正常访问
- [ ] 隐私政策页面完整
- [ ] 联系方式有效
- [ ] 网站加载速度快
- [ ] 手机端显示正常

---

## 🔗 用于 TikTok API 申请

网站上线后，在 TikTok API 申请中填写：

```
Company Website: https://YOUR_USERNAME.github.io/globalcross-ecom/
Privacy Policy: https://YOUR_USERNAME.github.io/globalcross-ecom/#privacy
```

---

## 💡 进阶：绑定自定义域名

```bash
# 1. 买域名（阿里云/腾讯云，¥50-80/年）
# 推荐：globalcross-ecom.com

# 2. 配置 DNS
# GitHub Pages: 添加 CNAME 文件
# Vercel/Netlify: 后台添加域名

# 3. 等待 DNS 生效（5-30 分钟）

# 4. 网站地址变为：
# https://www.globalcross-ecom.com
```

---

**有问题随时叫八嘎！🤖**
