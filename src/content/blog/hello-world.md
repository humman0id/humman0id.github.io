---
title: 'Hello World & Math Rendering Test'
description: 'Testing Markdown, syntax highlighting, and KaTeX LaTeX equations.'
pubDate: '2026-11-20'
tags: ['meta', 'math', 'systems']
draft: false
---

Welcome to your new Astro blog! Everything is preconfigured for technical writing, Obsidian Markdown workflows, and automatic GitHub Pages deployment.

## LaTeX Math Support

Inline equations like $e^{i\pi} + 1 = 0$ and $\nabla \cdot \mathbf{E} = \frac{\rho}{\varepsilon_0}$ render cleanly at build time.

Block equations automatically scroll horizontally on mobile devices:

$$
\int_{-\infty}^{\infty} e^{-x^2} \, dx = \sqrt{\pi}
$$

## Syntax Highlighting

```python
def gaussian_integral_approx(n: int = 10000, bound: float = 10.0) -> float:
    dx = (2 * bound) / n
    total = sum(pow(2.718281828459045, -((-bound + i * dx) ** 2)) * dx for i in range(n))
    return total
```

## Obsidian Workflow

You can open `src/content/blog/` directly in Obsidian. Set `draft: true` in the YAML frontmatter while writing, and switch it to `draft: false` when you are ready to push and publish.
