# which_slasher

A static, spoiler-light film guide site for the three big slasher franchises:
Friday the 13th, Halloween, and A Nightmare on Elm Street.

Each franchise page lists its films with year, a one-line "tag" hook, and a
short summary that avoids major spoilers. No build step, no dependencies —
plain HTML/CSS in a dark terminal style.

## Files

- `index.html` — landing page linking to the three franchises
- `friday.html` — Friday the 13th (12 films)
- `halloween.html` — Halloween (13 films)
- `nightmare.html` — A Nightmare on Elm Street (9 films)

## Running locally

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploying

Push to `main`; the site is static and can be served from any static host
(e.g. GitHub Pages).

Fan project, not affiliated with any studio.