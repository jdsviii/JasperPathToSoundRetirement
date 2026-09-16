# Video attribution — PTSR hero video test

Royalty-free stock only. **Not** Netflix / Virgin River copyrighted footage.

License: [Pexels License](https://www.pexels.com/license/) — free to use; attribution appreciated but not required. Credited here for good practice.

## Primary clip (wired in `index-hero-video-test.html`)

| Field | Value |
|--------|--------|
| File | `forest-river-a.mp4` (+ poster `forest-river-a-poster.jpg`) |
| Source ID | Pexels video **34450104** |
| Title | Aerial View of Misty Forest River Landscape |
| Creator | OvO Films |
| Page URL | https://www.pexels.com/video/aerial-view-of-misty-forest-river-landscape-34450104/ |
| Download used | https://www.pexels.com/download/video/34450104/ |
| Why | Winding river through dense green misty hills — closest Virgin River / calm PNW aerial feel among the three candidates |

Compressed locally with ffmpeg (720p, H.264, no audio, CRF 28, ~18s loop-friendly trim) for web weight.

## Alternate clip (kept for A/B)

| Field | Value |
|--------|--------|
| File | `forest-river-b.mp4` |
| Source ID | Pexels video **14118682** |
| Title | Drone Footage of a River |
| Creator | Matthias Groeneveld |
| Page URL | https://www.pexels.com/video/drone-footage-of-a-river-14118682/ |
| Download used | https://www.pexels.com/download/video/14118682/ |
| Why | Mist-covered river + forest at soft dawn glow; excellent palette match (sage/teal). Slightly less “winding through hills” than 34450104 |

To A/B: change the `<source src="...">` (and poster) in `index-hero-video-test.html` to `forest-river-b.mp4`.

## Also downloaded (not kept as compressed deliverable)

| ID | Title | Creator | Page |
|----|--------|---------|------|
| 32672412 | Aerial View of Misty River and Lush Green Forest | Jonathan David | https://www.pexels.com/video/aerial-view-of-misty-river-and-lush-green-forest-32672412/ |

Raw 4K originals were discarded after compression to save space; re-download via the URLs above if needed.

## Logo / brand note

PTSR logo vibe (muted sage/teal, winding path/river, soft dawn, calm focus) guided clip choice and the dark teal/slate overlay — no Netflix assets were used.
