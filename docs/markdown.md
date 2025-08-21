Markdown 是一种轻量级的标记语言，语法简洁易读，常用于撰写文档、笔记、博客等。以下是 Markdown 的基本语法规则（基于 CommonMark 标准）：

---

### 1. 标题（Headings）
使用 `#` 表示标题，`#` 的数量代表标题层级（共6级）。

```markdown
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```

---

### 2. 段落与换行
- 段落之间用空行分隔。
- 强制换行：在行尾加两个空格，或使用 `<br>` 标签。

```markdown
这是第一段。

这是第二段。  
这是同一段的换行。
```

---

### 3. 强调（粗体、斜体）
- 斜体：用 `*` 或 `_` 包裹文本。
- 粗体：用 `**` 或 `__` 包裹文本。
- 粗斜体：用 `***` 或 `___` 包裹文本。

```markdown
*斜体* 或 _斜体_
**粗体** 或 __粗体__
***粗斜体*** 或 ___粗斜体___
```

---

### 4. 列表
#### 无序列表（项目符号）
使用 `-`、`*` 或 `+`：

```markdown
- 项目一
- 项目二
  - 子项目（缩进2个空格或1个制表符）
```

#### 有序列表
使用数字加 `.`：

```markdown
1. 第一项
2. 第二项
   1. 子项
```

---

### 5. 链接（Links）
格式：`[显示文本](URL)`

```markdown
[百度](https://www.baidu.com)
```

可选：添加标题（鼠标悬停提示）：

```markdown
[Google](https://www.google.com "搜索引擎")
```

---

### 6. 图片（Images）
格式：`![替代文本](图片URL)`

```markdown
![Logo](https://example.com/logo.png)
```

> 注：`!` 表示是图片，`[]` 中是替代文本（图片无法加载时显示）。

---

### 7. 引用（Blockquote）
使用 `>` 开头：

```markdown
> 这是一段引用。
>
> 可以多行。
```

可嵌套：

```markdown
> 一级引用
>> 二级引用
```

---

### 8. 代码
#### 行内代码
用反引号 `` ` `` 包裹：

```markdown
使用 `console.log()` 输出。
```

#### 代码块
使用三个反引号 ``` 或缩进4个空格：

````markdown
```javascript
function hello() {
  console.log("Hello, Markdown!");
}
```
````

> 可在第一个 ``` 后指定语言，实现语法高亮。

---

### 9. 分隔线（Horizontal Rule）
使用三个或以上的 `-`、`*` 或 `_`（单独一行）：

```markdown
---
***
___
```

---

### 10. 表格（Tables）
使用 `|` 和 `-` 创建表格：

```markdown
| 姓名 | 年龄 | 城市     |
|------|------|----------|
| 张三 | 25   | 北京     |
| 李四 | 30   | 上海     |
```

对齐方式（可选）：
- `:---` 左对齐
- `:---:` 居中
- `---:` 右对齐

```markdown
| 左对齐 | 居中 | 右对齐 |
|:------|:----:|-------:|
| A     | B    | C      |
```

---

### 11. 转义字符
使用反斜杠 `\` 转义特殊字符：

```markdown
\*这不是斜体\*
\# 不是标题
```

常用转义字符：
- `\` `\` → `\`
- `\*` → `*`
- `\#` → `#`
- `\[` → `[`
- etc.

---

### 12. 其他（部分扩展语法）
> 注意：以下语法非所有 Markdown 解析器都支持，但常见于 GitHub Flavored Markdown（GFM）：

- **删除线**：`~~删除线~~`
- **任务列表**：
  ```markdown
  - [x] 完成任务
  - [ ] 待办任务
  ```
- **自动链接**：`<https://example.com>` 或 `example@email.com`

---

### 小贴士
- Markdown 文件通常以 `.md` 或 `.markdown` 为扩展名。
- 编辑器推荐：Typora、VS Code、Obsidian、Notion 等都支持 Markdown。

---

✅ 掌握以上语法，即可满足大多数写作需求。  
📘 更多高级用法可参考 [CommonMark 官方文档](https://commonmark.org/) 或 [GitHub Flavored Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)。