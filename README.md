# Offline Emoji + Science Symbol Searcher

A single, self-contained HTML file that lets you search and copy emoji **and**
scientific/math Unicode symbols (Greek letters, °C/°F, ∑ ∫ ∂ ∇, arrows, sub/superscripts…).

**Fully offline** — no server, no CDN, no downloads. Just open
[`index.html`](index.html) in any browser.

- 1,355 emoji + 147 science/math symbols, all baked into the page
- Live keyword search (type, or press `/` to focus)
- Click any glyph to copy it
- Quick-search preset buttons (✅ ⚠️ ⭐ 🚀 📊 📌 α)

## Data sources

- Emoji list & properties: [Unicode Character Database](https://www.unicode.org/ucd/)
  (`emoji-data.txt`) and Python's `unicodedata` — under the [Unicode License](https://www.unicode.org/license.txt).
- No third-party emoji-keyword library is bundled.

## Credits & license

This project is derived from **[Emoji finder](https://github.com/muan/emoji)**
by [Mu-An Chiou](https://github.com/muan), used and modified under the MIT License.
The original CSS, page markup, and search/copy logic live on in this project.

Distributed under the MIT License — see [`LICENSE`](LICENSE). The original copyright
notice is retained there as required.
