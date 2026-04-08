# Siddhartha

Interactive 3D book scene (Three.js): tropical table, coquí frog, tea steam, and ambient audio.

## Run locally

Serve this folder over HTTP (needed for `frog.glb`, textures, and audio), for example:

```bash
npx --yes serve .
```

Then open the URL shown in the terminal (the app lives at `/` as `index.html`). The old `book_scene.html` path redirects to `/`.

## Deploy (Vercel)

Import the GitHub repo, leave **Root Directory** empty, set **Framework Preset** to **Other** (static). The site entry is **`index.html`** at `/` — no build step.

## Assets (tracked in repo)

| File | Purpose |
|------|---------|
| `index.html` | Scene (main page) |
| `book_scene.html` | Optional redirect to `/` for old links |
| `frog.glb` | Coquí frog model |
| `coqui_sounds.mp4` | Ambient coquí audio (no spaces — works on GitHub Pages) |
| `siddhartha_cover.jpg` | Front cover art (outer face of the front board) |
| `book_cover_inner.jpg` | Parchment-style texture: inside of front board, back cover, and spine |
| Parchment | Generated in code (`parchmentBoardTex`) — no PNG required |

Optional: `Untitled-1.jpg` (reference only).
