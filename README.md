# octen-demo-assets

Public image assets for the Octen Ray-Ban Display demo.

These live here for one reason: the glasses render HUD images only from a
publicly reachable URL (the fetch happens through the Meta side, so data: URIs
and the phone's own loopback server are both dropped). Files are served over
raw.githubusercontent.com's CDN.

- `octen-mark.png` — Octen mark, transparent background and knocked-out face
  (matches how the mark is drawn on dark backgrounds on octen.ai).
- `octen-mark-whiteface.png` — same mark with a solid white face, for light backgrounds.
