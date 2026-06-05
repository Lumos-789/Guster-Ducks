# Guster-Ducks

A personal agent toolkit built on [Claude Code](https://docs.anthropic.com/en/docs/claude-code). You talk to Guster, Guster manages the ducks, ducks get things done.

Markdown specs, zero infrastructure. Each file is a spec for a capability — implement them in your own branch.

## Architecture

```
paths/          Agents exchange info through files
   ↓
hi-ducks/       How you interact with ducks
   ↓
manage-ducks/   How you manage ducks
   ↓
duck-skills/    What ducks can do
```

Data flows down. Components decouple through `paths/` — writers don't know who reads, readers don't know who writes.

## Quick Start

```
git clone https://github.com/Lumos-789/Guster-Ducks.git
cd Guster-Ducks
cat CLAUDE.md          # understand the structure
ls duck-skills/        # pick your skills
```

`main` branch is specs only. Branch off to add your implementation.

## License

[MIT](LICENSE)
