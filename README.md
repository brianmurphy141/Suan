# Suan

A soft, slowly pulsing tone for sleep. Drag anywhere to tune: up and down sets the tone (20 to 640 Hz), left and right sets the pulse (0.5 to 40 Hz). Tap for night mode. Sleep timer top right, time in the app bottom right.

One static page with no build step and no tracking. Settings are kept in the visitor's own browser. Works offline once opened, and installs to the home screen as an app.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole app |
| `manifest.webmanifest` | Name, colours and icons for installing to the home screen |
| `sw.js` | Offline support |
| `icons/`, `og.jpg` | App icons and the link preview image |
| `fonts/` | Cormorant Garamond and IBM Plex Mono, self hosted (SIL Open Font License, see `fonts/OFL.txt`) |

## Moving to your own domain

Add a file named `CNAME` containing the domain, point the domain's DNS at the host, and update the `canonical`, `og:url` and `og:image` addresses in `index.html`.

© 2026 Brian Murphy. All rights reserved.
