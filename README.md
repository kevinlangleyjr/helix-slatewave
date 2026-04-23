<div align="center">

# Slatewave for Helix

A dark Helix theme built around a slate foundation and a teal signature, with sky / rose / purple / amber accents pulled from the same palette as the companion [VSCode](https://github.com/kevinlangleyjr/vscode-slatewave), [Neovim](https://github.com/kevinlangleyjr/neovim-slatewave), [Zed](https://github.com/kevinlangleyjr/zed-slatewave), [Sublime Text](https://github.com/kevinlangleyjr/sublime-text-slatewave), [JetBrains](https://github.com/kevinlangleyjr/jetbrains-slatewave), [Obsidian](https://github.com/kevinlangleyjr/obsidian-slatewave), and [Oh My Posh](https://github.com/kevinlangleyjr/slatewave-omp) themes. Designed so every tool you use speaks the same visual language.

> _Slate below, teal above._

</div>

---

## Palette

### Foundation — slate

The editor, statusline, and popups all live in the slate scale.

| | Hex | Tailwind | Where |
|---|---|---|---|
| ![#0f172a](https://placehold.co/20x20/0f172a/0f172a.png) | `#0f172a` | slate-900 | ink on accent surfaces (status mode block) |
| ![#1e293b](https://placehold.co/20x20/1e293b/1e293b.png) | `#1e293b` | slate-800 | statusline, popups, menus, rulers |
| ![#21252b](https://placehold.co/20x20/21252b/21252b.png) | slate-chrome | bufferline background |
| ![#282c34](https://placehold.co/20x20/282c34/282c34.png) | slate-editor | editor surface, gutter |
| ![#334155](https://placehold.co/20x20/334155/334155.png) | `#334155` | slate-700 | selection, menu selected row |
| ![#3a3f4c](https://placehold.co/20x20/3a3f4c/3a3f4c.png) | slate-guide | indent guide |
| ![#475569](https://placehold.co/20x20/475569/475569.png) | `#475569` | slate-600 | virtual text |

### Text — slate (inverse)

| | Hex | Tailwind | Where |
|---|---|---|---|
| ![#64748b](https://placehold.co/20x20/64748b/64748b.png) | `#64748b` | slate-500 | comments, line numbers, inactive text |
| ![#94a3b8](https://placehold.co/20x20/94a3b8/94a3b8.png) | `#94a3b8` | slate-400 | operators, punctuation, inactive statusline |
| ![#cbd5e1](https://placehold.co/20x20/cbd5e1/cbd5e1.png) | `#cbd5e1` | slate-300 | parameters, struct fields, properties |
| ![#e2e8f0](https://placehold.co/20x20/e2e8f0/e2e8f0.png) | `#e2e8f0` | slate-200 | default foreground |

### Signature — teal

The "wave" in Slatewave. Primary accent across the editor and companion prompt.

| | Hex | Tailwind | Where |
|---|---|---|---|
| ![#5eead4](https://placehold.co/20x20/5eead4/5eead4.png) | `#5eead4` | teal-300 | **primary accent** — cursor, active line number, strings, statusline fg, normal mode badge |
| ![#99f6e4](https://placehold.co/20x20/99f6e4/99f6e4.png) | `#99f6e4` | teal-200 | types, constructors, inline code, insert mode badge |

### Accents

| | Hex | Role |
|---|---|---|
| ![#38bdf8](https://placehold.co/20x20/38bdf8/38bdf8.png) | `#38bdf8` | keywords, tags, info diagnostics, select mode badge, markdown links |
| ![#7dd3fc](https://placehold.co/20x20/7dd3fc/7dd3fc.png) | `#7dd3fc` | functions, methods, JSON/YAML keys |
| ![#b388ff](https://placehold.co/20x20/b388ff/b388ff.png) | `#b388ff` | storage (`const`/`let`/`fn`), `this`/`self`, attributes, directives |
| ![#fb7185](https://placehold.co/20x20/fb7185/fb7185.png) | `#fb7185` | numbers, constants, booleans, errors, diff minus |
| ![#fbbf24](https://placehold.co/20x20/fbbf24/fbbf24.png) | `#fbbf24` | decorators, escape chars, macros, warnings, diff delta |

---

## Syntax mapping

Mirrors the rest of the Slatewave family — same code lights up the same way across every editor.

| Token | | Color | Style |
|---|---|---|---|
| Comments | ![#64748b](https://placehold.co/20x20/64748b/64748b.png) | `#64748b` | italic |
| Keywords (`if`, `return`, `import`) | ![#38bdf8](https://placehold.co/20x20/38bdf8/38bdf8.png) | `#38bdf8` | — |
| Storage (`const`, `let`, `fn`, `class`) | ![#b388ff](https://placehold.co/20x20/b388ff/b388ff.png) | `#b388ff` | italic |
| Types, constructors | ![#99f6e4](https://placehold.co/20x20/99f6e4/99f6e4.png) | `#99f6e4` | — |
| Functions, methods | ![#7dd3fc](https://placehold.co/20x20/7dd3fc/7dd3fc.png) | `#7dd3fc` | — |
| Strings | ![#5eead4](https://placehold.co/20x20/5eead4/5eead4.png) | `#5eead4` | — |
| Numbers, booleans, constants | ![#fb7185](https://placehold.co/20x20/fb7185/fb7185.png) | `#fb7185` | — |
| Regex | ![#fb7185](https://placehold.co/20x20/fb7185/fb7185.png) | `#fb7185` | — |
| Escape sequences, macros | ![#fbbf24](https://placehold.co/20x20/fbbf24/fbbf24.png) | `#fbbf24` | — |
| Decorators / attributes | ![#fbbf24](https://placehold.co/20x20/fbbf24/fbbf24.png) | `#fbbf24` | italic |
| `this` / `self` / builtins | ![#b388ff](https://placehold.co/20x20/b388ff/b388ff.png) | `#b388ff` | italic |
| Parameters | ![#cbd5e1](https://placehold.co/20x20/cbd5e1/cbd5e1.png) | `#cbd5e1` | italic |
| Fields / properties | ![#cbd5e1](https://placehold.co/20x20/cbd5e1/cbd5e1.png) | `#cbd5e1` | — |
| Operators, punctuation | ![#94a3b8](https://placehold.co/20x20/94a3b8/94a3b8.png) | `#94a3b8` | — |
| HTML/JSX tags | ![#38bdf8](https://placehold.co/20x20/38bdf8/38bdf8.png) | `#38bdf8` | — |
| HTML/JSX attributes | ![#b388ff](https://placehold.co/20x20/b388ff/b388ff.png) | `#b388ff` | italic |
| Markdown headings | ![#5eead4](https://placehold.co/20x20/5eead4/5eead4.png) | `#5eead4` | bold |
| Markdown links | ![#38bdf8](https://placehold.co/20x20/38bdf8/38bdf8.png) | `#38bdf8` | underline |
| Diff plus / minus / delta | teal / rose / amber | — | — |

---

## Mode colors

Helix surfaces the current editing mode on the statusline and the primary cursor. Slatewave maps each mode to a distinct accent so the active mode is readable at a glance:

| Mode | Badge bg | Cursor bg |
|---|---|---|
| Normal | ![#5eead4](https://placehold.co/20x20/5eead4/5eead4.png) `#5eead4` teal-300 | ![#5eead4](https://placehold.co/20x20/5eead4/5eead4.png) teal-300 |
| Insert | ![#99f6e4](https://placehold.co/20x20/99f6e4/99f6e4.png) `#99f6e4` teal-200 | ![#99f6e4](https://placehold.co/20x20/99f6e4/99f6e4.png) teal-200 |
| Select | ![#38bdf8](https://placehold.co/20x20/38bdf8/38bdf8.png) `#38bdf8` sky-400 | ![#38bdf8](https://placehold.co/20x20/38bdf8/38bdf8.png) sky-400 |

Badge ink is always `#0f172a` slate-900 for maximum contrast against the accent.

---

## Installation

Requires Helix **24.03+** (for modern theme scopes like `ui.bufferline`, `ui.virtual.inlay-hint`, and curly diagnostic underlines).

### From a local clone

```sh
git clone https://github.com/kevinlangleyjr/helix-slatewave.git
cp helix-slatewave/themes/slatewave.toml ~/.config/helix/themes/slatewave.toml
```

Then enable it in `~/.config/helix/config.toml`:

```toml
theme = "slatewave"
```

Or pick it at runtime:

```
:set theme slatewave
```

Helix reloads themes on file save, so you can edit `~/.config/helix/themes/slatewave.toml` and changes apply immediately.

### Symlink for live editing

If you're tweaking the theme, symlink the repo file instead of copying:

```sh
ln -s "$PWD/helix-slatewave/themes/slatewave.toml" ~/.config/helix/themes/slatewave.toml
```

---

## Customize

Helix themes can inherit from each other via `inherits`. To override a single key without forking, create `~/.config/helix/themes/slatewave-mine.toml`:

```toml
inherits = "slatewave"

"ui.background" = { fg = "#e2e8f0", bg = "#0a0f1e" }
"comment" = { fg = "#475569", modifiers = ["italic"] }
```

Then set `theme = "slatewave-mine"` in your config. All Slatewave palette names (`slate-800`, `teal-300`, `purple`, …) remain available in the inherited theme.

---

## Companion themes

Slatewave was designed as a single palette shared across every tool in Kevin's workflow. Git status, diagnostics, and syntax roles map 1:1 between them.

- [vscode-slatewave](https://github.com/kevinlangleyjr/vscode-slatewave)
- [neovim-slatewave](https://github.com/kevinlangleyjr/neovim-slatewave)
- [zed-slatewave](https://github.com/kevinlangleyjr/zed-slatewave)
- [sublime-text-slatewave](https://github.com/kevinlangleyjr/sublime-text-slatewave)
- [jetbrains-slatewave](https://github.com/kevinlangleyjr/jetbrains-slatewave)
- [obsidian-slatewave](https://github.com/kevinlangleyjr/obsidian-slatewave)
- [slatewave-omp](https://github.com/kevinlangleyjr/slatewave-omp) — Oh My Posh prompt
- [alacritty-slatewave](https://github.com/kevinlangleyjr/alacritty-slatewave) · [ghostty-slatewave](https://github.com/kevinlangleyjr/ghostty-slatewave) · [iterm2-slatewave](https://github.com/kevinlangleyjr/iterm2-slatewave) · [wezterm-slatewave](https://github.com/kevinlangleyjr/wezterm-slatewave) · [tmux-slatewave](https://github.com/kevinlangleyjr/tmux-slatewave) · [starship-slatewave](https://github.com/kevinlangleyjr/starship-slatewave)

See the landing page at [getslatewave.com](https://getslatewave.com) for the full family.

---

## Contributing

Issues and PRs welcome. For palette tweaks, please include a before/after screenshot of the same file so the visual tradeoff is obvious.

---

## License

WTFPL — Do What The Fuck You Want To Public License. See [LICENSE](LICENSE).
