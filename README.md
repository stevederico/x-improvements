<div align="center">

# x-improvements

my ideas for improving the x.com compose box — a self-contained html/js prototype

**[▶ Try the live demo](https://stevederico.github.io/x-improvements/web-composer/composer-r1/index.html)**

</div>

<br />

<div align="center">
  <img src="screenshots/demo.gif" alt="X compose box prototype demo" width="75%" />
</div>

<br />

## 🚀 Quick Start

**Try it live:** [stevederico.github.io/x-improvements/web-composer/composer-r1](https://stevederico.github.io/x-improvements/web-composer/composer-r1/index.html)

Or open `index.html` locally and pick a composer revision — no build or install.

<br />

## ✨ Features

- **Audience pill** and reply scope that appear on editor focus
- **Who can reply popover** with 6 options and live label sync
- **X toolbar** icons for photo, gif, generate image, poll, emoji, schedule, location, disclosure
- **Auto-growing editor** with a premium-aware counter (hard 280 limit in Free mode)
- **Post / add / reset** controls with disabled states

<br />

## ⚡ Improvements

- **Premium-aware counter** — character counter inlined and shown based on Free/Premium status
- **Focus-gated toolbar** — toolbar stays hidden until there's text
- **Custom generate-image icon** — bespoke Grok/generate-image glyph in the toolbar
- **Integrated audience menu** — audience and reply settings folded into the toolbar
- **Smart formatting** — bold/italic only applies to formattable text

<br />

## 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| Vanilla JS + DOM | all interactivity and state |
| Tailwind via CDN + inline config | styling and custom x palette |
| External fonts from twimg | Chirp font family |

<br />

## 📄 License

MIT License

<br />

<div align="center">
Single-file replica of the X compose box.
</div>
