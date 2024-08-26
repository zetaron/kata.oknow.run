# kata.oknow.run

## Modify & Publish

```bash
gh repo clone zetaron/kata.oknow.run
code .
git add .
git commit -m ""
git push
```

## How it works

This repository uses GitHub Pages, which builds with `docs/` as it's root.
Under the covers GitHub Pages uses Jekyll by default, which also injects a bunch of stuff into the generated HTML output - sadly it seems the only way to get rid of that extra stuff is to go above and beyond in configuring Jekyll... which is not worth it for this project.