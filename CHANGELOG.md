# Wolf Pack Group Flyer: change log

Everything changed on the site, newest first, so we can look back before adding something and avoid doing it twice.

- **Live site (reps use this):** https://hartfordwolfpack.github.io/wolfpack-group-flyer/
- **Personal copy (not for reps):** https://ethanmorren-hky.github.io/wolfpack-group-flyer/ (it updates on every push too)
- **How to check which version is live:** the version number and date at the bottom of the page.

## How changes get made

1. Make the change in `index.html` (the whole app is that one file).
2. Try it in the local preview.
3. Push **only after Ethan approves**. One push updates both sites.
4. Confirm the work site shows the new version number at the bottom.

Every few releases, review the whole page for clutter and ease of use from the view of a rep who did not build it.

---

## Versions

### 1.14 · Nov 3, 2026
| Change | Impact for reps |
|---|---|
| **Default rep:** "This is me" checkbox in the Sales rep card | New flyers start with that rep's name, email and phone. The checklist always shows that rep's groups, even on a flyer made for a coworker. Saved per browser, so set it once on each computer. |
| **Drag to select** in manual edit | Drag a box across empty flyer space (or Shift-drag anywhere) to select everything fully inside. Delete removes them all; drag or arrow keys move them together; Undo brings them back. |
| **Clean-up:** game list | Shows upcoming games only (plus this flyer's game if it has been played). |
| **Clean-up:** Sales rep card | Shows the dropdown, a one-line email and phone summary, and "This is me". Name, email and phone boxes appear only for a custom rep or after **Edit details**. |
| **Clean-up:** wording | "Save setup file" and "Open setup file" became "Save this flyer as a file" and "Open a flyer file". |
| **Clean-up:** Logos card | Removed the duplicate "+" upload tile; the "Added logos" row only appears once a logo has been added. |
| **Clean-up:** welcome guide | The six flyer steps stay up front; manual edit tips fold under "Changing the layout". |

### 1.13 · Nov 3, 2026 (shipped inside the 1.14 push)
| Change | Impact for reps |
|---|---|
| **Removed items vanish** | Removed items leave no dashed outline. They are listed under **Removed** in the Manual edit card, and one click puts each back. |
| **Rotate anything** | Select an item, then type an angle or use ⟲/⟳ 90°. Carries into PNG, JPEG, PDF and PowerPoint. |
| **Text boxes with a width** | "Add text" makes a 400-wide box. The side handle sets the width and words wrap inside it; the corner handle still sets the size. |
| **Nothing runs off the flyer** | Text boxes wrap before the edge. Template text that grows too big wraps onto another line at the page edge and pushes its lower lines down. One word too long for its line shrinks to fit. |

### 1.12 · Nov 2, 2026
| Change | Impact for reps |
|---|---|
| **Two points of contact** (Manual edit checkbox, off by default) | The bottom becomes: "For more information & performance related questions:" with an example name and email, a red divider, then "For ticket related questions contact:" with the rep's name, email and phone. Double-click the example to type over it. The Sales rep card is not affected. |

### 1.11 · Nov 2, 2026 (includes 1.10.1)
| Change | Impact for reps |
|---|---|
| **Manual edits fill the cards** | Typing over the group name, price, FEVO link, deadline, rep name or email/phone on the flyer fills the matching card. If the typed wording matches the template exactly, the flyer follows the card again. Game date and time still come only from the game picker. |
| **Yellow "partly done" steps** | A step with several parts (group + price; top + promo text; contact + email) shows yellow with a dash until all are filled, then green. Only typing on the flyer counts; cards still turn green with Next. |
| **1.10.1:** toolbar placement | The text toolbar sits above (or below) the text being edited instead of covering it. |

### 1.10 · Nov 2, 2026
| Change | Impact for reps |
|---|---|
| **Aa button** | Switches the selected words (or all of them) between UPPER, lower and Title case, keeping formatting. |
| **Size box on all text** | Template text can be resized by typing a point size, not only added text. |
| **Theme night box editable on the flyer** | Double-click its top or bottom part. Saves back into its card. Per-word italic, super/subscript and white/black are hidden there because the card cannot store them. Size stays 8–30 pt. `{GROUP}` keeps following the group name, in the case it was written. |
| **Fix:** editor position | The double-click editor had sat slightly left of the text since the flyer was centred in 1.8. |

### 1.9 · Nov 1, 2026
| Change | Impact for reps |
|---|---|
| **Group flyer checklist** (top-bar dropdown) | Per-rep list of groups to make flyers for: stage bar (not started, in progress, saved), order-deadline alerts within 7 days, game as m/d. Opening a task saves the current flyer first, unless it is the same group. Finished flyers get a green ✓ in Recent flyers. |
| **Guided tour** (welcome guide or footer) | 14 stops, 8 seconds each, pauses on any interaction. Runs on a practice flyer; nothing is saved or downloaded. Clicking elsewhere jumps there and offers a review of skipped stops. |
| Wording | "Sponsor" became "another organization". |

### 1.8.1 · Oct 30, 2026
- File name centred under the flyer.

### 1.8 · Oct 29, 2026
| Change | Impact for reps |
|---|---|
| Delete any item, **Undo** button and ⌘/Ctrl+Z | Removing things is safe to try. |
| Cut / copy / paste (⌘/Ctrl X, C, V) | Duplicate logos and text. |
| Alignment guides while dragging | Includes mirror alignment across the centre. |
| Added logos land beside the QR code | They no longer cover it. |
| Logos card keeps added logos as tiles | A removed logo can be added again with one click. |
| Small polish | Rounder corners, button press, centred preview, phone margins. |

### 1.7 · Oct 28, 2026
- Theme night box can be removed in manual edit (with a warning in its card).

### 1.6 · Oct 28, 2026
| Change | Impact for reps |
|---|---|
| Left rail of numbered, collapsible step cards with Next/Done | Turn green with a connector line when finished. |
| Help text moved into **?** tooltips | Cleaner cards. |
| Recent flyers filtered to the selected rep | |
| Top Wolf Pack logo movable or removable in manual edit | Uses the exact template artwork. |
| **Remove background** for uploaded logos | |
| QR test run starts closed | |
| "This game" card in a right-hand column on wide screens | |
| Light/dark switch, dark by default | |

### 1.0–1.5 · Oct 27, 2026 (before this log)
Original single-page builder replacing the 36 game files, then the Buyer View, FEVO view and QR updates (git commits "Add Buyer View", "FEVO View Update", "FEVO Update v1.4", "QR Update v1.5").

---

## Decided against (don't redo)

- **Visual restyle (Oct 29):** a different dark-mode colour scheme, sentence-case headings and font changes were tried and rejected. Keep the current colours, capitals and fonts. Only small touches (corners, hover, press, spacing) were kept.
- **OmniRoute:** set up, then removed. Not used.
- **Moving "QR test run" into the FEVO card:** suggested in the Nov 3 review, held back as a small win.

## Known limits

- Everything a rep saves (recent flyers, checklist, default rep, uploaded logos) lives in **that browser only**. Use "Save this flyer as a file" to move a flyer between computers.
- Resizing a **rotated** item can shift it slightly.
- Font choice is only on added text boxes, not template text.
- Copy/paste and rotation work on one item at a time, not on a drag-selected group.
- Clearing text from a step does not remove its green check.
- The deadline defaults to the Friday about two weeks before the game, so for games under two weeks out it shows as already passed.
