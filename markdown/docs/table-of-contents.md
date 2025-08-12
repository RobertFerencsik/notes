# Table of Contents (TOC)

## Overview
A Table of Contents provides navigation and structure for longer markdown documents.

## Manual TOC
Create links to your headings manually:

```markdown
## Table of Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Basic Syntax](#basic-syntax)
  - [Headings](#headings)
  - [Paragraphs](#paragraphs)
- [Advanced Topics](#advanced-topics)
- [Conclusion](#conclusion)
```

## Automatic TOC
Many markdown processors support automatic TOC generation:

### GitHub/GitLab Style
```markdown
## Table of Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Basic Syntax](#basic-syntax)
  - [Headings](#headings)
  - [Paragraphs](#paragraphs)
- [Advanced Topics](#advanced-topics)
- [Conclusion](#conclusion)
```

### VS Code Extension
Use extensions like "Markdown All in One" to auto-generate TOCs.

## Anchor Links
Headings automatically become anchor links. Convert them to lowercase and replace spaces with hyphens:

```markdown
# Main Heading -> #main-heading
## Sub Heading -> #sub-heading
### Another Heading -> #another-heading
```

## Best Practices
- Place TOC near the top of the document
- Keep it updated when you add new sections
- Use consistent formatting
- Limit depth to 2-3 levels for readability
- Test all links to ensure they work correctly

---

**[← Back to Markdown Guide](../MARKDOWN.md)**
