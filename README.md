# Hi, I'm DelmarMG91 👋

I build **small, sharp, dependency-free command-line tools** in Python and
Node.js. Each project does one thing well, ships with tests, and installs in
seconds — no services, no build step, nothing to compile.

---

## Featured

### jsonpeek — a tiny jq-style JSON query CLI

Point at a value with dots and brackets; no filter DSL to learn.

![jsonpeek demo](https://raw.githubusercontent.com/DelmarMG91/jsonpeek/main/docs/demo.gif)

```console
$ jsonpeek 'users[*].name' examples/users.json
[ "Alice", "Bob", "Chen Wei" ]
```

→ [github.com/DelmarMG91/jsonpeek](https://github.com/DelmarMG91/jsonpeek)

---

## Toolbox

### Python

| Project | What it does |
| --- | --- |
| [**jsonpeek**](https://github.com/DelmarMG91/jsonpeek) | Zero-dependency `jq`-style JSON query CLI (`a.b`, `users[*].name`, `--format table`). |
| [**pycliphist**](https://github.com/DelmarMG91/pycliphist) | Cross-platform clipboard history manager backed by SQLite. |
| [**gitignore-gen**](https://github.com/DelmarMG91/gitignore-gen) | Smart `.gitignore` generator with language auto-detection. |
| [**dirwatch-cli**](https://github.com/DelmarMG91/dirwatch-cli) | Watch directories and re-run a command on change. |
| [**envfy**](https://github.com/DelmarMG91/envfy) | Validate and diff `.env` files against a schema. |
| [**waitport**](https://github.com/DelmarMG91/waitport) | Wait for TCP ports / HTTP services to become ready. |
| [**csvpeek**](https://github.com/DelmarMG91/csvpeek) | Read-only CSV exploration: `head`, `stats`, `select`, `filter`, `sort`. |
| [**httpstat-lite**](https://github.com/DelmarMG91/httpstat-lite) | HTTP request timing breakdown — dns, tcp, tls, ttfb, transfer. |

### Node.js

| Project | What it does |
| --- | --- |
| [**tocsmith**](https://github.com/DelmarMG91/tocsmith) | Markdown table-of-contents generator and CI validator (GitHub slugs, CJK-aware). |
| [**vbump**](https://github.com/DelmarMG91/vbump) | SemVer bump CLI and reusable GitHub Action. |

---

## Principles

- **Zero runtime dependencies** — standard library / built-ins only.
- **Tested** — every repo runs its suite in GitHub Actions on each push.
- **Boring on purpose** — one clear job per tool, documented, scriptable.

---

<sub>All projects are MIT licensed and tested on Windows, macOS and Linux.</sub>
