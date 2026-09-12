# Birthday website

## File structure
```
index.html
style.css
script.js
images/
  photo1.jpg
  photo2.jpg
  photo3.jpg
  photo4.jpg
audio/
  birthday-song.mp3   <- add your own licensed/royalty-free track here
```

## About the music
The MP3 you uploaded turned out to be a ~15-minute "trending Hindi songs"
compilation rather than a single track, and it's commercial copyrighted
music — not something that should be re-hosted on a public GitHub Pages
site. The site is already fully wired up for background audio (autoplay
attempt, loop, tap-to-resume on mobile) — just drop a single track you
have the rights to use into `audio/birthday-song.mp3` and it will work
immediately, no code changes needed.

## About the card illustration
The reference video's final scene uses a specific illustrated teddy-bear
greeting card graphic (someone else's stock artwork). Rather than copy
that exact image, the "HAPPY BIRTHDAY" card here uses a small original
SVG illustration in a similar spirit.

## How to use
1. Replace the four images in `images/` with different photos any time
   (keep the same file names, or update the `src` paths in `index.html`).
2. Add your chosen audio file to `audio/birthday-song.mp3`.
3. Push the folder to a GitHub repo and enable GitHub Pages — all paths
   are relative, so it works from a subdirectory like
   `https://username.github.io/repo-name/`.

## Interaction
Press the space bar (or tap the cake / the hint text on mobile) to blow
out the candle — the cake and photos fade out and the birthday card
fades in, matching the reference video's two scenes.
