# Graph Report - .  (2026-08-18)

## Corpus Check
- Corpus is ~8,855 words - fits in a single context window. You may not need a graph.

## Summary
- 35 nodes · 31 edges · 11 communities detected
- Extraction: 84% EXTRACTED · 16% INFERRED · 0% AMBIGUOUS · INFERRED: 5 edges (avg confidence: 0.71)
- Token cost: 0 input · 0 output
- Edge kinds: imports_from: 19 · semantically_similar_to: 5 · contains: 4 · references: 2 · cites: 1


## Input Scope
- Requested: auto
- Resolved: committed (source: cli)
- Included files: 29 · Candidates: 38
- Excluded: 1 untracked · 11109 ignored · 0 sensitive · 0 missing committed
- Recommendation: Use --scope all or graphify.yaml inputs.corpus for a knowledge-base folder.
## God Nodes (most connected - your core abstractions)
1. `Blog Placeholder Image 3` - 3 edges
2. `Using MDX (blog)` - 2 edges
3. `Blog Placeholder Image 4` - 2 edges
4. `blog` - 1 edges
5. `collections` - 1 edges
6. `AGENTS.md Agent Instructions` - 1 edges
7. `CLAUDE.md Project Instructions` - 1 edges
8. `Markdown Style Guide (blog)` - 1 edges
9. `Rob Pike Gopherfest 2015 Talk` - 1 edges
10. `HeaderLink Component` - 1 edges

## Surprising Connections (you probably didn't know these)
- `AGENTS.md Agent Instructions` --semantically_similar_to--> `CLAUDE.md Project Instructions`  [INFERRED] [semantically similar]
  AGENTS.md → CLAUDE.md
- `Blog Placeholder Image 3` --semantically_similar_to--> `Blog Placeholder Image 1`  [INFERRED] [semantically similar]
  src/assets/blog-placeholder-3.jpg → src/assets/blog-placeholder-1.jpg
- `Blog Placeholder Image 3` --semantically_similar_to--> `Blog Placeholder Image 2`  [INFERRED] [semantically similar]
  src/assets/blog-placeholder-3.jpg → src/assets/blog-placeholder-2.jpg
- `Blog Placeholder Image 4` --semantically_similar_to--> `Blog Placeholder Image 5`  [INFERRED] [semantically similar]
  src/assets/blog-placeholder-4.jpg → src/assets/blog-placeholder-5.jpg
- `Blog Placeholder Image 4` --semantically_similar_to--> `Blog Placeholder Image 3`  [INFERRED] [semantically similar]
  src/assets/blog-placeholder-4.jpg → src/assets/blog-placeholder-3.jpg

## Hyperedges (group relationships)
- **Blog Content Collection (src/content/blog)** — first_post, second_post, third_post, markdown_style_guide, using_mdx [EXTRACTED 1.00]
- **Identical Lorem Ipsum Placeholder Posts** — first_post, second_post, third_post [INFERRED 0.90]
- **Content Authoring Format Guides (Markdown and MDX)** — markdown_style_guide, using_mdx [INFERRED 0.75]
- **Placeholder Hero Image Set (blog-placeholder-*)** — blog-placeholder-1, blog-placeholder-2_image, blog-placeholder-3, blog-placeholder-4, blog-placeholder-5, blog-placeholder-about [INFERRED 0.90]

## Communities

### Community 2 - "Placeholder Hero Images"
Cohesion: 0.40
Nodes (5): Blog Placeholder Image 1, Blog Placeholder Image 2, Blog Placeholder Image 3, Blog Placeholder Image 4, Blog Placeholder Image 5

### Community 3 - "MDX Integration"
Cohesion: 0.67
Nodes (2): HeaderLink Component, Using MDX (blog)

### Community 4 - "Content Collections Config"
Cohesion: 0.67
Nodes (2): blog, collections

### Community 5 - "Agent Instructions"
Cohesion: 1.00
Nodes (2): AGENTS.md Agent Instructions, CLAUDE.md Project Instructions

### Community 6 - "Markdown Style Guide"
Cohesion: 1.00
Nodes (2): Markdown Style Guide (blog), Rob Pike Gopherfest 2015 Talk

### Community 8 - "About Page Image"
Cohesion: 1.00
Nodes (1): Blog Placeholder About Image

### Community 9 - "Site Favicon"
Cohesion: 1.00
Nodes (1): Site Favicon (favicon.svg)

### Community 10 - "First Post"
Cohesion: 1.00
Nodes (1): First Post (blog)

### Community 11 - "Project README"
Cohesion: 1.00
Nodes (1): Astro Starter Kit: Blog README

### Community 12 - "Second Post"
Cohesion: 1.00
Nodes (1): Second Post (blog)

### Community 13 - "Third Post"
Cohesion: 1.00
Nodes (1): Third Post (blog)

## Knowledge Gaps
- **16 isolated node(s):** `blog`, `collections`, `AGENTS.md Agent Instructions`, `CLAUDE.md Project Instructions`, `Astro Starter Kit: Blog README` (+11 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **Thin community `MDX Integration`** (2 nodes): `HeaderLink Component`, `Using MDX (blog)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Content Collections Config`** (2 nodes): `blog`, `collections`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Agent Instructions`** (2 nodes): `AGENTS.md Agent Instructions`, `CLAUDE.md Project Instructions`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Markdown Style Guide`** (2 nodes): `Markdown Style Guide (blog)`, `Rob Pike Gopherfest 2015 Talk`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `About Page Image`** (1 nodes): `Blog Placeholder About Image`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Site Favicon`** (1 nodes): `Site Favicon (favicon.svg)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `First Post`** (1 nodes): `First Post (blog)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Project README`** (1 nodes): `Astro Starter Kit: Blog README`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Second Post`** (1 nodes): `Second Post (blog)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Third Post`** (1 nodes): `Third Post (blog)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Are the 3 inferred relationships involving `Blog Placeholder Image 3` (e.g. with `Blog Placeholder Image 1` and `Blog Placeholder Image 2`) actually correct?**
  _`Blog Placeholder Image 3` has 3 INFERRED edges - model-reasoned connections that need verification._
- **Are the 2 inferred relationships involving `Blog Placeholder Image 4` (e.g. with `Blog Placeholder Image 5` and `Blog Placeholder Image 3`) actually correct?**
  _`Blog Placeholder Image 4` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `blog`, `collections`, `AGENTS.md Agent Instructions` to the rest of the system?**
  _16 weakly-connected nodes found - possible documentation gaps or missing edges._