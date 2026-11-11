# mujur-media

Social media content for **Mujur Development** (Instagram: [@mujurdevelopment](https://instagram.com/mujurdevelopment)).

This repository is the public image host for Instagram posts. Windsor.ai publishes each post from the image's public link here.

> ⚠️ **This repository is public.** Anyone on the internet can see every file. Only add content that is ready to be posted. Never add price lists, contracts, legal documents, customer data or internal plans.

## Folder structure

```
mujur-media/
├── posts/              One folder per Instagram post (images + caption)
│   └── _template/      Copy this folder to start a new post
├── calendar/           Content calendar (posting schedule)
├── brand/              Logo, colours, fonts, voice and tone
│   └── logo/
├── projects/           Approved photos and renders per development project
│   ├── babura-park-residence/
│   └── emerald-residence/
└── captions/           Reusable hashtag sets and caption snippets
```

## How to add a new post

1. Copy `posts/_template/` and rename it `YYYY-MM-DD_short-title`
   (example: `posts/2026-11-15_babura-park-intro/`).
2. Add the image(s), named `01.jpg`, `02.jpg` … in the order they should appear.
3. Fill in `caption.md` (caption, hashtags, status).
4. Add the post to `calendar/content-calendar.md`.

## Image rules (Instagram)

| Type | Size (pixels) | Format |
|---|---|---|
| Feed post, portrait (recommended) | 1080 × 1350 (4:5) | JPEG (.jpg) |
| Feed post, square | 1080 × 1080 (1:1) | JPEG (.jpg) |
| Story / Reel cover | 1080 × 1920 (9:16) | JPEG (.jpg) |
| Reel video | 1080 × 1920 (9:16) | MP4 |

- Use **JPEG** for images: automatic publishing does not accept PNG (Portable Network Graphics).
- Keep each image **under 8 MB** (megabytes). GitHub rejects any file over 100 MB.
- File and folder names: lowercase, no spaces, use `-` between words.

## Public image link

Every file here has a public link in this format:

```
https://raw.githubusercontent.com/jaxxsoon/mujur-media/main/<path-to-file>
```

Example: `https://raw.githubusercontent.com/jaxxsoon/mujur-media/main/posts/2026-11-15_babura-park-intro/01.jpg`

## Where big files go

Raw photos, drone footage and editing files stay in Google Drive or Dropbox. Only the final, ready-to-post version goes in this repository.
