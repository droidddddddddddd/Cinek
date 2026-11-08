# CINEK Artist Universe — v0.1.0

A deployable starter for a Claudia.gallery-inspired artist universe: landing page, song catalogue, link directory, wiki, public JSON API, `llms.txt`, and read-only MCP-style JSON-RPC endpoint.

## Run locally
Requires Node.js 18+.
```bash
npm start
```
Open http://localhost:3000

## Deploy free on Render
1. Create a new GitHub repository (e.g. `cinek-artist-universe`).
2. Upload the contents of this folder to the repository root.
3. In Render, create a **New Web Service** connected to the repository.
4. Render should detect `render.yaml`; build command `npm install`, start command `npm start`.
5. Free instances may sleep when idle.

## Important content/rights notes
- The official Linktree `https://linktr.ee/noahcinek` is the current verified public hub. It lists TikTok, Instagram, YouTube, Apple Music, Spotify and Facebook.
- The direct destination URLs are not yet independently verified in this starter. Do not replace pending values with guessed URLs.
- Song names in the catalogue are based on public music catalogue sources; individual direct streaming/video URLs still need verification.
- This starter is not an official artist site and does not claim endorsement. Obtain explicit permission for commercial use of Cinek's name, likeness, music, artwork and for any artist-linked token before public launch.
- No token ticker, mint address, wallet, price chart or launch claim is included.

## Structure
- `public/index.html`, `styles.css`, `app.js`: website
- `public/wiki/`: creative wiki
- `public/agents/`: agent instructions
- `public/api/*.json`: machine-readable catalogue
- `public/llms.txt`, `public/llms-full.txt`: model-readable indexes
- `server.js`: static server and read-only MCP JSON-RPC endpoint

## Next content pass
Replace the placeholder archive with approved artist bio/canon and add verified direct URLs for each social profile, track, video, image, credit and making-of record. Keep source and verification notes in the JSON catalogue.
