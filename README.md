# Momo 24 website

Bilingual English and Simplified Chinese product, support, and privacy pages for **Momo 24: Math Chain Puzzle / 萌萌24：算式连锁消除**.

## Pages

- `index.html` — bilingual product page with actual gameplay screenshots.
- `support.html` and `zh-Hans/support.html` — English and Chinese support.
- `privacy.html` and `zh-Hans/privacy.html` — English and Chinese privacy policy.

The `assets/` folder contains actual App Store screenshots captured from the game. `app_icon.png` is the app icon. The product page switches languages in the browser and uses no external libraries or tracking scripts.

## Preview locally

From the repository root, run:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages

To host these pages, enable GitHub Pages for the `main` branch and repository root in the repository’s **Settings → Pages**. The resulting project site URL is normally `https://chenkaitech.github.io/Momo24/`.
