# FALL2026TIDYVERSE

Student Tidyverse Vignettes — DATA 607, Fall 2026

- **TIDYVERSE CREATE (Assignment 1) due: 15-Nov-2026**
- **TIDYVERSE EXTEND (Assignment 2) due: 06-Dec-2026**

## The two assignments

1.  **Initial vignette (TIDYVERSE CREATE).** Write a `.qmd` file that demonstrates one or more R / tidyverse functions with a worked example. Add it to this repo with a pull request, and fill in the **Initial** line of your own block in the roster below.
2.  **Revision / addition (TIDYVERSE EXTEND).** Pick a *different* classmate's vignette that has already been merged, and improve it: add a second example, an enhancement, or a correction. Submit it as a pull request, and fill in the **Revision/Addition** line of your own block.

You are not a collaborator on this repo, so every change arrives as a pull request from your fork. The instructor merges pull requests; you do not merge your own.

## Rules that keep 45 people from colliding

- **Edit only your own block in this README.** Replace the `_TBD_` after the colon on your two lines. Do not add, delete, or reorder any other lines.
- **Sync your fork with this repo right before opening each pull request** (GitHub: *Sync fork* button on your fork, then `git pull` locally). Stale forks cause merge conflicts in this README.
- **Vignettes live in `vignettes/`** and are named `firstname_lastinitial_topic.qmd`, for example `vignettes/andre_t_pivot_longer.qmd`. Lowercase, underscores, no spaces.
- **Commit only the `.qmd` file.** Do not commit rendered `.html` or `.pdf` (they are gitignored) and do not commit data files. Use a built-in R dataset or read a public URL inside the document.
- **Assignment 2 edits the classmate's existing file in place.** Do not create a new file or rename theirs. Choose a vignette that nobody has revised yet; check the roster before you start.
- **A revision pull request touches two things only:** the classmate's `.qmd` and the Revision/Addition line of *your* block.

## How to submit (both assignments)

1.  **Fork** this repo on GitHub (once; reuse the same fork for both assignments).
2.  **Clone** your fork: `git clone https://github.com/<your-username>/FALL2026TIDYVERSE.git`
3.  **Sync** your fork with upstream (see above) and `git pull` so your local copy matches.
4.  **Add or edit** the vignette, and update your block in `README.md`.
5.  **Commit** and **push** to your fork: `git push`
6.  **Open a pull request** from your fork to `acatlin/FALL2026TIDYVERSE` `main`. Title it:
    - Assignment 1: `Initial: Andre T`
    - Assignment 2: `Revision: Andre T edits Benjamin B`
7.  **Assignment 2 only:** once the pull request exists, copy its URL into your Revision/Addition line, commit, and push again. The open pull request picks up the new commit automatically.

## What a finished block looks like

``` markdown
### Andre T
Initial Description and Link: `pivot_longer()` and `pivot_wider()` on the `billboard` dataset — [andre_t_pivot_longer.qmd](vignettes/andre_t_pivot_longer.qmd)

Revision/Addition Description and Link: Added a `separate_wider_delim()` example to Benjamin B's stringr vignette — [PR #37](https://github.com/acatlin/FALL2026TIDYVERSE/pull/37)
```

------------------------------------------------------------------------

## Roster

### Anastasiia G

Initial Description and Link: Demonstrates dplyr, tidyr, and ggplot2 using international tourism data — [anastasiia_g_tourism.qmd](vignettes/anastasiia_g_tourism.qmd)

Revision/Addition Description and Link: *TBD*

### Andy C

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Aniss S

Initial Description and Link: lubridate date handling (`make_date()`, `ymd()`, `wday()`, `floor_date()`, `days_in_month()`, `weeks()`, `%m+%`) on FiveThirtyEight's daily US births data, ending with the Friday the 13th effect — [aniss_s_lubridate_births.qmd](vignettes/aniss_s_lubridate_births.qmd)

Revision/Addition Description and Link: *TBD*

### Arauca M

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Bikash B

Initial Description and Link: Initial Description and Link: Explores income, poverty, and commuting patterns across New York City using dplyr and ggplot2 — [bikash_b_income_poverty_NYC.qmd](vignettes/bikash_b_income_poverty_NYC.qmd)

