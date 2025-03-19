---
layout: post
title: "如何编写Jekyll博客文章"
date: 2025-03-19 10:00:00 +0800
categories: [教程, Jekyll]
tags: [博客, Markdown]
author: "博主"
---

## 如何编写博客文章

在Jekyll博客中编写文章非常简单，只需要遵循以下步骤：

1. 在`_posts`目录下创建新的Markdown文件
2. 文件名格式为：`YYYY-MM-DD-标题.md`
3. 在文件开头添加YAML前置数据
4. 使用Markdown语法编写文章内容

### YAML前置数据说明

```yaml
---
layout: post        # 文章布局，通常使用post
title: "文章标题"   # 文章标题
date: YYYY-MM-DD   # 发布日期
categories: []     # 文章分类
tags: []          # 文章标签
author: "作者名"    # 作者
---
```

### Markdown语法示例

- **粗体文本**
- *斜体文本*
- [链接文本](URL)
- ![图片描述](/assets/images/24021.jpg)

> 这是一个引用块

```python
# 这是代码块
print("Hello, Jekyll!")
```

### 本地预览

1. 确保已安装Jekyll环境
2. 在项目根目录运行 `jekyll serve`
3. 访问 `http://localhost:4000` 预览博客