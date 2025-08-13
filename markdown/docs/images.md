# Images

## Overview

Images can be embedded in markdown documents to enhance visual content and provide context.

## Basic Syntax

Use an exclamation mark, alt text in brackets, and the image URL in parentheses:

```markdown
![Alt text](image-url)
```

## Examples

### Basic Image

```markdown
![Markdown Logo](https://markdown-here.com/img/icon256.png)
```

### Image with Title

```markdown
![Markdown Logo](https://markdown-here.com/img/icon256.png "Markdown Logo")
```

### Local Images

```markdown
![Local Image](./images/logo.png)
![Relative Path](../assets/image.jpg)
```

### Reference Style

```markdown
![Alt text][image-ref]

[image-ref]: ./images/logo.png "Logo"
```

## Image Sizing

Some markdown processors support image sizing:

```markdown
![Image](url){width=300px height=200px}
```

## Best Practices

- Always provide meaningful alt text for accessibility
- Use appropriate image formats (PNG, JPG, SVG)
- Optimize images for web (compress when possible)
- Use descriptive filenames for local images
- Consider image loading times and file sizes
- Test how images render in different markdown viewers

---

**[← Back to Markdown Guide](../MARKDOWN.md)**
