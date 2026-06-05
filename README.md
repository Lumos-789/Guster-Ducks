# Guster-Duck

You talk to Guster, Guster manages the ducks, ducks get things done.

A personal agent toolkit built on [Claude Code](https://docs.anthropic.com/en/docs/claude-code). Markdown specs, zero infrastructure.

## Architecture

```
paths/          Agents exchange info through files
   ↓
hi-duck/        How you interact with ducks
   ↓
manage-duck/    How you manage ducks
   ↓
duck-skills/    What ducks can do
```

Data flows down. Components decouple through `paths/` — writers don't know who reads, readers don't know who writes.

## Quick Start

```
git clone https://github.com/Lumos-789/Guster-Duck.git
cd Guster-Duck
cat CLAUDE.md          # understand the structure
ls duck-skills/        # pick your skills
```

`main` branch is specs only. Branch off to add your implementation.

## License

[MIT](LICENSE)
