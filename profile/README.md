# ANSILITHIC

Command-line tools for macOS — written in Swift, designed for Apple Silicon. Human-made. Agent-grade.

Every tool outputs beautiful ANSI for humans at the terminal and structured JSON for agents on the wire. Built on the ancient standards (stdin, stdout, exit codes, pipes) that still work as the best integration layer between humans and machines.

```sh
brew tap ansilithic/tap
```

---

### Agent context

Tools that surface app data and system state — giving agents ambient awareness of the environment they're operating in.

| Tool | Install | Description |
|------|---------|-------------|
| [**icloud**](https://github.com/ansilithic/icloud) | source | Unified CLI for 15+ Apple apps — Mail, Calendar, Messages, Notes, Find My, and more |
| [**saddle**](https://github.com/ansilithic/saddle) | `brew install ansilithic/tap/saddle` | Local repo inventory — what's cloned, dirty, or out of sync |
| [**plzfix**](https://github.com/ansilithic/plzfix) | source | Document review and annotation for Word and PowerPoint files |

### Agent safety

Drop-in replacements that make destructive operations reversible — critical when agents run with elevated privileges.

| Tool | Install | Description |
|------|---------|-------------|
| [**rm**](https://github.com/ansilithic/rm) | `brew install ansilithic/tap/rm` | Moves files to Trash instead of permanent deletion |
| [**rmdir**](https://github.com/ansilithic/rmdir) | `brew install ansilithic/tap/rmdir` | Moves directories to Trash instead of permanent deletion |

### System visibility

macOS system information, readable and parseable.

| Tool | Install | Description |
|------|---------|-------------|
| [**dns**](https://github.com/ansilithic/dns) | source | DNS and network configuration |
| [**nic**](https://github.com/ansilithic/nic) | source | Network interfaces and addresses |
| [**ping**](https://github.com/ansilithic/ping) | `brew install ansilithic/tap/ping` | Ping with timestamps, color-coding, and packet loss summary |
| [**ps**](https://github.com/ansilithic/ps) | source | Processes with active network connections |
| [**path**](https://github.com/ansilithic/path) | source | PATH entries with source files and ownership |
| [**hostname**](https://github.com/ansilithic/hostname) | source | System hostname |
| [**daemons**](https://github.com/ansilithic/daemons) | source | Launch agents and daemons |

### Capture

Terminal output as shareable artifacts.

| Tool | Install | Description |
|------|---------|-------------|
| [**cli2png**](https://github.com/ansilithic/cli2png) | source | Terminal output → PNG/SVG screenshot |
| [**cli2gif**](https://github.com/ansilithic/cli2gif) | source | Terminal recording → animated GIF |
| [**json2clr**](https://github.com/ansilithic/json2clr) | source | JSON color palettes → macOS .clr files |

### Foundation

| Library | Description |
|---------|-------------|
| [**swift-cli-core**](https://github.com/ansilithic/swift-cli-core) | Shared styling, table formatting, dual-output (ANSI/JSON), and structured messaging |
