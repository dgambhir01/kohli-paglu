# Kohli Paglu

A living tribute page - a scrolling chronicle of Virat Kohli's career, from the West Delhi academy through the 2026 IPL and his 15,000th ODI run, built for every Kohli Paglu out there.

No build step: `index.html` plus an `Images/` folder of local photos. Open it directly, or serve it via GitHub Pages.

## Media

- **Local photos** (`Images/`) are personal/found images supplied directly, referenced by relative path. If you add more, keep filenames free of spaces so paths stay simple.
- **A few photos are hotlinked** from Wikimedia Commons (Creative Commons licensed) - credit and license link are inline in each figure's caption. Don't remove those captions; that's the attribution the license requires.
- **Videos are embedded YouTube iframes**, mostly third-party reuploads rather than official broadcasts. They can go dark if a rights holder pulls them - the surrounding text never depends on the clip to make sense.
- Requires an internet connection to preview properly (hotlinked photos and embedded video won't load offline).

## Updating

The page is one static file plus an image folder, so it's meant to be extended as Kohli's career continues - new chapters, updated stats, the eventual full retirement post. Edit the chapter sections, the honours board list, and the "Runs, by format" chart values directly in `index.html`.

## Local preview

Just open `index.html` in a browser, or serve the folder:

```
npx serve .
```
