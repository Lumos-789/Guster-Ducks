<div align="center">
  <img src="assets/logo.jpg" alt="Guster-Ducks" width="180" />
</div>

# Guster-Ducks

A personal agent toolkit built on [Claude Code](https://docs.anthropic.com/en/docs/claude-code). Talk to Guster and manage the ducks. Ducks get things done.

Markdown specs, zero infrastructure. Each file is a spec for a capability — implement them in your own branch.

## Architecture

```
paths/          Ducks exchange info through files
   ↓
hi-ducks/       How you interact with ducks
   ↓
manage-ducks/   How you manage ducks
   ↓
duck-skills/    What ducks can do
```

Data flows down. Components decouple through `paths/`.

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
