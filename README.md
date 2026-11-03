# The Pilgrim's Road

A classroom game for Global Studies 7: eleven stations from Bethlehem to the
Great Gate. Live at <https://andresmessina-sdg.github.io/the-pilgrims-road/>.

## Updating the game

If `index.html` is replaced with a new version from its artifact, run:

```bash
python3 tools/localize-fonts.py
```

It swaps the Google Fonts link for `fonts/fonts.css`, downloading any font the
new page needs into `fonts/`. Players' browsers then ask no other site for the
fonts. Commit `index.html` and anything new in `fonts/` together.
