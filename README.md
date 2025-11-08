# 📘 Markdown Formatting Reference
A quick guide to Markdown syntax for formatting text, lists, links, images, code, and more.

## ✍️ Text Formatting
- **Bold**: `**bold**` or `__bold__` → **bold**
- *Italic*: `*italic*` or `_italic_` → *italic*
- ***Bold & Italic***: `***bold italic***` → ***bold italic***
- ~~Strikethrough~~: `~~strikethrough~~` → ~~strikethrough~~
- `Inline code`: `` `code` `` → `code`
- Blockquote: `> quoted text` → <blockquote>quoted text</blockquote>

## 📋 Lists
### Unordered List
- Item A
- Item B
  - Subitem B1
  - Subitem B2
- Item C
- Item D

### Ordered List
1. First
2. Second
   1. Subitem
   2. Subitem

## 🔗 Links and Images
- Link: `[Link text](https://example.com)` → [Link text](https://example.com)
- Reference-style link:
  ```
  [Google][1]

  [1]: https://google.com
  ```
- Image: `![Alt text](https://example.com/image.png)` → ![Alt text](https://example.com/image.png)

## 📌 Headings
```
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

## 📐 Horizontal Rule
```
---
***
___
```

## 🧮 Code Blocks
### Inline
Use `code` for inline snippets.

### Multiline fenced code block (with optional language)
```python
def hello():
    print("Hello, Markdown!")
```

### Indented code block (less common)
    def hello():
        print("Indented code block")

## 📊 Tables
| Column A | Column B |
|----------|----------|
| Value 1  | Value 2  |
| Value 3  | Value 4  |

## ✅ Task Lists
- [x] Completed task
- [ ] Incomplete task

## 🔣 Escaping Characters
```
\*literal asterisks\*
\# not a heading
\`not code\`
```

## 🧩 HTML in Markdown
```html
<b>Bold with HTML</b>
<br>
<span style="color:red">Red text</span>
```

## 🧠 Advanced Tricks
- Nesting elements: lists inside blockquotes, code inside lists
- Combining styles: `**_bold italic_**` → **_bold italic_**
- Footnotes example:
  ```
  This is a statement.[^1]

  [^1]: Footnote text.
  ```
- Collapsible sections:
  <details>
    <summary>Click to expand</summary>
    Content inside the collapsible section.
  </details>
- Emoji (GitHub style): `:smile:` → 😄

## 🤝 Accessibility and Best Practices
- Always include meaningful alt text for images
- Use headings in logical order
- Prefer semantic structure over visual tricks
- Keep lines short for readability

## 💻 Platform Notes
- GitHub Flavored Markdown supports tables, task lists, mentions, emojis, and reference links.
- CommonMark is widely used; some platforms extend it.
- VS Code previews depend on renderer and extensions.

## 📑 Quick Cheatsheet
- Bold: `**text**`
- Italic: `*text*`
- Inline code: `` `code` ``
- Code block: ` ```lang ... ``` `
- Link: `[text](url)`
- Image: `![alt](url)`
- List: `- item` or `1. item`
- Table: `| a | b |`
- Blockquote: `> quote`
- Horizontal rule: `---`
- Task: `- [ ] task`

## 📦 Admonition & Callout Blocks
These are Markdown extensions used in GitHub, VS Code, Obsidian, MkDocs, Docusaurus, etc. The HTML below shows the Markdown syntax itself as code samples.

### 🔔 Common Block Types

- **Note**
  
> [!NOTE]
> 
> This is a note block. Use it for general tips or reminders.
  
- **Important**
  
> [!IMPORTANT]
> This is an important block. Use it for critical information.
  
- **Warning**
  
> [!WARNING]
> 
> This is a warning block. Use it for cautions or potential issues.
  
- **Tip**
  
> [!TIP]
> 
> This is a tip block. Use it for helpful suggestions.
  
- **Caution**
  
> [!CAUTION]
> 
> This is a caution block. Use it for things that could go wrong.
  
### 🛠️ Notes on Usage
- In **GitHub Markdown**, these render as styled callouts.
- In **VS Code Markdown Preview Enhanced**, they also work.
- In **MkDocs/Docusaurus**, admonitions may use `!!! note` or `:::note` instead.
- Always check your platform’s documentation for exact syntax.

### 📑 Cheatsheet
```
> [!NOTE]      → General info
> [!IMPORTANT] → Critical info
> [!WARNING]   → Cautionary info
> [!TIP]       → Helpful suggestion
> [!CAUTION]   → Potential danger
> [!EXAMPLE]   → Illustrative example
```

## Further Customization

See the project GitHub: [**Glasgow-Uni-Notes**][project-link]

[project-link]: https://github.com/NoahDomingues/Glasgow-Uni-Notes
