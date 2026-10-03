# Krishna's Secret Files

A playful personal brand site for Krishna Agarwal, built as one self-contained `index.html` plus an `img/` folder.

## Sections
1. **Krishna 26** – a retro desktop with icons, draggable windows, a Start menu, Paint, the K.amp music player, a screensaver and tray notifications. A "Hang with K" sign swings in on load.
2. **Hang with K** – conversation cards from [@hang.withk](https://www.instagram.com/hang.withk/) hanging on a rope; pull one to flip it.
3. **Row 3** – a black-and-white cinema audience of the people in Krishna's life.
4. **Letters** – a pile of papers with eyes peeking out; click to open a letter, or write an anonymous one.
5. **Unsaid** – a Notepad window with a hanging phone; pick up to chat.
6. **Krishna Counter** – a card machine that prints what Krishna does plus a personalised receipt of your visit.

Little Krishna (a small 3D character) runs along the bottom of the page. There are six hidden secrets.

## Run locally
Open `index.html` through any static server, e.g. `python3 -m http.server`, then visit http://localhost:8000.

## Notes
- External scripts: three.js r128 from cdnjs. Fonts: Google Fonts.
- Anonymous letters use the claude.ai artifact database when hosted there; on other hosts the letter form falls back to "copy and email".
- Placeholder content to replace: Hang with K answers, Row 3 people, letters, chat replies, K.amp playlist.
