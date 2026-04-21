# Claude Skills by Third Vector

Open-source Claude Skills built by [Third Vector](https://thirdvector.eu) for founders, operators, and GTM teams.

A Claude Skill is a structured set of instructions that Claude uses to guide a specific task, from writing an investment memo to enriching a sales target list. Well-designed skills produce sharper, more consistent output than an unprimed prompt, because they encode a repeatable process and the hard-won conventions of the domain.

We build these because we use them ourselves. If one is useful to you, fork it, improve it, send a pull request.

## Skills in this repository

### [investment-memo](./investment-memo/)

Walks a solo or early-stage founder through writing a rigorous Investment Memo for a new business. Five phases: calibrate, interview, draft, critical review, iterate. Produces a 5 to 8 page Word document plus a companion list of open questions and next experiments. The foundational strategy artefact that feeds into everything downstream: pitch decks, GTM plans, website copy, hiring pitches.

Background and recommended process: *[Write the Memo First](https://thirdv3ctor.substack.com)* on the Blueishprint *(link to be updated on publish)*.

## Installing a skill

Clone this repo and copy the skill folder you want into your local Claude skills directory.

```bash
git clone https://github.com/third-vector-eu/claude-skills.git
cp -r claude-skills/investment-memo ~/.claude/skills/
```

The target path depends on which Claude product you are using.

- **Claude Code**: `~/.claude/skills/` for a global skill, or `.claude/skills/` inside a project for a project-scoped skill.
- **Claude Desktop / Cowork**: `~/.claude/skills/` on macOS and Linux.

Once the skill folder sits in that path, Claude discovers it automatically. You invoke it by describing your task in natural language. The skill's description handles the triggering; you do not need to name it explicitly.

## Contributing

Pull requests welcome. If you improve an existing skill or add a new one, open a PR with a short description of what you changed and why. Issues with specific, reproducible examples are also useful.

## License

MIT. Use these skills however you like, commercially or otherwise. A credit is appreciated but not required.

## About Third Vector

[Third Vector](https://thirdvector.eu) helps European businesses become AI-native. Based in Rotterdam, the Netherlands. Follow the work on [The Blueishprint](https://thirdv3ctor.substack.com) and on [LinkedIn](https://www.linkedin.com/company/third-vector-eu).
