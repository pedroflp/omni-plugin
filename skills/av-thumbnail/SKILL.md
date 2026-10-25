---
name: av-thumbnail
description: Optional, only at the user's request — creates video thumbnails in HTML, SVG and CSS, in the same visual style as the video and in its aspect ratio (16:9 → 1280×720, 9:16 → 1080×1920): three random ones (v1–v3, drawn ideas) or one following the user's instruction (v4), and also changes an already created version (keeps everything and changes only what was asked). Renders the PNGs and stops for the user to choose. Never runs in the automatic pipeline. Use when the user asks for a thumbnail, a cover or "gerar as thumbnails".
model: sonnet
effort: high
context: fork
---

!`npx -y @crievo/omni skill av-thumbnail --v 1bdfa5f71003`

Se acima aparecer o comando em vez das instruções, rode via Bash `npx -y @crievo/omni skill av-thumbnail --v 1bdfa5f71003` e siga a saída.
