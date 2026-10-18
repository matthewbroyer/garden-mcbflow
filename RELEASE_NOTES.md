# Release notes · Garden (garden.mcbflow.com)

Newest first. One entry per release, in plain words a user would understand.

## 1.7 · 2026-10-17
- Garden opens on Home for everyone, and the logo takes you there. On phones the bottom bar is Home · Beds · + · Schedule · More: the + adds a task, the same as "+ Add a task" on Home. Harvests moved into More.
- More is one short list, the same in every mcbflow.com app: Settings, Harvests, Records, Crop guide, Help and What's new. Privacy, Terms and Credits are in the page footer and in Settings → About.
- What's new opens the same dialog from the footer, Settings → About and More. The separate Release notes page is gone (old #notes links open the dialog).
- Sample data loads only when you pick "Start with sample data" in the welcome (or Plans… → Add sample data). A new garden starts empty. If you have the sample, Home shows a note with Remove sample data, and Undo right after. Sample entries are tagged "Sample". Gardens that already have the sample keep it until they remove it.
- Deleting a harvest entry, a crop or a plan happens right away, with Undo in the message instead of an "Are you sure?" box.
- Search (the Search button, / or Ctrl+K) uses the same search box as the other apps: your plantings, harvests and records first, then plans, crops, pages, actions and help.
- Clearer Help: Getting started in five steps, then questions by topic, ending with Install the app and Your data & privacy.
- Settings starts with "Changes save as you make them.", the Install section reads the same as in the other apps, and the column is no longer centered.
- The Home banner reads "Your garden" with the date and your zone. Empty lists say what goes there, with a button to add one. Outline icons replace emoji on buttons and lists (crop emoji on your beds stay).
- Export file names follow one pattern, for example garden-backup-2026-10-17.zip and garden-harvests-2026-10-17.csv (the rolling backup file is still garden-backup.json). Exporting an empty list still saves a file. Older backup files still import.
- Seedlings started indoors show in a light green on the map and charts instead of lavender.
- Your plans, crops, harvests, records, photos and settings are unchanged.

## 1.6 · 2026-10-17
- Clear all data now asks you to type DELETE, the same in every mcbflow.com app. It offers to save a backup first, and still deletes your synced copy too when you're signed in. The button on the Privacy page is now called Clear all data… too.
- Account pop-up spacing fixed.
- The Home banner art is no longer cut off on phones, and the banner has the same height as in the other apps. Its second line now shows your zone (and the "this plan is for …" note) before the plan names, so a long plan name can't push them out of view.
- Very long plan, crop and note names wrap instead of pushing the page sideways on phones.

## 1.5 · 2026-10-16
- New Settings page (gear in the sidebar; first item under More on phones): theme, sync, your zone and frost dates, plans, plot size, auto-size big crops, weather alerts, the getting-started checklist, backups, Install and About in one place. Install and About moved here from Help.
- New account button in the top bar. Signed in, it shows your profile picture (or initial) with a sync dot. New "Keep me signed in on this device" switch: turn it off on a shared computer and you're signed out when the browser closes.
- Profile picture and screen name: pick them once with Edit profile and every mcbflow.com app shows the same ones.
- Home greets you ("Good morning, …") with your screen name when you're signed in.
- Today is now called Home, with a house icon, and Settings has a gear icon. Old #today links still open it.
- Same welcome screen as the other apps: Welcome, pick a look, your USDA zone (same frost-date logic), then your garden or the sample garden, with Sign in and Import a backup on the last step.
- Clearer Data menu: every item has a one-line description, in the same order as the other apps. Export All comes as JSON, CSV (every planting in every plan) or ZIP (backup, a spreadsheet per record type and your photos). Single spreadsheets, CSV import and copy-paste backup text are still there. Clear all data is at the bottom.
- Journal and problem photos open in the built-in viewer (step through them, zoom, download) instead of a separate dialog. Photos from another device show a "not on this device" note.
- Quieter backup reminders when you're signed in and syncing: the backup label reads "Synced", never turns amber, and the Data menu says "Synced to your account".
- Even top bar: every control is the same height, and the name reads "Garden ∙ mcbflow.com" (just "Garden" on phones). On laptops under 1280 px wide, the plan picker, Plans… and zone sit under the ≡ button so everything fits.
- Charts (season timeline, crop tracker bar, spending bars) show exact dates or amounts when you hover, tap or use the arrow keys.
- One standard footer on every page (What's new, Privacy, Terms, More free apps).

## 1.4 · 2026-10-15
- New: optional sync across devices. Data → Sync signs in with a free mcbflow.com account; plans, crops, harvests, tasks, seeds, journal, problems, expenses and settings then match on every device you sign in on.
- Photos stay on the device where you added them and show as "Not on this device" elsewhere. Export All (ZIP) and Import still move them.
- Not signed in: nothing changes. Deleting all data warns when you're signed in, since it also clears synced data.

## 1.3 · 2026-10-14
- Moved to garden.mcbflow.com. Data saved at the old address doesn't carry over: export a backup there and import it here.
- Storage names simplified.

## 1.2 · 2026-10-14
- On computers, the search box, backup status and logo spacing now look exactly like the other mb apps: same size, same "Search…" text and the same "/" shortcut.
- The top bar now matches the other mb apps. On phones it shows Search, Data and the light/dark switch right in the bar, plus a ≡ button that opens your plan picker, Plans… and zone.
- A small dot on Data means a backup is due.
- On computers everything sits in one row: Search, plan, Plans…, zone, backup status, Data and the light/dark switch.
- On phones the top bar is a steady 56 px tall, so the Select / Undo tools under it are no longer squeezed.
- Your plans, plantings, harvests and backups are unchanged.

## 1.1 · 2026-10-14
- New logo (a seedling over raised beds), redrawn in the same style as the other mb apps; app icon, tab icon, share image and pages all updated.
- About card at the bottom of Settings: version, release date, links and copyright in one place.
- Installing from matthewbroyer.com: the hub's Install button opens the app with a short install prompt.
- New "page not found" page that matches the app and links back to it.
- Garden has no Settings page, so the About card sits at the bottom of Help, and the Install card moved from the top of Help down next to it. The Help answer about installing now says so.
- Version numbers restart at 1.x with the suite's "Official Web App" label; earlier releases were numbered v1–v8.

## 2026-10-13 · v8: new look, sidebar and share cards

- **New logo and app icon:** a leaf over a soil row. The installed app is now called **Garden**.
- **Sidebar navigation:** sections sit in a sidebar on the left. Tablets get a compact icon rail, and phones keep the bottom bar, with Records, Crop guide and Help under **More**.
- **Logo, name and subtitle take you home** to your start page (Today once you have your own plan and zone, otherwise Beds). Browser tabs read "Garden | Beds", "Garden | Harvests" and so on.
- **Share cards:** *Share season* on the Harvests tab and *Share plan* on the Beds tab make a square image on your device to post or send. Only your own entries count (not the sample garden), and the plan name stays off the card unless you switch it on.
- **Install card** at the top of Help. It only appears when your browser can actually install the app, and shows Add to Home Screen steps on iPhone and iPad.
- **Fresher look:** a light green wash, a garden banner on Today, gradient primary buttons and progress bars. Layout, data and features are unchanged.
- **Fixed:** the Log a harvest form ran off the edge of narrow phone screens.
- **Accessibility:** the Beds side panels and wide tables can now be reached and scrolled with the keyboard.

Your garden data, backups and settings carry over as they are. Backups made with v7 restore in v8.

## 2026-10-13 · v7

Today tab, records, rotation, companions, weather alerts, photos and offline use. See the in-app Release notes page for the full list.
