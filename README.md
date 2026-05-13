# Inverting the Bellman Equation: From *Q*-Values to World Models

Source for the project website of *Inverting the Bellman Equation: From
Q-Values to World Models* by Letcher, Fellows, Goldie, Richens, Foerster, and
Richardson.

The site is a single static `index.html` deployable via GitHub Pages.

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Updating placeholder links

The current build uses placeholder URLs that should be replaced once the arXiv
preprint and code repository are public:

| Placeholder | Location | Replace with |
| --- | --- | --- |
| `https://arxiv.org/abs/2511.00000` | `index.html` (Paper button + BibTeX) | real arXiv URL / eprint id |
| `https://www.alphaxiv.org/abs/2511.00000` | `index.html` (Discussion button) | real alphaXiv URL |
| `https://github.com/p-learning/p-learning` | `index.html` (Code button) | real code-repo URL |

`imgs/thumbnail.jpg` is a rendered first page of the paper used as the icon
for the Paper button; replace it (and `imgs/paper.pdf`, kept for reference) if
the paper changes.

The BibTeX block at the bottom of `index.html` is a placeholder arXiv entry
and should be updated with the real eprint id once available.

## Credits

Built from the
[Easy Academic Website Template](https://github.com/EasyAcademicWebsite/EasyAcademicWebsite.github.io),
itself derived from [Jon Barron's website](http://jonbarron.info/).
