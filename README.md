# Scarlet — GPU‑accelerated terminal emulator

**Scarlet** is a Rust‑powered, WebGPU‑backed terminal aiming for WezTerm‑class
performance in a lightweight, MIT‑licensed code‑base.

## Features (work‑in‑progress)

- ✅ Asynchronous PTY reader (`scarlet-core`)
- ✅ Workspace‑wide build with Cargo
- [ ] Damage‑tracked renderer (`scarlet-gui`)
- [ ] Tabs & panes
- [ ] AI command palette (OpenAI)

## Quick start

```bash
git clone https://github.com/twiggy24/scarlet-term
cd scarlet-term
cargo run -p scarlet-gui --release
