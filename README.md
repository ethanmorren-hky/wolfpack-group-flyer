# Wolf Pack Group Flyer

One page that replaces the 36 per-game PowerPoint flyers. The flyer layout is locked to the official template (same positions, sizes, colors, Taurunum W00 Tall + Azo Sans). You only fill in the details.

## Put it on GitHub Pages (about 5 minutes)

1. Create a new repository on GitHub, e.g. `wolfpack-group-flyer`.
2. Upload `index.html` and the `logos` folder (drag them onto **Add file → Upload files**), then **Commit**.
3. Go to **Settings → Pages**. Under **Build and deployment**, pick **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
4. After a minute the site is live at `https://<your-username>.github.io/wolfpack-group-flyer/`.

> Note: Pages sites on free GitHub plans are public, and this page embeds the team fonts. If that matters, use a private repo on a GitHub plan that supports private Pages.

## Team settings (edit `index.html` on GitHub)

Open `index.html`, click the pencil icon, and look for **TEAM SETTINGS** near the top of the script.

**Sales reps.** Add one line per rep:

```js
const REPS = [
  { name: "Jane Smith", email: "jane.smith@oakviewgroup.com", phone: "860-555-0101" },
  { name: "John Doe",   email: "john.doe@oakviewgroup.com",   phone: "860-555-0102" },
];
```

**Schedule.** The 36-game 2026-27 home schedule is already in, the same as the Line Chart. Edit `SCHEDULE` if a game moves.

## Opponent logos

All 31 AHL opponent logos are built into the page, so every game fills in the opponent automatically; nobody can replace it from the tool. The same files are in the `logos` folder (cut from the league logo sheet: blank tile space removed, logos otherwise unchanged); replacing a file there with the same name changes that team's logo for everyone. **Add another logo** (Logos card) puts an extra logo, like a youth organization's, on top of the flyer without touching the opponent.

## What the tool does

- **Game** menu: opens on the next home game; date, puck drop and opponent logo fill in automatically.
- **Group name and ticket price**: the group name also fills "back to …" in the theme night box.
- **FEVO link**: prints where the template says "INSERT FEVO LINK". A QR code is generated (no internet needed) and placed below the link; it can also be saved as PNG or SVG.
- **Theme night box**: text with size, bold, italic, underline, alignment and color controls. Text shrinks if it outgrows the box.
- **Order deadline**: defaults to the Friday about two weeks before the game (11/14 game → Fri 10/30, as on the template); ±1 day / ±1 week buttons.
- **Sales rep**: fills the contact name, email and phone.
- **Download**: PNG, JPEG, PowerPoint (editable) or PDF, all 8.5 × 11 at print quality (300 DPI). Files are named like `26-27 HWP261114 - Group Name - 11.14.26.pdf`.
- **Print**: the button next to Download prints the flyer straight to a printer on letter paper (set margins to "None" if the print window asks).
- **Reset**: next to Print; starts a fresh flyer from the template (asks you to click twice). Keeps the selected rep and never touches saved flyers.
- **Recent flyers**: every download and print is filed in a folder for the rep on the flyer. Each rep picks their folder once and it stays open on their computer. The small × deletes a flyer after a Delete / Keep confirmation. Flyers are kept in each person's own browser.
- **Manual edit**: a checkbox that unlocks the flyer. Drag items to move them, use the corner handle to resize and a logo's side handles to reshape it, and nudge with the arrow keys. Double-click any text to type right on the flyer; a toolbar at the top gives bold, italic, underline, superscript, subscript and color (plus font, size and alignment for added text). Add new text or extra logos (any AHL team or an uploaded image). Unchecking locks changes in place; only "Original text", "Put this item back" or "Reset all to template" undo them.

The PDF and PowerPoint downloads load a small helper library from jsDelivr (unpkg as a backup) the first time they're used, so those need an internet connection. PNG, JPEG, Print and QR codes work offline.
