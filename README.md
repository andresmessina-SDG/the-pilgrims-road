# The Pilgrim's Road

A classroom game for Global Studies 7: eleven stations from Bethlehem to the
Great Gate. Live at <https://andresmessina-sdg.github.io/the-pilgrims-road/>.

## Updating the game

If `index.html` is replaced with a new version from its artifact, run:

```bash
python3 tools/localize.py
```

It swaps the Google Fonts link for `fonts/fonts.css`, downloading any font the
new page needs into `fonts/`, and copies any image the page loads from another
site into `images/`. Players' browsers then load the game entirely from this
site. Commit `index.html` with anything new in `fonts/` and `images/`.
