# READ ME CHEAT SHEET  

- In ***Markdown***, which is commonly used for README files on GitHub, special characters and formatting syntax are used to create headings, subheadings, and other elements. Here's a quick guide:

## Headings
- Heading 1: # Heading 1
- Heading 2: ## Heading 2
- Heading 3: ### Heading 3
- Heading 4: #### Heading 4
- Heading 5: ##### Heading 5
- Heading 6: ###### Heading 6

## Text Formatting
- Bold: **bold text** or __bold text__
- Italic: *italic text* or _italic text_
- Bold + Italic: ***bold and italic text***
- Strikethrough: ~~strikethrough~~

## Lists
>Unordered List:
markdown
- Item 1
- Item 2
  - Subitem 1
  - Subitem 2
>Ordered List:
markdown
1. First item
2. Second item
    1. Subitem 1
    2. Subitem 2
## Links
Inline Link: [link text](https://example.com)
Reference Link:
markdown
Copy code
[link text][id]

[id]: https://example.com

## Images
Image Syntax: ![alt text](image_url) Example:
markdown

![My Image](https://example.com/image.png)

## Code
- Inline Code: `inline code`
- Code Block:

```markdown
```language
Your code here
```

```javascript
Copy code
Replace `language` with the programming language for syntax highlighting (e.g., `python`, `javascript`, `html`).
```

## Blockquote
- Quote Text: > This is a blockquote.

## Horizontal Rule
- Add a line break with:
```markdown
---
```
## Tables

```markdown
| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Row 1    | Data     | More Data|
| Row 2    | Data     | More Data|
```