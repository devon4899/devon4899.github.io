# Devon Cheng Portfolio

Live at **https://devon4899.github.io/**. Static HTML, CSS, and JavaScript hosted by GitHub Pages from `main`.

## Projects

- [Hirenao](https://devon4899.github.io/projects/hirenao/) — job search, résumé tools, and interview practice.
- [FRPG / Liftling](https://devon4899.github.io/projects/frpg/) — native workout tracking and a growing pixel companion. [GitHub](https://github.com/devon4899/FRPG).
- [Tap Track](https://devon4899.github.io/projects/tap-track/) — native calorie and nutrient logging with weekly/monthly history. [GitHub](https://github.com/devon4899/TapTrack).
- [Last Tide](https://devon4899.github.io/projects/last-tide/) — cooperative Roblox treasure-hauling prototype. [GitHub](https://github.com/devon4899/Last-Tide).

## Screenshot provenance

FRPG / Liftling and Tap Track images were captured from their current working iOS builds on November 12, 2026, in an iPhone simulator. All profile, workout, and nutrition values in these captures are synthetic demonstration data. Last Tide images are actual Roblox Studio captures of the local project, not concept art. Project pages identify release status and the distinction between public showcases and separately maintained development source.

The earlier Hirenao screenshots remain unchanged. Personal résumé download links and the hosted PDF have been removed from the site. Original FRPG WebP images are retained for existing inbound image links; current pages use the new PNG captures.

## Local preview

```sh
python3 -m http.server 8765
```

Open `http://localhost:8765/`. The site has no build dependencies. Screenshot links open a keyboard-accessible native dialog with previous/next controls and full-size viewing. Mobile galleries scroll horizontally.

Before publishing, check local links and images, run `node --check assets/site.js`, inspect desktop and phone layouts, and test the screenshot dialog. After pushing, verify GitHub Pages deployment and the live project pages.
