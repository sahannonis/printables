# Free printables page — sahannonis.github.io/printables

Every Kindle edition links here, each to its own section (for example `#nine-lights`).

## 1. Put the page online (about 2 minutes)
1. On GitHub, create a new **public** repository named exactly `printables`.
2. Upload `index.html` and the `covers` folder from this zip.
3. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)` → Save.
4. In a minute the page is live at https://sahannonis.github.io/printables/

## 2. Set up Kit to email the PDFs (free plan, up to 10,000 subscribers)
For each of the eight books:
1. In Kit: Grow → Landing Pages & Forms → New → Form → Inline. Name it after the book.
2. In the form's settings, turn on **Incentive email** and upload that book's
   "- Free Printables.pdf" as the download. Kit sends it after the reader confirms their email.
3. Copy the form's ID (the number in its address), or the `action="…"` address from "Embed using HTML".
4. Paste it into the matching line of `KIT_FORMS` near the bottom of `index.html`, then re-upload `index.html`.

Until a form ID is filled in, that book's button shows "Coming very soon", so the page is safe to publish first.
Tip: add a tag per book in Kit (e.g. "nine-lights") so you know which book each reader came from.
