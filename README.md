# upath

**Status: scaffold only. No source code exists yet.**

`upath` is a monorepo scaffold for a planned library described as "a universal object graph, queryable by path, and designed to allow setting boundaries." The description appears in both `Cargo.toml` (`[workspace.package]`) and `package.json`.

## What exists

| File | Content |
|---|---|
| `Cargo.toml` | Virtual Cargo workspace, `resolver = "3"`, `members = []` |
| `package.json` | npm workspace (`@portal-solutions/upath`), `workspaces: []`, dev dep on `zshy ^0.7.0` |
| `crates/_` | Placeholder file to allow git to track an empty directory |
| `packages/_` | Placeholder file to allow git to track an empty directory |

There are no Rust crates, no TypeScript/JavaScript packages, no source files, no tests, and no build scripts. The Cargo workspace will not build (`cargo` reports: "The manifest is virtual, and the workspace has no members").

## Intended structure

The directory layout anticipates:

- `crates/` — Rust crates (none yet)
- `packages/` — Node.js/TypeScript packages (none yet)

## Repository

- GitHub: `git@github.com:portal-co/upath.git`
- Single commit: "Initial scaffold"
- Part of the `portal-solutions` / `portal-co` organization
