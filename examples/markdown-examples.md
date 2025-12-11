# Markdown 示例文档

这个文档展示了各种 Markdown 语法的实际应用示例，帮助初学者理解如何在实际场景中使用 Markdown。

## 📚 文档结构示例

一个好的文档通常包含以下结构：

1. **标题和简介** - 说明文档的目的
2. **目录** - 方便快速导航
3. **主要内容** - 详细的信息和说明
4. **示例代码** - 实际的代码演示
5. **总结和资源** - 总结要点并提供额外资源

---

## 💼 项目 README 示例

以下是一个典型的项目 README 结构：

# 项目名称

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-green.svg)]()

> 这是一个简短的项目描述，用一两句话说明项目的用途。

## 功能特性

- ✨ 功能 1：做某件很酷的事情
- 🚀 功能 2：快速且高效
- 🔒 功能 3：安全可靠
- 📱 功能 4：响应式设计

## 快速开始

### 前置要求

在开始之前，请确保您已安装：

- Node.js (版本 >= 14.0)
- npm 或 yarn
- Git

### 安装步骤

```bash
# 克隆仓库
git clone https://github.com/username/project.git

# 进入项目目录
cd project

# 安装依赖
npm install

# 启动项目
npm start
```

### 配置

创建 `.env` 文件并添加以下配置：

```env
API_KEY=your_api_key_here
DATABASE_URL=your_database_url
PORT=3000
```

## 使用示例

### 基本用法

```javascript
const Project = require('project');

const app = new Project({
  apiKey: 'your_api_key',
  debug: true
});

app.run();
```

### 高级功能

```javascript
// 使用高级配置
const app = new Project({
  apiKey: 'your_api_key',
  options: {
    timeout: 5000,
    retries: 3,
    cache: true
  }
});

// 处理事件
app.on('success', (data) => {
  console.log('操作成功:', data);
});

app.on('error', (error) => {
  console.error('发生错误:', error);
});
```

## API 文档

### 方法列表

| 方法名 | 参数 | 返回值 | 描述 |
| --- | --- | --- | --- |
| `init()` | 无 | Promise | 初始化应用 |
| `run()` | options: Object | void | 运行应用 |
| `stop()` | 无 | void | 停止应用 |

## 贡献指南

我们欢迎所有形式的贡献！请阅读我们的贡献指南：

1. Fork 本仓库
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个 Pull Request

## 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 联系方式

- 作者：Your Name
- 邮箱：your.email@example.com
- 项目链接：[https://github.com/username/project](https://github.com/username/project)

---

## 📝 博客文章示例

# 如何开始使用 Markdown

**作者**: 张三 | **日期**: 2024-01-15 | **分类**: 教程

![Markdown Logo](https://markdown-here.com/img/icon256.png)

## 引言

Markdown 是一种轻量级标记语言，由 John Gruber 于 2004 年创建。它的设计理念是：

> "易读易写是 Markdown 的核心。一个 Markdown 格式的文档应该能够直接以纯文本形式发布，而不会看起来像被标记或格式化指令所污染。"

## 为什么使用 Markdown？

使用 Markdown 有很多好处：

1. **简单易学** - 语法简洁，几分钟就能掌握基础
2. **纯文本** - 可以用任何文本编辑器编辑
3. **平台无关** - 在任何操作系统上都能使用
4. **版本控制友好** - 与 Git 完美配合
5. **广泛支持** - GitHub、Reddit、Stack Overflow 等平台都支持

## 基础语法

让我们从最基本的语法开始：

### 段落和换行

在 Markdown 中，段落之间用空行分隔。如果需要在段落内换行，可以在行末添加两个空格。

### 强调文本

有三种方式强调文本：

- *斜体*：用一个星号或下划线包围
- **粗体**：用两个星号或下划线包围
- ***粗斜体***：用三个星号包围

### 列表

创建列表非常简单：

**购物清单：**
- 苹果
- 香蕉
- 橙子

**待办事项：**
1. 学习 Markdown 基础
2. 练习编写文档
3. 创建自己的项目文档

## 实用技巧

### 提示框

> 💡 **提示**: 使用引用符号创建提示框，使重要信息突出显示。

> ⚠️ **警告**: 这是一个警告信息，提醒用户注意潜在问题。

### 代码高亮

Markdown 支持多种编程语言的语法高亮：

```python
def fibonacci(n):
    """计算斐波那契数列"""
    if n <= 1:
        return n
    return fibonacci(n-1) + fibonacci(n-2)

print(fibonacci(10))
```

```javascript
// 快速排序算法
function quickSort(arr) {
  if (arr.length <= 1) return arr;
  
  const pivot = arr[0];
  const left = arr.slice(1).filter(x => x < pivot);
  const right = arr.slice(1).filter(x => x >= pivot);
  
  return [...quickSort(left), pivot, ...quickSort(right)];
}
```

## 总结

Markdown 是一个强大而简单的工具，适合各种场景：

- 📖 撰写技术文档
- 📝 写作博客文章
- 📋 创建待办列表
- 📧 编写邮件
- 💬 在线讨论和评论

开始使用 Markdown，您会发现它能极大提高您的写作效率！

---

**延伸阅读：**

- [Markdown 官方文档](https://daringfireball.net/projects/markdown/)
- [GitHub Flavored Markdown](https://github.github.com/gfm/)
- [Markdown 编辑器推荐](https://www.markdownguide.org/tools/)

---

## 🐛 Issue 报告示例

以下是如何在 GitHub 上撰写一个好的 issue：

# Bug 报告：登录功能失效

## 问题描述

当用户尝试使用邮箱和密码登录时，系统返回"认证失败"错误，即使凭证正确。

## 重现步骤

1. 访问登录页面 `https://example.com/login`
2. 输入有效的邮箱地址：`test@example.com`
3. 输入正确的密码
4. 点击"登录"按钮
5. 观察错误消息

## 期望行为

用户应该能够成功登录并跳转到仪表盘页面。

## 实际行为

系统显示错误消息："认证失败，请检查您的凭证"，即使凭证正确。

## 截图

![Error Screenshot](https://via.placeholder.com/600x400?text=Error+Screenshot)

## 环境信息

- **操作系统**: macOS 13.0
- **浏览器**: Chrome 120.0
- **应用版本**: v2.3.1

## 附加信息

### 控制台错误

```
POST https://api.example.com/auth/login 401 (Unauthorized)
Error: Authentication failed
    at handleLogin (auth.js:45)
    at onClick (LoginForm.js:23)
```

### 可能的原因

- 后端 API 可能更改了认证端点
- JWT token 验证逻辑可能有问题
- 数据库连接可能不稳定

## 优先级

- [x] 高优先级 - 影响核心功能
- [ ] 中优先级
- [ ] 低优先级

---

这些示例展示了 Markdown 在不同场景下的实际应用。通过学习和实践这些模式，您将能够创建清晰、专业的文档。