Revision/Addition Description and Link: *TBD*

### Cecilia D

Initial Description and Link: dplyr to explore USDA maple syrup yield data — [cecilia_d_maple_syrup.qmd](vignettes/cecilia_d_maple_syrup.qmd)

Revision/Addition Description and Link: *TBD*

### Chanice M

Initial Description and Link: Exploring diamond prices using dplyr and ggplot2, including grouping, summarization, and visualization by cut and carat size — [chanice_m_diamond_prices.qmd](vignettes/chanice_m_diamond_prices.qmd)

Revision/Addition Description and Link: *TBD*

### Christine L

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Daanish R

Initial Description and Link: Exploring College Majors: [daanish_r_collegemajors.qmd](https://github.com/daanishrasheed/FALL2026TIDYVERSE/blob/main/vignettes/daanish_r_collegemajors.qmd){.uri}

Revision/Addition Description and Link: *TBD*

### David O

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Diana T

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Dillon L

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Dylan D

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Edgarlyn G

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Ellie W

Initial Description and Link: Exploring Electricity Mix Data with Tidyverse [ellie_w_tidyr_energy_mix.qmd](vignettes/ellie_w_tidyr_energy_mix.qmd)

Revision/Addition Description and Link: *TBD*

### Enrique D

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Esra D

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Gamze B

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Jocelyn S

Initial Description and Link: Data Science: Into the Tidyverse. An exploration of the tidyverse using Marvel Comic Data. [Jocelyn_S_IntoTheTidyverse.qmd](vignettes/Jocelyn_S_IntoTheTidyverse.qmd)

Revision/Addition Description and Link: *TBD*

### Johnny M

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Jubilation B

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Kailot H

Initial Description and Link: `case_when()`, `summarize()`, `fct_reorder()`, and `ggplot2` on NY Knicks shot-chart data via `hoopR` — [kailot_h_knicks_shots.qmd](vignettes/kailot_h_knicks_shots.qmd)

Revision/Addition Description and Link: *TBD*

### Keenan R

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Kenny J

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Kevin V

Initial Description and Link: `fct_lump_n()`, `fct_collapse()`, and other forcats functions on the NYC Dog Licensing dataset — [kevin_v_forcats_nyc_dogs.qmd](vignettes/kevin_v_forcats_nyc_dogs.qmd)

Revision/Addition Description and Link: *TBD*

### Lakeranie B

Initial Description and Link: This project explores flight delays at JFK, LaGuardia, and Newark airports during 2013 using the nycflights13 dataset. I used Tidyverse packages such as dplyr and ggplot2 to clean, organize, and analyze flight records. The analysis compares departure delay rates by month and airline, using summary tables and visualizations to identify patterns.

[View My NYC Flight Delays Vignette](vignettes/Lakeranie_b_flight_delays.qmd)

Revision/Addition Description and Link: *TBD*

### Lionel D

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Marlon N

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Marvyn G

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Mohd S

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Mubin E

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Muhammad I

Initial Description and Link: This vignette demonstrates how to use the **Tidyverse** to import, inspect, transform, summarize, and visualize an observational dataset. The dataset contains information about online news articles and the number of times each article was shared. (Muhammad_I_online_news_popularity_analysis_using_tidyverse.qmd)[vignettes/Muhammad_I_online_news_popularity_analysis_using_tidyverse.qmd]

Revision/Addition Description and Link: *TBD*

### Muntasir M

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Nicholas W

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Paul T

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Renan C

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Samantha M

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Shanice S

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Steven M

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Supriya P

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Tenzin T

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Ummay R

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Valery S

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### William A

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Yeimi P

Initial Description and Link: *TBD*

Revision/Addition Description and Link: *TBD*

### Zaina H

Initial Description and Link: Using a Netflix movies and TV shows dataset to demonstrate how TidyVerse functions can be used to clean and organize data, focused on separating genres into individual rows, counting the most common categories, and visualizing the results. [zaina_h_netflixgenres.qmd](vignettes/zaina_h_netflixgenres.qmd)

Revision/Addition Description and Link: *TBD*
