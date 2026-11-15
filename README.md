# Sergei, Video Editor: portfolio site

Static one-page site. No build step.

## Publish on GitHub Pages
1. Create a repository and upload everything in this folder (keep the folder structure).
2. Repository **Settings → Pages → Build and deployment**: Source "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
3. After a minute the site is live at `https://<your-github-username>.github.io/<repository-name>/`.

## Add videos
Put files into `assets/video/` with exactly these names (lowercase):

| File | Where it shows |
|---|---|
| `hero.mp4` | Header showreel, silent loop |
| `reel-1.mp4`, `reel-2.mp4`, `reel-3.mp4` | Vertical 9:16 |
| `video-1.mp4`, `video-2.mp4` | Horizontal 16:9 |

A slot keeps its placeholder until its file exists. Optional cover: a `.jpg` with the same name (`reel-1.jpg`).

Limits: GitHub rejects files over 100 MB and the browser upload page takes up to 25 MB per file. Export H.264 MP4, 1080p, and aim for under 20 MB per clip (hero loop under 8 MB, no audio).

## Change the photo
Replace `assets/profile.jpg` (portrait, about 4:5).
