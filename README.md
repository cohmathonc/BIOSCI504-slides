# BIOSCI504 slides

Quarto source for BIOSCI 504 course presentations. Package code, datasets and
exercise templates live in the separate
[`cohmathonc/BIOSCI504`](https://github.com/cohmathonc/BIOSCI504) repository.

## Preview

```sh
quarto preview
```

## Render

```sh
quarto render
```

Rendered files are written to `_site/`. The presentations are
`_site/lecture-2.html` and `_site/lecture-3.html`.

## Source material

Lecture 2 adapts *Introduction to R and RStudio* from Data Carpentry's
[*Data Analysis and Visualization in R for
Ecologists*](https://datacarpentry.github.io/R-ecology-lesson/instructor/introduction-r-rstudio.html),
licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
Changes were made for the BIOSCI 504 course context. This adaptation does not
imply endorsement by The Carpentries.

Lecture 3 adapts teaching moves from the current Data Carpentry R Ecology and
Spreadsheet Ecology lessons, also licensed under CC BY 4.0. Its executable
table examples use `BIOSCI504` package commit
`3730f8b813668f317689ac56fabb299c9a1b072e`. The lecture shows data structure
and inspection mechanics but deliberately withholds the completed exercise
comparison.

The `gander` workflow stills are derived from a screencast embedded in the
official [`gander` documentation](https://simonpcouch.github.io/gander/) and
credited to Simon Couch. The GitHub user attachment has no separate licence
metadata. The surrounding source repository is MIT licensed; its notice is
retained in [`assets/gander-LICENSE.md`](assets/gander-LICENSE.md).

The `chattr` Viewer screenshot is reproduced from the official
[`chattr` documentation](https://mlverse.github.io/chattr/) under the project's
MIT licence, retained in
[`assets/chattr-LICENSE.md`](assets/chattr-LICENSE.md).
