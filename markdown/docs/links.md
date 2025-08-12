# Links

## Overview
Links allow you to connect your markdown documents to other resources on the web or within your project.

## Basic Links
Use square brackets for the text and parentheses for the URL:

```markdown
[Link text](URL)
```

## Examples

### Basic Link
[Google](https://www.google.com)

### Link with Title
```markdown
[Google](https://www.google.com "Google Homepage")
```

### Internal Links
```markdown
[Read more about headings](./headings.md)
[Go to top](#top)
```

### Reference Links
```markdown
[Google][google-link]

[google-link]: https://www.google.com "Google Homepage"
```

## Link Types

### External Links
```markdown
[GitHub](https://github.com)
[Stack Overflow](https://stackoverflow.com)
```

### Internal Links (Same Document)
```markdown
[Go to Introduction](#introduction)
[See Examples](#examples)
```

### Internal Links (Different Files)
```markdown
[Read about Headings](./headings.md)
[View Code Examples](./code.md)
```

## Best Practices
- Use descriptive link text
- Test your links to ensure they work
- Use relative paths for internal links
- Add titles for better accessibility
- Keep link text concise but informative
- Use reference links for frequently used URLs

---

**[← Back to Markdown Guide](../MARKDOWN.md)**
