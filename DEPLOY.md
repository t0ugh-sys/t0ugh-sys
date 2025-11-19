# 🚀 部署说明

## 📋 部署步骤

### 1. 在 GitHub 创建仓库

1. 访问 https://github.com/new
2. 仓库名称：`t0ugh-sys` （必须与用户名完全一致）
3. 设置为 **Public**（公开）
4. **不要**勾选 "Add a README file"（我们已经准备好了）
5. 点击 "Create repository"

### 2. 连接远程仓库并推送

在当前目录 `d:\code\t0ugh-sys` 执行：

```bash
# 添加远程仓库
git remote add origin https://github.com/t0ugh-sys/t0ugh-sys.git

# 添加所有文件
git add .

# 提交
git commit -m "feat: 添加超级炫酷的个人主页 🚀"

# 推送到 GitHub
git branch -M main
git push -u origin main
```

### 3. 激活贪吃蛇动画

1. 访问 https://github.com/t0ugh-sys/t0ugh-sys/actions
2. 点击左侧 "Generate Snake Animation"
3. 点击右侧 "Run workflow" → "Run workflow"
4. 等待 1-2 分钟完成

### 4. 查看效果

访问你的个人主页：https://github.com/t0ugh-sys

---

## ✏️ 需要修改的内容

打开 `README.md`，修改以下内容：

### 1. 社交媒体链接（第 265-270 行）

```markdown
[![Email](...))](mailto:your-email@example.com)  # 改成你的邮箱
[![Twitter](...))](https://twitter.com/your-handle)  # 改成你的 Twitter
[![LinkedIn](...))](https://linkedin.com/in/your-profile)  # 改成你的 LinkedIn
```

### 2. 个人信息（第 25-30 行）

```typescript
const t0ugh_sys = {
    location: "🌏 Building the Future",  // 改成你的位置
    funFact: "I turn coffee ☕ into code..."  // 改成你的个性签名
};
```

### 3. 如果你有其他项目

在 "Featured Projects" 部分添加更多项目。

---

## 🎨 可选：自定义配色

当前使用 **Indigo Purple** 主题（`#6366f1`）

如果想换成其他颜色，全局替换：

```bash
# Ocean Blue
sed -i 's/6366f1/0ea5e9/g' README.md

# Neon Green
sed -i 's/6366f1/10b981/g' README.md

# Sunset Orange
sed -i 's/6366f1/f97316/g' README.md
```

---

## 📊 包含的统计图表

✅ GitHub Stats（基础统计）
✅ Top Languages（语言分布）
✅ Streak Stats（连续提交）
✅ Activity Graph（活动图表）
✅ GitHub Trophies（成就奖杯）
✅ Profile Summary（5个详细卡片）
✅ Contribution Snake（贪吃蛇动画）
✅ Random Dev Quote（随机名言）
✅ Random Dev Meme（随机梗图）

---

## 🔧 故障排除

### Q: 统计图表不显示？
A: 等待 5-10 分钟，GitHub API 有缓存。

### Q: 贪吃蛇动画不显示？
A: 确保 Actions 已成功运行，并且有 `output` 分支。

### Q: 如何更新内容？
A: 修改 README.md 后，执行：
```bash
git add README.md
git commit -m "docs: 更新个人主页"
git push origin main
```

---

## 🎉 完成！

部署完成后，你的个人主页会自动显示所有统计数据和炫酷效果！

**访问地址**: https://github.com/t0ugh-sys
