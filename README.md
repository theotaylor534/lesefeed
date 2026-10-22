# Lesefeed

Kant's *Kritik der reinen Vernunft* as a feed you scroll: one sentence at a
time, German first, the words that blocked you underneath, the English only
when you ask for it. 213 sittings of about fifteen minutes.

Everything is static — no build, no server code. Put these files on any HTTPS
host and open the URL on your phone.

**Install on iPhone:** open the URL in Safari, Share, *Add to Home Screen*.
It then runs full screen with its own icon, works offline, and keeps your
place, your bookmarks and your streak.

| file | what it is |
| --- | --- |
| `index.html` | the whole app |
| `book.json` | the reader, pre-parsed (183,591 German words, 4,506 cards) |
| `jszip.min.js` | lets you open any other EPUB from inside the app |
| `sw.js` | caches everything for offline use |
| `manifest.webmanifest` | makes it installable |

Ending the URL with `#s42` opens at sitting 42.
