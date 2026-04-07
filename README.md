# Harvey Prospect Intel

A single-page sales intelligence tool built for Harvey AI's go-to-market team. Type any law firm or in-house legal team name and get back a structured research brief in seconds — covering firm overview, recent deals and hires, AI/tech signals, Harvey product fit, and three ready-to-use AE talking points. All research is pulled live from the web via Claude's web search tool, so every brief reflects what's actually happening at the firm right now, not stale CRM notes.

## Why I built this

At Draper Associates I spent a significant chunk of my time as a VC scout doing exactly this kind of research — manually pulling together firm overviews, recent news, and pitch angles for 30+ companies at a time before partner calls. It was tedious, inconsistent, and the output lived in a dozen different docs. I built Harvey Prospect Intel to collapse that process into a single search. Harvey's sales team faces the same problem at scale: they need fast, specific, opinionated intel on hundreds of AmLaw firms. This tool gives them a structured starting point in under 30 seconds.

## How to run

1. Open `index.html` in any modern browser (or deploy to GitHub Pages — no build step needed).
2. Paste your Anthropic API key in the top-right field. It saves to `localStorage` so you only do this once.
3. Type a firm name and hit Enter. The brief renders in place.

> **Note:** The app calls the Anthropic API directly from the browser. Your API key never leaves your machine — it's stored only in `localStorage` and sent only to `api.anthropic.com`.
