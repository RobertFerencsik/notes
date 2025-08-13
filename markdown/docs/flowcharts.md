# Flowcharts

## Overview

Flowcharts can be created in markdown using Mermaid syntax, which is supported by many platforms including GitHub and GitLab.

## Basic Syntax

Use Mermaid code blocks:

```markdown
```mermaid
flowchart TD
    A[Start] --> B{Decision?}
    B -->|Yes| C[Do Something]
    B -->|No| D[Do Nothing]
    C --> E[End]
    D --> E
```
```

## Common Elements

### Start/End

```mermaid
flowchart TD
    A([Start]) --> B([End])
```

### Process

```mermaid
flowchart TD
    A[Process Step] --> B[Another Process]
```

### Decision

```mermaid
flowchart TD
    A{Is it true?} -->|Yes| B[Do This]
    A -->|No| C[Do That]
```

### Input/Output

```mermaid
flowchart TD
    A[/Input/] --> B[Process]
    B --> C[/Output/]
```

## Example Flowchart

```mermaid
flowchart TD
    A[Start] --> B{User logged in?}
    B -->|No| C[Show Login Form]
    B -->|Yes| D[Show Dashboard]
    C --> E{Valid Credentials?}
    E -->|No| C
    E -->|Yes| D
    D --> F[End]
```

## Best Practices

- Keep flowcharts simple and readable
- Use descriptive labels
- Maintain consistent styling
- Test your flowchart in the target platform
- Use appropriate shapes for different types of elements
- Consider the flow direction (TD = top-down, LR = left-right)

---

**[← Back to Markdown Guide](../MARKDOWN.md)**
