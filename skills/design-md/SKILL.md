---
name: design-md
description: >-
  Curated library of 80+ real-world DESIGN.md design system specifications extracted from top tech companies and websites (Apple, Stripe, Linear, Vercel, Figma, Airbnb, OpenAI, GitHub, etc.).
  Use when designing pages, looking for visual style guidelines, copying design tokens, typography scales, color schemes, or requesting UI styled after a specific brand.
license: MIT
metadata:
  repository: https://github.com/VoltAgent/awesome-design-md
---

# DESIGN.md Library

This skill provides complete, tokenized `DESIGN.md` design system specifications from 80+ industry-leading products and websites.

## What is DESIGN.md?
`DESIGN.md` is a plain-text design system document (created for AI coding agents and design tools like Google Stitch) that defines:
- **Design Tokens**: Color palettes, semantic surfaces, border radii, shadows.
- **Typography**: Font families, weights, font size ladders, line heights, letter spacing.
- **Components & Layout**: Spacing systems, hero layouts, card styling, buttons, and interaction behaviors.
- **Visual Personality**: Guidelines on whitespace, contrast, imagery, and aesthetic tone.

## Available Brand Specifications
All brand specs are available under `references/<brand>/DESIGN.md`. Available brands include:
- **Tech & Tools**: `apple`, `linear`, `vercel`, `stripe`, `figma`, `cursor`, `github`, `openai`, `claude`, `framer`, `supabase`, `resend`, `hashicorp`, `datadog`, `postman`, `sentry`, `expo`, `raycast`
- **Consumer & Media**: `airbnb`, `spotify`, `netflix`, `notion`, `intercom`, `cal`, `aljazeera`, `nyt`, `medium`
- **Automotive & Luxury**: `bmw`, `bmw-m`, `bugatti`, `ferrari`, `porsche`
- **Crypto & Fintech**: `coinbase`, `binance`, `kraken`, `robinhood`, `revolut`
... and many more.

## How to Apply a Brand Style
1. Inspect the relevant brand spec in `references/<brand>/DESIGN.md`.
2. Extract the color tokens, typography scales, and component constraints.
3. Apply them directly to the components, Tailwind classes, or CSS variables in your project.
