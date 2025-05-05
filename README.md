# Nudge-GF (v4.1.7)

Nudge-GF is the Glassflow-native evolution of the Nudge auto-iteration engine. This version is modular, persona-driven, and composed entirely of atomic shards compiled by the Glassflow interpreter.

---

## What is Nudge-GF?

Nudge-GF iterates toward software and design goals automatically by splitting projects into intelligent subgoals. Each subsystem handles a specific domain, and all logic is expressed in proprietary Glassflow code using reusable `.shX` shards and `.gfX` modules.

---

## Subsystems

Each system is independently versioned and documented:

- [Core Engine](docs/core.md) – `v4.1.7`
- [Persona Engine](docs/personas.md) – `v2.9.0`
- [Iteration Controller](docs/iterations.md) – `v3.3.1`
- [Output Renderer](docs/output-engine.md) – `v2.2.5`
- [Glassflow Interpreter](docs/glassflow-interpreter.md) – `v1.0.0`
- [Compiler Interface](docs/compiler.md) – `v0.4.8`

---

## Shard Architecture

- `.shX` – atomic shards (code, data, behavior, persona)
- `.gfX` – file-level Glassflow modules
- `gfs` – registry file mapping shard structure

---

## Versioning Map

See `VERSION_MAP.md` for complete version lineage and semver rules.

---

## Development

```bash
git clone https://github.com/flypaper-creative/nudge-gf.git
cd nudge-gf
# Run shard graph, initialize system
```

---

Nudge-GF is maintained by Joshua Durden. All contributions are tracked through Glassflow-compatible iteration logs.
