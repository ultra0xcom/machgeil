# machgeil

**Mach geil.**  
Take code, writing, designs, plans, prompts, or implementations that already exist and make them substantially, noticeably better — until further real improvement would be marginal or overengineered.

An open agent skill for the [skills.sh](https://skills.sh) ecosystem.

## Install

```bash
npx skills add ultra0xcom/machgeil
```

This works in:
- Claude Code
- Cursor
- GitHub Copilot
- Codex / Windsurf
- Gemini CLI
- and 60+ other agents supported by skills.sh

See https://skills.sh for the full list and agent-specific instructions.

## What it does

Rejects "good enough", "it works", and "first clean version". Runs the full improvement loop defined in `SKILL.md` until the stopping condition.

The output should feel intentional, robust, elegant, and obviously the strongest reasonable version.

## Usage

Speak naturally:

- `mach geil this`
- `make this geil`
- `improve this until you can't make it better`
- `don't stop at good enough`
- `elevate / productionize / polish this hard`
- `mach geil the [component / README / prompt / plan / design]`

Works on anything that already exists and deserves to be excellent.

## Example triggers

- `mach geil this React component`
- `mach geil the README`
- `improve this ADR until it's the strongest version`
- `take this agent prompt and make it geil`
- `mach geil this implementation plan`

## Quality Bar

A machgeil result is:

- Correct, robust, clean
- Elegant and intentional
- Useful and practical
- Polished and maintainable

It makes people think: *"Yes. That is the version I actually wanted."*

Full criteria and domain-specific guidance live in `SKILL.md`.

## Philosophy

> Arbeite solange weiter, bis du der Meinung bist, du kannst das nicht mehr geiler machen.  
> Mach geil!

Preserve the user's intent.  
Upgrade execution until you honestly believe you cannot make it meaningfully better.

## Files

```
.
├── SKILL.md     # Agent instructions (the skill)
├── README.md    # Human docs + install
├── LICENSE
└── .gitignore
```

Pure instruction skill — no scripts required.

## Publishing & Contributing

This skill is published via GitHub + skills.sh.

### Install for yourself

```bash
npx skills add ultra0xcom/machgeil
```

### For maintainers

- The repo at https://github.com/ultra0xcom/machgeil is the source of truth.
- Any public GitHub repo with a valid `SKILL.md` in the root is automatically available via `npx skills add`.
- To test locally: `npx skills add ultra0xcom/machgeil`

Ideas that would genuinely make *this skill* more geil are welcome (issues or PRs). The skill applies its own standard: only meaningful improvements.

## License

MIT

## Credits

Original concept by the machgeil team.  
Crafted to agent-skills best practices (skills.sh / agentskills.io).

---

**Mach geil.** Don't settle.
