# arnaldosepulveda.com

Personal technical site for Arnaldo Sepulveda — Senior AI Engineer building governed AI
infrastructure for regulated industries. Static, deployed via Cloudflare Pages.

## Purpose

An employer-readable technical dossier and entity-consolidation target. Positions the work
(Keystone: a governed AI platform), records lessons and background, and keeps writing
first-class. Person schema (JSON-LD) links this site to LinkedIn, GitHub, and getkeystone.ai.
It is a visual **sibling** of getkeystone.ai (shared paper/ink/slate/teal palette and
Fraunces/Inter/JetBrains Mono type), with a more personal, editorial voice.

## Structure

- `index.html` — home: hero, Current work, What I've learned, Writing, Background, Proof, Contact
- `writing/index.html` — writing index: published posts + an in-progress notebook roadmap
- `fonts/` — self-hosted variable WOFF2 (Fraunces, Inter, JetBrains Mono), latin subset, SIL OFL 1.1
- `og.png` — 1200×630 social card (regenerate from the template noted in the site history)

## Stack

Plain HTML and CSS. No framework, no build step. Fonts are self-hosted (no external
dependency); minimal inline JS.

## Deployment

Cloudflare Pages, auto-deploy from `main`.

## Edits

Edit the HTML directly. Push to `main`. Cloudflare Pages redeploys in under a minute.
