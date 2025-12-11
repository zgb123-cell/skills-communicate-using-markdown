# Markdown 快速参考指南

这是一份简明的 Markdown 语法参考指南，帮助您快速查找常用的 Markdown 格式。

## 目录
- [标题](#标题)
- [文本样式](#文本样式)
- [列表](#列表)
- [链接](#链接)
- [图片](#图片)
- [代码](#代码)
- [引用](#引用)
- [表格](#表格)
- [任务列表](#任务列表)
- [水平分割线](#水平分割线)
- [Emoji](#emoji)

---

## 标题

```markdown
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```

**效果：**

# 一级标题
## 二级标题
### 三级标题

---

## 文本样式

```markdown
**粗体文本**
*斜体文本*
***粗斜体文本***
~~删除线文本~~
```

**效果：**

**粗体文本**  
*斜体文本*  
***粗斜体文本***  
~~删除线文本~~

---

## 列表

### 无序列表

```markdown
- 项目 1
- 项目 2
  - 子项目 2.1
  - 子项目 2.2
- 项目 3
```

**效果：**

- 项目 1
- 项目 2
  - 子项目 2.1
  - 子项目 2.2
- 项目 3

### 有序列表

```markdown
1. 第一项
2. 第二项
3. 第三项
   1. 子项 3.1
   2. 子项 3.2
```

**效果：**

1. 第一项
2. 第二项
3. 第三项
   1. 子项 3.1
   2. 子项 3.2

---

## 链接

```markdown
[链接文字](https://www.example.com)
[带标题的链接](https://www.example.com "鼠标悬停显示的标题")
```

**效果：**

[链接文字](https://www.example.com)

---

## 图片

```markdown
![图片替代文字](https://via.placeholder.com/150)
![带标题的图片](https://via.placeholder.com/150 "鼠标悬停显示的标题")
```

**效果：**

![图片替代文字](https://via.placeholder.com/150)

---

## 代码

### 行内代码

```markdown
这是一段 `行内代码`。
```

**效果：**

这是一段 `行内代码`。

### 代码块

````markdown
```
普通代码块
```

```python
# Python 代码块
def hello():
    print("Hello, World!")
```

```javascript
// JavaScript 代码块
function hello() {
    console.log("Hello, World!");
}
```
````

**效果：**

```python
# Python 代码块
def hello():
    print("Hello, World!")
```

---

## 引用

```markdown
> 这是一段引用。
> 
> 可以有多行。
>> 这是嵌套引用。
```

**效果：**

> 这是一段引用。
> 
> 可以有多行。
>> 这是嵌套引用。

---

## 表格

```markdown
| 列1 | 列2 | 列3 |
| --- | --- | --- |
| 数据1 | 数据2 | 数据3 |
| 数据4 | 数据5 | 数据6 |

| 左对齐 | 居中对齐 | 右对齐 |
| :--- | :---: | ---: |
| 文本 | 文本 | 文本 |
```

**效果：**

| 列1 | 列2 | 列3 |
| --- | --- | --- |
| 数据1 | 数据2 | 数据3 |
| 数据4 | 数据5 | 数据6 |

---

## 任务列表

```markdown
- [x] 已完成的任务
- [ ] 未完成的任务
- [ ] 另一个未完成的任务
```

**效果：**

- [x] 已完成的任务
- [ ] 未完成的任务
- [ ] 另一个未完成的任务

---

## 水平分割线

```markdown
---
***
___
```

**效果：**

---

## Emoji

```markdown
:smile: :heart: :thumbsup: :rocket: :star:
```

**效果（在 GitHub 上）：**

:smile: :heart: :thumbsup: :rocket: :star:

---

## 更多资源

- [GitHub Markdown 官方文档](https://docs.github.com/zh/get-started/writing-on-github)
- [Markdown 基础语法](https://www.markdownguide.org/basic-syntax/)
- [GitHub Flavored Markdown 规范](https://github.github.com/gfm/)
