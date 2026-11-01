# strunk-white

*The Elements of Style* as a Claude plugin. One skill sets the style; three apply its rules to text you already wrote.

## Install

From the Claude plugin directory, or in Claude Code:

```
/plugin install strunk-white --marketplace joso-skarica/strunk-white
```

## Skills

| Skill | What it does | How it triggers |
|---|---|---|
| `strunk-white-style` | Claude writes in plain, direct, economical prose for the rest of the conversation | By name only |
| `line-edit` | Tightens your draft and lists the changes | "edit this", "tighten", "polish" |
| `prose-check` | Reports clarity problems with counts and quoted examples; changes nothing | "check this", "review the writing", "critique" |
| `cut-to-length` | Shortens to a stated limit while keeping every claim | "under 300 words", "cut by a third", "one page" |

All four share the same rules: omit needless words, use the active voice, put statements in positive form, prefer the specific to the vague, and choose the plain word.

## Which one

- You want Claude to write that way → `strunk-white-style`
- You wrote it and want it fixed → `line-edit`
- You wrote it and want to fix it yourself → `prose-check`
- It has to fit a limit → `cut-to-length`

## Layout

```
strunk-white/
├── .claude-plugin/plugin.json
├── LICENSE.txt
├── README.md
└── skills/
    ├── strunk-white-style/SKILL.md
    ├── line-edit/SKILL.md
    ├── prose-check/SKILL.md
    └── cut-to-length/SKILL.md
```

## License

Apache 2.0. See LICENSE.txt. *The Elements of Style* (1918) is in the public domain; this plugin applies its rules and reproduces none of its text.
