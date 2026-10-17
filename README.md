# $BARBIE — retro meme site

One file: `index.html`. No build step, no external files. Upload it to GitHub Pages, Netlify, Vercel or any host, or just double-click it.

## Add your links
Open `index.html`, search for `var CONFIG` and fill in:

```js
tokenCA:  '',  // contract address (shows in the click-to-copy box)
buyUrl:   '',  // e.g. pump.fun coin page
chartUrl: '',  // e.g. dexscreener page
xUrl:     ''   // your X profile
```
Empty values show a "coming soon!!" popup instead of a broken link.

Guestbook, chat name and visitor counter are saved in each visitor's own browser only.
