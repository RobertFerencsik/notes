# Math

## Overview
Mathematical expressions can be written in markdown using LaTeX syntax, supported by many platforms including GitHub.

## Inline Math
Use single dollar signs for inline math:

```markdown
The quadratic formula is $x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$
```

## Block Math
Use double dollar signs for block math:

```markdown
$$
\int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi}
$$
```

## Common Mathematical Symbols

### Greek Letters
```markdown
$\alpha, \beta, \gamma, \delta, \epsilon, \theta, \lambda, \mu, \pi, \sigma, \phi, \omega$
```

### Operators
```markdown
$\sum, \prod, \int, \frac{a}{b}, \sqrt{x}, \sqrt[n]{x}$
```

### Subscripts and Superscripts
```markdown
$x^2, x_i, x_{i,j}, x^{n+1}$
```

### Fractions and Brackets
```markdown
$\frac{a}{b}, \left(\frac{a}{b}\right), \left[\frac{a}{b}\right]$
```

## Examples

### Inline Examples
- The area of a circle is $A = \pi r^2$
- The sum of the first $n$ integers is $\sum_{i=1}^{n} i = \frac{n(n+1)}{2}$
- Euler's identity: $e^{i\pi} + 1 = 0$

### Block Examples
$$
\begin{align}
(a + b)^2 &= a^2 + 2ab + b^2 \\
&= a^2 + b^2 + 2ab
\end{align}
$$

$$
\begin{matrix}
a & b \\
c & d
\end{matrix}
$$

## Best Practices
- Use inline math for short expressions
- Use block math for longer equations
- Test math rendering in your target platform
- Use proper LaTeX syntax
- Consider accessibility for screen readers
- Keep equations simple and readable

---

**[← Back to Markdown Guide](../MARKDOWN.md)**
