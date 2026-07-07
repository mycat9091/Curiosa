# 链接与图片

[← 回到主目录](00_Index.md)

## 链接

### 基本链接
```markdown
[链接文本](https://example.com)
```
显示为：[链接文本](https://example.com)

### 带标题的链接
```markdown
[链接文本](https://example.com "悬停时显示的标题")
```

### 直接URL
```markdown
<https://example.com>
```

### 参考链接
```markdown
这是一个[参考链接][ref1]

[ref1]: https://example.com
```

---

## 内部链接（Obsidian特有）

### 基本内部链接
链接到同一库中的其他笔记：

```markdown
[[笔记名称]]
```

点击后会打开该笔记，且自动在该笔记中显示反向链接。

### 自定义链接文本
```markdown
[[笔记名称|显示的文本]]
```
链接指向"笔记名称"，但显示为"显示的文本"。

### 链接到特定标题
```markdown
[[笔记名称#二级标题]]
[[笔记名称#二级标题|显示的文本]]
```

### 包含空格的笔记名称
```markdown
[[文件夹/笔记 名称]]
```

---

## 图片

### 基本图片
```markdown
![图片替代文本](图片路径或URL)
```

示例：
```markdown
![Obsidian Logo](https://obsidian.md/images/obsidian-logo.svg)
```

### 本地图片
```markdown
![我的图片](image.png)
![图片](./folder/image.jpg)
```

### 指定图片大小（Obsidian特有）
```markdown
![图片|100x100](image.png)
![图片|150](image.png)
```

- `|100x100` 指定宽度和高度
- `|150` 只指定宽度，高度自动调整

---

## 嵌入文件（Obsidian特有）

### 嵌入笔记
```markdown
![[笔记名称]]
```
会在当前位置显示整个笔记的内容。

### 嵌入笔记的特定部分
```markdown
![[笔记名称#标题]]
```
只显示该笔记中特定标题下的内容。

### 嵌入图片
```markdown
![[image.png]]
```

### 嵌入代码块
```markdown
![[笔记名称#^块ID]]
```

---

**上一页：** [[01_BasicSyntax|基础语法]]

**下一页：** [[03_CodeTable|代码与表格]]
