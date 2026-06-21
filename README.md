# GTM Skills

Open, production-grade go-to-market skills for AI agents — prospecting, research, outreach, pipeline, CRM, and revenue operations. Built by [Swan](https://getswan.com).

Each skill is a plain `SKILL.md` file that any agent can read — Claude Code, Cursor, Codex, Claude Desktop, and more. Use them anywhere, or run them with full execution inside Swan.

## Install

**Use with Swan** (one click, fully executable): browse the library at [our skills site] and hit **Use with Swan**.

**Claude Code / Cursor / Codex** (any CLI coding agent):

```bash
npx skills add swan-gtm/gtm-skills --skill cold-outreach -a claude-code
```

Swap `-a claude-code` for `cursor`, `codex`, etc. Drop `--skill` to install the whole pack.

**Claude Desktop / ChatGPT / Gemini** (no terminal): download a skill as a `.zip` from the site and upload it in your app's skills settings.

## Layout

```
skills/
  <category>/
    <skill-slug>/
      SKILL.md        # the skill — frontmatter + instructions
```

Categories: `icp`, `research`, `signals`, `prospecting`, `outreach`, `engagement`, `pipeline`, `customer`, `crm`, `reporting`, `competitive`.

## Frontmatter

```yaml
---
name: cold-outreach
description: Use this skill when… (dense trigger phrasing for routing)
author: swan
category: outreach
license: MIT
---
```

`author` is a slug; the full creator profile lives on the skills site.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Skills must be tool-agnostic (speak in GTM verbs, not vendor tool names), include a "What good looks like" section, and pass validation.

## License

MIT — see [LICENSE](LICENSE).
</content>
