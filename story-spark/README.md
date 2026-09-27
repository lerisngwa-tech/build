# ✨ Story Spark

A slot machine for story ideas. It spins three reels (**Hero**, **Place** and **Problem**) to make a prompt like:

> A shy dragon in a library at midnight who lost their echo.

## Run it

It's a single HTML file with no build step or dependencies. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server -d story-spark 8000
# then visit http://localhost:8000
```

## How to use

- **Spin** (or press `Space`) for a new idea.
- **Lock** a reel (or press `1` / `2` / `3`) to keep that part and re-roll the others.
- **Save** (or press `S`) keeps a favourite in your browser (localStorage).
- **Copy** puts the sentence on your clipboard.

## Make it yours

Edit the word lists in the `REELS` array near the top of the `<script>` in `index.html`. Each reel is a `label` and an `items` list. You can add a 4th reel (for example "Twist" or "Sidekick") and the layout will pick it up.
