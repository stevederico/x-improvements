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
| **Notifications** | The notifications screen | [Live demo](https://stevederico.github.io/x-improvements/notifications/r1/index.html) |
| **Account Messages** | Every email X sent you, in the app | [Live demo](https://stevederico.github.io/x-improvements/account-messages/r1/index.html) |

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

## 🛎️ Notifications

A self-contained HTML/JS prototype of the X notifications screen (All / Verified / Mentions tabs).

**[▶ Try the live demo](https://stevederico.github.io/x-improvements/notifications/r1/index.html)**

Lives in `notifications/` — a frozen `baseline/` (current X from console dump) plus the working `r1/` revision with tabs, mark-read, simulate new, etc.

<br />

## 📬 Account Messages

A new screen under Security and account access that lists every message X has sent to the account. If an email isn't listed here, it isn't from X.

**[▶ Try the live demo](https://stevederico.github.io/x-improvements/account-messages/r1/index.html)**

<div align="center">
  <img src="screenshots/account-messages-demo.gif" alt="Account Messages demo" width="40%" />
</div>

**Improvements**

- **phishing check** — compare any email in your inbox against the real list in the app
- **security and other tabs** — logins, connected apps and password changes kept apart from everything else
- **verified sender** — each message shows it was sent by X with a Mark Certificate
- **one tap from settings** — sits next to Security, Apps and sessions, and Connected accounts

Lives in `account-messages/r1/`. Add `?s=1`, `?s=2` or `?s=3` to the URL to hold one screen.

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
