<div align="center">
  <img src="assets/logo.jpg" alt="Guster-Ducks" width="160" style="border-radius: 24px; box-shadow: 0 4px 24px rgba(0,0,0,0.12);" />
  <h1>Guster-Ducks</h1>
</div>

A personal agent toolkit built on [Claude Code](https://docs.anthropic.com/en/docs/claude-code). Talk to Guster and manage the ducks. Ducks get things done.

Markdown specs, zero infrastructure. Each file is a spec for a capability — implement them in your own branch.

## Architecture

```
paths/              Ducks exchange info through files
   ↓
hi-ducks/           How you interact with ducks
   ↓
manage-ducks/       How you manage ducks
   ↓
duck-skills/        What ducks can do
  ├── engineering/    Code skills
  └── desktop-setup/  Desktop vibe skills
```

## Quick Start

```
git clone https://github.com/Lumos-789/Guster-Ducks.git
cd Guster-Ducks
claude
```

Open in Claude Code. Ducks deploy.

## License

[MIT](LICENSE)
