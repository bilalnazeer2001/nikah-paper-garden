# Nikah invitation: Paper Garden
**Rahma & Hasanul Banna**, Monday 19 October 2026

Pastel cut paper. You fly through paper arches, then pop-up flowers, a pop-up date and a paper flower blooming.

**Live page:** https://bilalnazeer2001.github.io/nikah-paper-garden/

## Change the details (works from a phone too)
1. Open **index.html** in this repo and tap the **pencil (Edit)** button.
2. Search for **EDIT THE DETAILS HERE**. Everything on the page reads from that block:
   - `time: ''`: the time in 24-hour form, e.g. `'11:30'`
   - `name` and `address` inside `venue`
   - `maps`: a Google Maps link (shows an "Open in Maps" button)
   - `whatsapp`: number with country code, no + or spaces, e.g. `'919876543210'` (shows a "Confirm on WhatsApp" button)
   - `brideFirst: false` shows Hasanul Banna's name first
3. Change only what is between the quote marks and keep the commas.
4. Tap **Commit changes**. The live page updates in about a minute. Refresh it to see the change.

## Personal links
Add `?to=` and a guest's name to the end of the live link, e.g. `.../nikah-paper-garden/?to=Uncle%20Rahim` (`%20` is a space). The guest's name then appears on the invitation.

## How it moves
One swipe, one mouse-wheel scroll or one arrow key goes to one page, and that page then plays its animation by itself. Phones get a lighter version so it stays smooth. Add `?pages=0` to the link for the older style, where animations follow the scroll.

## Please double-check
- **Arabic:** the Bismillah and Surah Ar-Rum 30:21. Have someone confirm them before sending.
- **Time zone:** the countdown assumes India time (`tz: '+05:30'`).
