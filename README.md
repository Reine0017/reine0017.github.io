# reine0017.github.io

Ran Fang's personal site: https://reine0017.github.io/

The page opens on a paper cover. Click "Turn the page" and it burns away. The embers settle into the stars of a night sky, the smoke thins into drifting clouds, and the links fade in.

- The burn is the WebGL effect from [the flammable page](https://github.com/Reine0017/flammable-page). Its burn maps, char texture and font are inlined in `index.html`, so the page is a single file.
- The sky is Canvas 2D: twinkling stars, two layers of tileable procedural cloud, and the embers handed over from the burn.
- If you've already burned the cover in this browser session, the page opens straight onto the sky. "Light it again" replays the burn.
- With reduced motion, or without WebGL, the cover simply fades out.
- `404.html` sends old links (the 2020 About and Projects pages) back home.

No build step and no libraries. To serve it locally, run `python3 -m http.server`.
