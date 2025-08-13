# Code

## Overview

Markdown provides several ways to display code, from inline code snippets to code blocks.

## Inline Code

Use backticks for inline code:

```markdown
Use the `console.log()` function to print to the console.
```

## Code Blocks

Use triple backticks for code blocks:

```markdown
```javascript
function hello() {
    console.log("Hello, World!");
}
```
```

## Syntax Highlighting

Specify the language after the opening backticks:

```markdown
```python
def hello():
    print("Hello, World!")
```

```html
<div class="container">
    <h1>Hello World</h1>
</div>
```
```

## Indented Code Blocks

Use 4 spaces or 1 tab for indented code blocks:

```markdown
    function hello() {
        console.log("Hello, World!");
    }
```

## Examples

### Inline Code

The `git commit` command creates a new commit.

### Code Block

```javascript
function greet(name) {
    return `Hello, ${name}!`;
}
```

### With Syntax Highlighting

```python
def calculate_sum(a, b):
    return a + b
```

## Best Practices

- Use inline code for short snippets, function names, or commands
- Use code blocks for longer code examples
- Specify the language for syntax highlighting
- Keep code examples simple and relevant
- Test your code examples to ensure they work

---

**[← Back to Markdown Guide](../MARKDOWN.md)**
