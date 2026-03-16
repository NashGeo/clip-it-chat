# Clip it, Chat

A DVR for your ears. Say the phrase, save the moment.

## How it works
Always-listening rolling audio buffer. When you say your wake phrase ("Hey Chat, Clip it"), it saves the last 10 seconds + the next 10 seconds as a named clip.

## Files
- `index.html` — the entire app (single file)
- `manifest.json` — PWA manifest (name, icons, colors)
- `sw.js` — service worker (offline support)
- `icons/` — app icons (192px and 512px)

## Editing
The whole app lives in `index.html`. That's the only file you'll ever need to edit.

After any change:
```bash
git add . && git commit -m "your message" && git push
```
Netlify auto-deploys in ~10 seconds.

## Tiers
- **Basic** — 5 clips/day, fixed 10s+10s window, one folder
- **Pro** — unlimited, adjustable up to 30s+30s, folders/tags/custom phrase
