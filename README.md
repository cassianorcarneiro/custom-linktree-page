# Custom LinkTree Page

Minimal, fast, and responsive personal landing page designed for social media bios.  
Loads content dynamically from a JSON config file and runs entirely as a static site.

---

## Features

- Fully responsive (mobile + desktop)
- Dynamic content via JSON (no HTML edits needed)
- Built-in animations
- Automatic dark/light theme
- SVG icons (no external libraries)
- Google Analytics compatible
- Zero frameworks
- Works on GitHub Pages

---

## Demo Use Case

Ideal for:
- Instagram bio link
- Portfolio hub
- Personal card
- Creator link page

---

## File Structure

```
index.html
config.json
avatar.jpg
```

---

## Setup

1. Upload files to a GitHub repository
2. Go to **Settings → Pages**
3. Select branch `main`
4. Done

---

## Editing Content

Edit only:

```
config.json
```

Example:

```json
{
  "username":"@yourname",
  "button":{
    "text":"Anonymous Messages",
    "url":"https://yourlink.com"
  }
}
```

---

## Adding Analytics

Replace in index.html:

```
G-XXXXXXXXXX
```

with your Google Analytics measurement ID.

---

## Performance

Because this site:

- has no frameworks
- no fonts
- no libraries
- no trackers (unless you add)

It loads extremely fast (<1s typical).
