# AI in Your Editor

A practical setup guide for developers who have been writing code for years but are new to AI
tooling: getting an agent into VS Code with DeepSeek, wiring it into GitHub, and using GitHub
gists well. Not a beginner's guide to programming.

Interactive setup checklist, hand-built SVG diagrams, and copyable commands throughout.

Live at **https://danhamilt.github.io/guides/**

## Contents

- `index.html` — the guide (single self-contained file, no dependencies)

## What it covers

1. The mental model — the agent loop, Plan/Act, context, tokens
2. Setup — VS Code, the Cline extension, a DeepSeek key, model choice and cost
3. Editors &amp; alternatives — Cursor's agent window with Cline (the free, DeepSeek route),
   VSCodium (same editor, no Microsoft telemetry), and where else Cline runs
4. Working with it — Plan first, `.clinerules`, controlling the blast radius
5. The GitHub integration — auth, PRs and issues in the editor, `gh`, Cline in Actions
6. GitHub gists — public vs secret, `gh gist`, gist vs repo vs Pages, rendering HTML
7. Prompting patterns
8. Gotchas — retired model names, `gh` hangs, MCP approval, secrets
9. Cheatsheet — models, CLI, `gh`, links

## Editing

Everything lives in `index.html`. Styles are inline in a `<style>` block, diagrams are inline
SVG, and the small amount of JavaScript handles copy buttons and the saved checklist.

Tooling details (model names, `gh` and `cline` flags, extension behaviour) reflect October 2026
and are the first thing to check if something stops matching reality.
