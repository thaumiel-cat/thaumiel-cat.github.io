# thaumiel-cat.github.io

My personal bio site. Plain HTML + CSS, so there's no build step and nothing to install.

## Files

| File | What it is |
|------|------------|
| `index.html` | All the content. Look for `<!-- EDIT: ... -->` comments. |
| `style.css`  | All the styling. Colours and fonts are variables at the top (`:root`). |
| `images/`    | Put your photo here (e.g. `images/me.jpg`). |
| `.nojekyll`  | Tells GitHub Pages to serve files as-is (don't delete). |

## Common edits

- **Add a project:** in `index.html`, copy one whole `<article class="card"> ... </article>` block and paste it below the others.
- **Add a skill:** add a `<li>Skill</li>` inside `<ul class="chips">`.
- **Add a photo:** save it as `images/me.jpg` and follow the comment above `<div class="avatar">`.
- **Change colours:** edit the variables at the top of `style.css`. The second block is for dark mode.

## Preview locally

Open `index.html` in a browser, or run a tiny server:

```bash
python3 -m http.server 8000
```

then visit http://localhost:8000.

## Publishing

GitHub Pages serves this repo at https://thaumiel-cat.github.io from the default branch.
Push to that branch (or set the source under **Settings → Pages**) and the site updates within a minute or so.
