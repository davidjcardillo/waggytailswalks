# 🐾 Waggy Tails Walks

Website and marketing assets for **Waggy Tails Walks** — a neighborhood dog walking business run by Norah and Kelsey.

**Live site:** [waggytailswalks.com](https://waggytailswalks.com)

---

## Project structure

```
waggytailswalks/
├── index.html                  ← The live website (waggytailswalks.com)
├── CNAME                       ← DO NOT TOUCH — connects repo to the domain
├── README.md                   ← This file
├── flyer/
│   ├── waggy-tails-flyer.html  ← Printable flyer (open in browser to print)
│   └── waggy-tails-flyer.pdf   ← Print-ready PDF version of the flyer
└── assets/
    └── waggy-tails-qr-code.png ← QR code image linking to waggytailswalks.com
```

---

## How the website works

The website is a single HTML file (`index.html`). When changes are pushed to the `main` branch on GitHub, the live site at [waggytailswalks.com](https://waggytailswalks.com) updates automatically via **GitHub Pages** — usually within 1–2 minutes.

### Booking form
Customer booking requests are handled by **Formspree** (form ID: `mredbqwz`). When a customer submits the form, both parents receive an email notification with the customer's details. Log in at [formspree.io](https://formspree.io) to manage submissions and notification settings.

---

## How to make changes

### First time setup (do this once per computer)

1. Install [Git](https://git-scm.com) and [VS Code](https://code.visualstudio.com)
2. Clone the repo:
   ```bash
   git clone https://github.com/davidjcardillo/waggytailswalks.git
   cd waggytailswalks
   ```
3. Open in VS Code:
   ```bash
   code .
   ```

### Making and publishing a change

```bash
# 1. Always pull the latest changes first
git pull

# 2. Make your edits in VS Code

# 3. Stage all changed files
git add .

# 4. Commit with a short description of what you changed
git commit -m "describe what you changed here"

# 5. Push to GitHub — site updates live within ~2 minutes
git push
```

### Example commit messages
- `git commit -m "update pricing on website and flyer"`
- `git commit -m "add Calendly booking link"`
- `git commit -m "update dog logo on flyer"`

---

## Using Claude Code for changes

Both parents can use [Claude Code](https://claude.ai/code) in the terminal to make changes without writing code manually. From inside the `waggytailswalks` folder just run:

```bash
claude
```

Then describe what you want, for example:
- *"Update the pricing section to add a new walk type"*
- *"Change the contact email in the footer"*
- *"Regenerate the flyer PDF with the latest changes"*

Claude Code will edit the files directly. Then commit and push as normal.

---

## Collaborating as two parents

- **Always run `git pull` before starting any work** — this ensures you have the latest version
- **Never both edit the same file at the same time** — coordinate with each other first
- If you see a merge conflict, reach out so we can sort it together
- The `CNAME` file must never be deleted or modified — it connects the repo to waggytailswalks.com

---

## Key accounts and logins

| Service | Purpose | URL |
|---|---|---|
| GitHub | Code hosting & deployment | github.com/davidjcardillo/waggytailswalks |
| GitHub Pages | Live website hosting (free) | Configured under repo Settings → Pages |
| Namecheap | Domain registration (waggytailswalks.com) | namecheap.com |
| Formspree | Booking form submissions | formspree.io (form ID: mredbqwz) |

---

*Built with ❤️ for Norah & Kelsey — future business moguls 🐾*
