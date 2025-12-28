---
title: "On Simplicity"
description: "Why simple solutions often beat complex ones, and how to resist the urge to over-engineer."
date: 2024-12-20
tags: ["engineering", "philosophy"]
---

Simplicity is underrated.

In software engineering, there's a constant temptation to add complexity. More abstractions, more layers, more indirection. It feels productive. It feels like you're building something substantial.

But complexity has costs:

- **Cognitive load** — More moving parts means more to keep in your head
- **Debugging difficulty** — When things break, where do you even start?
- **Onboarding friction** — New team members take longer to become productive
- **Maintenance burden** — Every line of code is a liability

## The right amount of complexity

The goal isn't zero complexity. Some problems are genuinely complex, and the solution needs to reflect that.

The goal is *appropriate* complexity. No more than necessary.

```
Complexity should be proportional to the problem being solved.
```

## How to stay simple

A few heuristics I try to follow:

1. **Start with the simplest thing that could work** — You can always add complexity later
2. **Question every abstraction** — Does this actually help, or does it just feel smart?
3. **Delete code liberally** — The best code is no code
4. **Resist premature optimization** — Solve the problem first, optimize if needed

Simple isn't easy. It takes discipline to resist the pull of complexity.

But it's worth it.

