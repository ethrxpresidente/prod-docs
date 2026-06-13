# prod-docs

Public documentation source for ethrx products. Each product has its own
directory, versioned per release. Pages are MDX with YAML frontmatter; the
documentation site renders this tree directly.

## Layout

```
<product-lowercase>/
  v<version>/
    _meta.json        # sidebar label + ordered slugs
    <slug>.mdx        # one page per file
```

## Products

| product | version | pages |
|---------|---------|-------|
| dragon  | v0.1.0  | 9     |
| chaos   | v0.1.0  | 10    |
| halo    | v0.1.0  | 9     |
| raidr   | v0.1.0  | 9     |

Each `.mdx` page begins with frontmatter (`title`, `slug`, `product`,
`version`, `order`, `eyebrow`, `description`) followed by the page body.
