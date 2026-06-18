# ⛪ Church Decathlon — Live Scoreboard App

A lightweight, mobile-friendly scoreboard for the **First Annual Church Decathlon** — a Father's Day community field day featuring 10 events, 3 competing teams, and one epic grand finale.

> **Live event:** Sunday, June 21, 2026 · 1:00–4:00 PM · Fox Hill Park

---

## What It Does

This app is a single-page scoreboard designed to be pulled up on any phone or tablet during the event. One volunteer at the scoring table can track all 10 events in real time, and the leaderboard updates instantly for everyone watching.

**Features:**
- Live point totals for Red Team, Blue Team, and Green Team
- One-tap scoring for 1st, 2nd, and 3rd place after each event
- Automatic double-point calculation for the Final Challenge Relay (Event 10)
- Checkmark system to mark events as complete
- Progress bar showing how many of 10 events are done
- Trophy/medal rankings that update in real time
- Winner banner that appears automatically when all 10 events are marked complete
- Scores save to local storage — closing the tab won't lose your data
- Works on any device, any browser — no app download needed
- Dark mode supported

---

## The 10 Events

| # | Event | Points |
|---|-------|--------|
| 01 | Potato Sack Race | 1st = 3 · 2nd = 2 · 3rd = 1 |
| 02 | Three-Legged Race | 1st = 3 · 2nd = 2 · 3rd = 1 |
| 03 | Egg & Spoon Race | 1st = 3 · 2nd = 2 · 3rd = 1 |
| 04 | Tug of War | 1st = 3 · 2nd = 2 · 3rd = 1 |
| 05 | Hula Hoop Contest | 1st = 3 · 2nd = 2 · 3rd = 1 |
| 06 | Wheelbarrow Race | 1st = 3 · 2nd = 2 · 3rd = 1 |
| 07 | Bean Bag Toss | 1st = 3 · 2nd = 2 · 3rd = 1 |
| 08 | Water Balloon Toss | 1st = 3 · 2nd = 2 · 3rd = 1 |
| 09 | Paper Airplane Contest | 1st = 3 · 2nd = 2 · 3rd = 1 |
| 10 | ⭐ Final Challenge Relay | **1st = 6 · 2nd = 4 · 3rd = 2 (double points!)** |

**Maximum possible score: 33 points per team** (27 from Events 1–9 + 6 from Event 10)

---

## How to Use It

**During the event:**
1. Open the app on a phone or tablet at the scoring table
2. After each event finishes, tap the point button (6/4/2 for Event 10, 3/2/1 for all others) next to the winning team
3. Tap the **✓ checkmark** to mark the event complete — it grays out so you know where you are
4. Totals and rankings update automatically at the top
5. After Event 10 is marked complete, the winner banner appears

**To fix a mistake:** Tap the highlighted button again to deselect it, then tap the correct one.

**To start over:** Tap **Reset all** in the Live Scores header (you'll be asked to confirm).

---

## Hosting on GitHub Pages

This app is a single `index.html` file — no build tools, no dependencies, no server required.

### First-time setup

1. [Create a free GitHub account](https://github.com) if you don't have one
2. Click **+** → **New repository**
3. Name it `church-decathlon` (or anything you like)
4. Set visibility to **Public**
5. Check **"Add a README file"**
6. Click **Create repository**
7. Click **Add file → Upload files**
8. Upload `index.html` (and this `README.md` if you'd like)
9. Click **Commit changes**
10. Go to **Settings → Pages**
11. Under Branch, select **main** and folder **/ (root)**
12. Click **Save**

Your live URL will appear within ~60 seconds:
```
https://yourusername.github.io/church-decathlon
```

Share that link with your team before the event — it works on any device with no setup.

### Updating the app

To push an update (new `index.html`):
1. Open your repository on GitHub
2. Click on `index.html`
3. Click the **pencil (edit) icon**, or click **Upload files** to replace it
4. Commit the change — GitHub Pages updates automatically within a minute

---

## Scoring Summary

| Place | Events 1–9 | Event 10 (Final Challenge) |
|-------|-----------|---------------------------|
| 1st | 3 pts | 6 pts |
| 2nd | 2 pts | 4 pts |
| 3rd | 1 pt | 2 pts |

The Final Challenge Relay is worth double because it's the grand finale — a full-team relay course that combines all 9 previous events into one epic run. Every team member competes, the whole crowd watches, and the points reflect the stakes.

---

## Technical Notes

- **No frameworks.** Pure HTML, CSS, and vanilla JavaScript — loads instantly on any connection.
- **No backend.** All score data is stored in the browser's `localStorage`. Scores persist across page refreshes and tab closes on the same device.
- **No installation.** Works in any modern browser (Chrome, Safari, Firefox, Edge).
- **Offline capable.** Once the page has loaded, it works without an internet connection.
- **Dark mode.** Automatically follows the device's system preference via `prefers-color-scheme`.

> **Note:** Because scores are stored in `localStorage`, they are device-specific. If you switch devices mid-event, you'll need to re-enter scores on the new device. For a shared experience, keep one designated scoring device for the whole event.

---

## Event Day Contacts

| Role | Name | Contact |
|------|------|---------|
| Event Organizer | [Name] | [Email / Phone] |
| Scoring Table | [Name] | [Email / Phone] |
| Head Captain | [Name] | [Email / Phone] |

---

*Built for the Fox Hill Park Father's Day community field day. Go team!* 🏆
