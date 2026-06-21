# Contributing

In the early phase, skills are authored by the Swan team. This repo is the source of truth for skill **content**; a sync job mirrors merged changes into the product.

## Adding or editing a skill

1. Create `skills/<category>/<slug>/SKILL.md`.
2. Include frontmatter: `name`, `description`, `author`, `category`, `license`.
3. Open a PR. Merging to `main` publishes the change.

## Quality bar

- **Tool-agnostic.** Speak in GTM verbs ("check the CRM", "load the ICP"), not vendor tool names. Skills must work whether the org runs HubSpot, Salesforce, Attio, a spreadsheet, or nothing.
- **Dense description.** Lead with "Use this skill when…" + the outcome. The router reads this to decide when to fire the skill.
- **"What good looks like" required.** Every skill states what a great output is vs. a mediocre one.
- **No rot.** No dates, "recently added", or UI-specific references.
- **Compact.** Target ~600 words of instructions. If you're past ~800, split a concern into a sub-page.

## Slugs are stable

The folder slug is the skill's permanent identity — it's the key the product syncs against. Renaming a slug is a breaking change; avoid it.
</content>
