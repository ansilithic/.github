# ANSILITHIC

**Precision command-line tools for macOS. Built from stone.**

ANSI codes meet lithic craft — terminal tools carved from the ground up with no excess, no bloat, no compromise.

---

### Philosophy

Every tool here is built with a single mandate: do one thing with absolute precision.

- **Native Swift.** Most binaries are written in Swift, compiled to bare metal on Apple Silicon. No interpreters. No runtimes. No garbage collectors between you and the machine.
- **Feels like macOS.** These tools respect the platform. They follow Apple's conventions, integrate with system services, and behave the way native software should. The terminal is part of the OS, not a escape hatch from it.
- **Zero dependencies on the host.** Runs on a virgin macOS install. No Homebrew. No third-party frameworks. Nothing you didn't ship with.
- **Containerized when necessary.** Anything that requires external dependencies runs inside Apple's native Containerization framework — full VM isolation, sub-second startup, zero residue.
- **Bleeding-edge macOS.** We target the latest. No backwards compatibility shims. No legacy workarounds. If Apple ships it, we use it.
- **Aesthetic is not optional.** Terminal output is deliberate. Every escape sequence, every glyph, every alignment is intentional.

### For whom

Developers who run their machines clean. Who care what's in `/usr/local/bin`. Who read man pages for pleasure and think `defaults write` is a power tool.

If you're still installing Python with Homebrew, this isn't for you yet.

---

*All repositories are private.*
