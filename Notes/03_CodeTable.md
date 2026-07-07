# 代码与表格

[← 回到主目录](00_Index.md)

## 代码

### 行内代码
使用反引号 `` ` `` 包裹：

```markdown
这是`行内代码`的示例
```
显示为：这是`行内代码`的示例

### 代码块
使用三个反引号，可指定编程语言：

````markdown
```javascript
function hello() {
  console.log("Hello, World!");
}
```
````

### 常见编程语言标识
```markdown
```python
def hello():
    print("Hello")
```

```java
public class Hello {
  public static void main(String[] args) {
    System.out.println("Hello");
  }
}
```

```sql
SELECT * FROM users WHERE id = 1;
```

```bash
echo "Hello, World!"
```

```

支持的语言：javascript、python、java、cpp、c、ruby、php、go、rust、sql、html、css、bash、shell 等。


```
---

## 表格

### 基本表格
```markdown
| 列1 | 列2 | 列3 |
|-----|-----|-----|
| 单元格1 | 单元格2 | 单元格3 |
| 单元格4 | 单元格5 | 单元格6 |
```

显示为：

| 列1   | 列2   | 列3   |
| ---- | ---- | ---- |
| 单元格1 | 单元格2 | 单元格3 |
| 单元格4 | 单元格5 | 单元格6 |

### 表格对齐

```markdown
| 左对齐 | 居中对齐 | 右对齐 |
|:------|:--------:|-------:|
| 左1 | 中1 | 右1 |
| 左2 | 中2 | 右2 |
```

对齐符号说明：
- `:------` 左对齐
- `:-----:` 居中对齐
- `-----:` 右对齐
- `------` 默认（通常左对齐）

### 表格中的特殊字符
```markdown
| 特殊字符 | 说明 |
|---------|------|
| \| | 竖线需要用反斜杠转义 |
```

---

**上一页：** [[02_Links&Images|链接与图片]]

**下一页：** [[04_Quotes&Tasks|引用与任务]]
