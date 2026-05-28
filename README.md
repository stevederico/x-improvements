<div align="center">

# x-improvements

my ideas for redesigning x.com, one component at a time

</div>

<br />

## 🧩 Components

A growing set of redesigned X components. More to come.

| Component | What it is | Try it |
|-----------|------------|--------|
| **Web Composer** | A redesigned X compose box | [Live demo](https://stevederico.github.io/x-improvements/web-composer/composer-r1/index.html) |

<br />

## ✍️ Web Composer

A self-contained HTML/JS prototype of a redesigned X compose box.

**[▶ Try the live demo](https://stevederico.github.io/x-improvements/web-composer/composer-r1/index.html)**

<div align="center">
  <img src="screenshots/composer-demo.gif" alt="Web Composer demo" width="75%" />
</div>

**Improvements**

- **fullscreen mode** — floating close button in upper right, Cmd+. to toggle, persistent toolbar, Escape to exit
- **icons on focus** — toolbar stays hidden until you focus the editor
- **generate image** — custom Grok image-generation icon added to the toolbar
- **no dropdowns in writing area** — audience and "who can reply" (6 options) folded into a single toolbar popup with live label sync
- **no counter for premium** — character count inlined and shown based on Free/Premium (hard 280 limit in Free mode)
- **no bold for usernames + links** — bold/italic only applies to formattable text, not usernames or links

Lives in `web-composer/` — a frozen `baseline` plus the working `composer-r1` revision.

<br />

## 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| Vanilla JS + DOM | all interactivity and state |
| Tailwind via CDN + inline config | styling and custom X palette |
| External fonts from twimg | Chirp font family |

<br />

## 📄 License

MIT License

<br />

<div align="center">
Concept redesigns of X.com components.
</div>
