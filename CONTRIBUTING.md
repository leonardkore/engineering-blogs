# Contributing

Thanks for helping improve this directory. Please follow the rules below so the list stays clean, consistent, and easy to maintain.

## What We Include

Include a blog **only if it is company‑controlled and engineering‑focused**:

- Official company engineering blogs
- Official team‑run sub‑blogs (e.g., data, ml, sre, security) that are clearly company‑controlled
- Official Medium/Substack publications linked from the company site or org profile

Exclude:

- Personal blogs
- Marketing/newsroom pages
- Paywalled or login‑required blogs

## Verification (Required)

All new entries must pass a medium verification bar:

1. **Link loads** (no 404s or dead redirects)
2. **Engineering‑focused** (spot check content)

If a link redirects to a non‑engineering destination, do not include it.

## Entry Format

```
- **Company** — [blog](https://example.com) — Tags: [topic: x] [sector: y] [region: z] [lang: xx]
```

Rules:

- Use the most common brand name for the company
- Ignore leading “The/An/A” and punctuation when sorting
- Companies that start with numbers/symbols go under the **#** section
- Multiple blogs must be pipe‑separated; link text must be a topic label
  - Example: `- **Company** — [ml](...) | [security](...) — Tags: ...`
- Omit any unknown tag brackets (tagless entries are allowed)
- Add `[lang: xx]` only if the blog is predominantly non‑English
- Use `[lang: mixed]` only if content is predominantly non‑English and mixed

## Tags

**Topic (required list):** backend, frontend, mobile, data, ml, sre, security, infra

**Sector (required list):** consumer, enterprise, fintech, health, ecommerce, media, devtools, gaming, edtech

**Region (required list):** na, latam, emea, apac, global

New tags require maintainer approval. If a new tag is approved, update the **Tag Glossary** and **indexes** in the same PR.

## Mirrors

List only the primary canonical link. Add a mirror only if:

- It has substantively different posts, **or**
- The primary source is stale (no posts in 12 months) or incomplete

## PR Requirements

- **Max 50 entries per PR**
- **Include evidence links in the PR description** for team‑run blogs
- **Complete the verification checkbox** in the PR template
- **List entry count and source lists used** in the PR description

## Sorting and Naming

- Use the most common brand name
- If a company renamed or merged, use the current name and add `(formerly X)`
- If names collide, disambiguate with parenthetical HQ region
- If anchors still collide, append a numeric suffix (e.g., `(emea-2)`)
- Non‑Latin names should be transliterated, with native script optionally in parentheses

## Seeding Policy

Seeding from public lists is allowed, but every entry must be verified before merge. Cite source lists in PR notes (not README).
