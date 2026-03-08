# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a **GitHub profile README repository** (saachinnnn/saachinnnn). It renders as the profile page at github.com/saachinnnn. There is no application code, build system, or test suite.

## Repository Contents

- `README.md` — The profile page content (HTML/Markdown with a Minecraft/retro gaming theme, color `#dd2d4a` as primary accent)
- `heartbar.svg` — Pixel-art SVG with CSS animation (10 hearts: 3 full, 1 half pulsing, 6 empty). Scale 2.2x for visibility.
- `pixel-divider.svg` — RPG-style pixel-art section divider with center sword motif and diamond accents
- `.github/workflows/snake.yml` — GitHub Actions workflow that generates contribution snake SVGs every 12 hours using `Platane/snk/svg-only@v3`, pushes output to the `output` branch

## Design System

- **Color palette:** `#dd2d4a` (crimson accent), `#000000` (background), `#c9d1d9` (text), `#555555` (muted), `#FFFF55` (Minecraft yellow splash)
- **Font:** `Press Start 2P` (pixel/retro) for all typing SVGs
- **Theme:** Retro pixel RPG / Minecraft / Terminal hybrid. Dark, moody, cinematic. NO emojis.
- **Badges:** `flat-square` style shields.io for AI/ML tools, `skillicons.dev` for languages/infra
- **Dividers:** `pixel-divider.svg` between every major section, with animated Minecraft-quote typing SVGs

## README Sections (12 total)

1. Waving header (capsule-render)
2. Player name (typing SVG)
3. Animated heartbar (heartbar.svg)
4. Minecraft splash text rotator (typing SVG, yellow)
5. Player stats (pixel-profile, streak, top-langs, trophies)
6. About me (JS code block)
7. Tech stack / Inventory (skillicons + shields.io badges)
8. Adventure log (ASCII art book and quill)
9. Contribution snake (from output branch)
10. Multiplayer mode / Connect (for-the-badge links)
11. Footer (typing SVG farewell + profile views + capsule-render)
12. Section divider animations (grey Minecraft quotes between every section)

## Key Details

- Snake SVGs served from `output` branch (`raw.githubusercontent.com/saachinnnn/saachinnnn/output/...`)
- Custom SVGs (`heartbar.svg`, `pixel-divider.svg`) served from `main` branch raw URL
- Minecraft splash texts are REAL game splash texts only — no custom ones
- External services: `capsule-render`, `readme-typing-svg`, `pixel-profile`, `streak-stats`, `github-readme-stats`, `github-profile-trophy`, `github-readme-activity-graph`, `skillicons`, `komarev/ghpvc`

## Working with This Repo

- No build, lint, or test commands exist
- Changes are purely to Markdown, SVG, or workflow YAML
- Preview README changes by pushing to `main` and viewing the GitHub profile
