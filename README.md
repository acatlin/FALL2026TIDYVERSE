# FALL2026TIDYVERSE

Student Tidyverse Vignettes — DATA 607, Fall 2026

- **TIDYVERSE CREATE (Assignment 1) due: 15-Nov-2026**
- **TIDYVERSE ExTEND (Assignment 2) due:06-Dec-2026**

## The two assignments

1. **Initial vignette.** Write a `.qmd` file that demonstrates one or more R / tidyverse functions with a worked example. Add it to this repo with a pull request, and fill in the **Initial** line of your own block in the roster below.
2. **Revision / addition.** Pick a *different* classmate's vignette that has already been merged, and improve it: add a second example, an enhancement, or a correction. Submit it as a pull request, and fill in the **Revision/Addition** line of your own block.

You are not a collaborator on this repo, so every change arrives as a pull request from your fork. The instructor merges pull requests; you do not merge your own.

## Rules that keep 45 people from colliding

- **Edit only your own block in this README.** Replace the `_TBD_` after the colon on your two lines. Do not add, delete, or reorder any other lines.
- **Sync your fork with this repo right before opening each pull request** (GitHub: *Sync fork* button on your fork, then `git pull` locally). Stale forks cause merge conflicts in this README.
- **One branch per assignment** in your fork, for example `initial-andre-t` and `revision-andre-t`. Do not work on your fork's `main`.
- **Vignettes live in `vignettes/`** and are named `firstname_lastinitial_topic.qmd`, for example `vignettes/andre_t_pivot_longer.qmd`. Lowercase, underscores, no spaces.
- **Commit only the `.qmd` file.** Do not commit rendered `.html` or `.pdf` (they are gitignored) and do not commit data files. Use a built-in R dataset or read a public URL inside the document.
- **Assignment 2 edits the classmate's existing file in place.** Do not create a new file or rename theirs. Choose a vignette that nobody has revised yet; check the roster before you start.
- **A revision pull request touches two things only:** the classmate's `.qmd` and the Revision/Addition line of *your* block.

## How to submit (both assignments)

1. **Fork** this repo on GitHub (once; reuse the same fork for both assignments).
2. **Clone** your fork: `git clone https://github.com/<your-username>/FALL2026TIDYVERSE.git`
3. **Sync** your fork with upstream (see above), then create a branch: `git checkout -b initial-andre-t`
4. **Add or edit** the vignette, and update your block in `README.md`.
5. **Commit** and **push** the branch: `git push -u origin initial-andre-t`
6. **Open a pull request** from your branch to `acatlin/FALL2026TIDYVERSE` `main`. Title it:
   - Assignment 1: `Initial: Andre T`
   - Assignment 2: `Revision: Andre T edits Benjamin B`
7. **Assignment 2 only:** once the pull request exists, copy its URL into your Revision/Addition line, commit, and push to the same branch. The open pull request picks up the new commit automatically.

## What a finished block looks like

```markdown
### Andre T
Initial Description and Link: `pivot_longer()` and `pivot_wider()` on the `billboard` dataset — [andre_t_pivot_longer.qmd](vignettes/andre_t_pivot_longer.qmd)

Revision/Addition Description and Link: Added a `separate_wider_delim()` example to Benjamin B's stringr vignette — [PR #37](https://github.com/acatlin/FALL2026TIDYVERSE/pull/37)
```

---

## Roster

### Anastasiia G
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Aniss S
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Arauca M
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Bikash B
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Cecilia D
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Chanice M
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Christine L
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Daanish R
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### David O
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Diana T
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Dillon L
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Dylan D
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Edgarlyn G
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Ellie W
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Enrique D
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Esra D
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Gamze B
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Jocelyn S
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Johnny M
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Jubilation B
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Kailot H
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Keenan R
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Kenny J
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Kevin V
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Lakeranie B
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Lionel D
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Marlon N
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Marvyn G
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Mohd S
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Mubin E
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Muhammad I
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Muntasir M
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Nicholas W
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Paul T
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Renan C
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Samantha M
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Shanice S
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Steven M
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Supriya P
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Tenzin T
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Ummay R
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Valery S
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### William A
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Yeimi P
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

### Zaina H
Initial Description and Link: _TBD_

Revision/Addition Description and Link: _TBD_

