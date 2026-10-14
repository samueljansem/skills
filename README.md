# skills

Personal agent skills, installable with [`skills`](https://www.npmjs.com/package/skills):

```sh
npx skills add <this-repo> -g
```

| Skill | What it does |
|---|---|
| `writing` | Write and edit copy built from facts, and avoid the patterns that read as machine-written |
| `product-context` | Maintain `.agents/product-marketing.md`, the per-project facts that other skills read |

## What goes in a skill here

A skill should hold only what a capable model can't produce by itself: taste, conventions, hard constraints, and project-specific or proprietary knowledge. It should not hold generic frameworks, checklists, step-by-step procedures, fixed output templates or scripts, because those get in the way as models improve.

Skills that carry fresh facts a maintainer keeps up to date (for example SEO) stay installed from upstream instead of being copied here.
