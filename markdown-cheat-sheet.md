# Markdown Cheat Sheet

Thanks for visiting [The Markdown Guide](https://www.markdownguide.org)!

This Markdown cheat sheet provides a quick overview of all the Markdown syntax elements. It can’t cover every edge case, so if you need more information about any of these elements, refer to the reference guides for [basic syntax](https://www.markdownguide.org/basic-syntax) and [extended syntax](https://www.markdownguide.org/extended-syntax).

## Basic Syntax

These are the elements outlined in John Gruber’s original design document. All Markdown applications support these elements.

### Heading

# H1
## H2
### H3

### Bold

**bold text**

### Italic

*italicized text*

### Blockquote

> blockquote

### Ordered List

1. First item
2. Second item
3. Third item

### Unordered List

- First item
- Second item
- Third item

### Code

`code`

### Horizontal Rule

---

### Link

[Markdown Guide](https://www.markdownguide.org)

### Image

![alt text](https://www.markdownguide.org/assets/images/tux.png)

## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### Table

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

### Fenced Code Block

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Footnote

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### Heading ID

### My Great Heading {#custom-id}

### Definition List

term
: definition

### Strikethrough

~~The world is flat.~~

### Task List

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

### Emoji

That is so funny! :joy:

(See also [Copying and Pasting Emoji](https://www.markdownguide.org/extended-syntax/#copying-and-pasting-emoji))
There is separate file in detail for emoji [Link](emoji-cheat-sheet.md).

### Highlight

I need to highlight these ==very important words==.
Above recommendation does not work for VS Code so use `<mark>`to highlight. Sample user case <mark>highlight this</mark>.
<!-- markdownlint-disable-file MD033 -->
### Subscript

H~2~O

### Superscript

X^2^

### Mermaid related documentation

[Overall documentation](https://mermaid.js.org/intro/n00b-syntaxReference.html)
[Video reference on styling mermaid](https://www.youtube.com/watch?v=-XV1JBfhgWo)
[Color reference](https://htmlcolorcodes.com/)
I had to add section to flow chart, was able to do that using subgraph refer to 03 January 2023 notes.

### Special Keys

You can add special keys in following way. This breaks linting rule MD03, which suggest no inline HTML.

<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Space</kbd>
