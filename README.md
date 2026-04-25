# 🔗 Custom LinkTree Page

> Minimal, fast, and responsive personal landing page — perfect for social media bios.

A static personal landing page that loads its content dynamically from a JSON config file. Zero frameworks, zero build steps, zero external dependencies — just upload to GitHub Pages and you're live.

<p align="center">
  <img alt="Stack" src="https://img.shields.io/badge/Stack-HTML%20%2B%20JSON-blue?style=for-the-badge">
  <img alt="License" src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge">
  <img alt="Status" src="https://img.shields.io/badge/Performance-%3C1s%20Load-success?style=for-the-badge">
</p>

---

## 📦 Features

- 📱 **Fully responsive** — looks great on mobile and desktop
- ⚙️ **Dynamic content via JSON** — no HTML edits needed to update links
- 🎨 **Built-in animations** — subtle motion without external libraries
- 🌓 **Automatic dark/light theme** — adapts to the visitor's system preference
- 🎯 **SVG icons** — crisp at any size, no icon fonts
- 📈 **Google Analytics compatible** — drop in your measurement ID and you're tracked
- 🪶 **Zero frameworks** — no React, no Vue, no build step
- 🌐 **Works on GitHub Pages** — free hosting, custom domain optional

---

## 🎯 Demo use cases

Ideal for:

- Instagram bio link
- Portfolio hub
- Personal business card
- Creator link page
- Lightweight personal homepage

---

## 📋 Prerequisites

- A **GitHub account** (free)
- A photo to use as your avatar
- ~5 minutes

That's it. No Node, no npm, no build tools.

---

## 🚀 Quick start

### 1. Get the files

Clone or download this repository:

```bash
git clone https://github.com/cassianorcarneiro/custom-linktree-page.git
cd custom-linktree-page
```

### 2. Customize your content

Open `config.json` and edit the values to match your profile:

```json
{
  "username": "@yourname",
  "button": {
    "text": "Anonymous Messages",
    "url": "https://yourlink.com"
  }
}
```

Replace `avatar.jpg` with your own photo (keep the same filename).

### 3. (Optional) Add Google Analytics

In `index.html`, find the placeholder:

```
G-XXXXXXXXXX
```

Replace it with your Google Analytics measurement ID.

### 4. Deploy to GitHub Pages

1. Push the repository to GitHub
2. Go to **Settings → Pages**
3. Select branch `main` (or `master`)
4. Click **Save**
5. Wait ~30 seconds — your page is live at `https://<username>.github.io/<repo-name>/`

---

## 📁 Project structure

```
custom-linktree-page/
├── index.html      # Static page with vanilla JS that reads config.json
├── config.json     # All editable content (username, links, etc.)
├── avatar.jpg      # Your profile picture
└── README.md
```

---

## ⚡ Performance

Because this site has:

- ❌ No frameworks
- ❌ No external fonts
- ❌ No third-party libraries
- ❌ No trackers (unless you opt in)

...it loads **in under a second** on a normal connection — and works even on slow mobile networks.

---

## 🛣️ Roadmap

- [ ] Multiple buttons/links via JSON array
- [ ] Optional QR code generator for the page URL
- [ ] Custom theme colors via JSON
- [ ] Multi-language support driven from `config.json`
- [ ] Vanity URL templates ready for popular use cases (creator, dev, freelancer)

---

## 📜 License

MIT — see `LICENSE` file.

## 👤 Author

**Cassiano Ribeiro Carneiro** — [@cassianorcarneiro](https://github.com/cassianorcarneiro)

---

### 🤖 AI Assistance Disclosure

The codebase architecture, organizational structure, and stylistic formatting of this repository were refactored and optimized leveraging [Claude](https://www.anthropic.com/claude) by Anthropic. All core business logic and intellectual property remain the work of the repository authors and are governed by the project's license.

---

> *A bio link page that loads faster than the apps it links to.*
