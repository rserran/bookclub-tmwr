<<<<<<< Updated upstream
# R4DS Tidy Modeling with R Book Club

Welcome to the R4DS Tidy Modeling with R Book Club!

We are working together to read [Tidy Modeling with R](https://www.tmwr.org/) by Max Kuhn and Julia Silge.
Join the #book_club-tidy_modeling_with_r channel on the [R4DS Slack](https://r4ds.io/join) to participate.
As we read, we are producing [notes about the book](https://r4ds.github.io/bookclub-tmwr/).

## Meeting Schedule

If you would like to present, please see the sign-up sheet for your cohort (linked below, and pinned in the [#book_club-tmwr](https://rfordatascience.slack.com/archives/C01H9SLA48M) channel on Slack)!

- Cohort 1 (started 2021-01-05, ended 2021-10-19): [meeting videos](https://www.youtube.com/playlist?list=PL3x6DOfs2NGgP7y2sOGcYNGFd_9pORpYG)
- Cohort 2 (started 2021-02-07, ended 2021-06-06): [meeting videos](https://www.youtube.com/playlist?list=PL3x6DOfs2NGggq4ssmi3KnOMwODhGz33W)
- Cohort 3 (started 2021-03-29, ended 2021-11-08): [meeting videos](https://www.youtube.com/playlist?list=PL3x6DOfs2NGiAi_0odUkLGxz0ZpFlugg-)
- Cohort 4 (started 2021-12-03, ended 2022-07-01): [meeting videos](https://www.youtube.com/playlist?list=PL3x6DOfs2NGgb6mnvCMUVWEQ4AtLsIxwS)
- [Cohort 5](https://docs.google.com/spreadsheets/d/1kowl2oUm3sUZSYh5z4w_OWA6UEz9iJINd8i1KkeA2_8/edit#gid=0) (started 2023-04-04, facilitated by Federica Gazzelloni): [Tuesdays, 8:00AM CST/CDT](https://www.timeanddate.com/worldclock/converter.html?iso=20230404T130000&p1=24&p2=1440&p3=215) | [meeting videos](https://youtube.com/playlist?list=PL3x6DOfs2NGgSt6vIGQWtLwZXS2Q7WZlE)


<hr>  

## How to Present

This repository is structured as a [{bookdown}](https://CRAN.R-project.org/package=bookdown) site.
To present, follow these instructions:

Do these steps once:

1. [Setup Github Locally](https://www.youtube.com/watch?v=hNUNPkoledI) (also see [_Happy Git and GitHub for the useR_](https://happygitwithr.com/github-acct.html))
2. Install {usethis} and {devtools} `install.packages(c("usethis", "devtools"))`
3. Set up a default {usethis} directory:
  - `usethis::edit_r_profile()` to open your profile for editing.
  - Add this line: `options(usethis.destdir = "YOURDIR")` (replace `YOURDIR` with the root directory under which you want your R projects to appear; or you can skip these steps, and the project will be saved to your Desktop).
  - Restart your R session (Session/Restart R in Rstudio).
4. `usethis::create_from_github("r4ds/bookclub-tmwr")` (cleanly creates your own copy of this repository).

Do these steps each time you present another chapter:

1. Open your project for this book.
2. `usethis::pr_init("my-chapter")` (creates a branch for your work, to avoid confusion, making sure that you have the latest changes from other contributors; replace `my-chapter` with a descriptive name, ideally).
3. `devtools::install_dev_deps()` (installs any packages used by the book that you don't already have installed).
4. Edit the appropriate chapter file, if necessary. Use `##` to indicate new slides (new sections).
5. If you use any packages that are not already in the `DESCRIPTION`, add them. You can use `usethis::use_package("myCoolPackage")` to add them quickly!
6. Build the book! ctrl-shift-b (or command-shift-b) will render the full book, or ctrl-shift-k (command-shift-k) to render just your slide. Please do this to make sure it works before you push your changes up to the main repo!
7. Commit your changes (either through the command line or using Rstudio's Git tab).
8. `usethis::pr_push()` (pushes the changes up to github, and opens a "pull request" (PR) to let us know your work is ready).
9. (If we request changes, make them)
10. When your PR has been accepted ("merged"), `usethis::pr_finish()` to close out your branch and prepare your local repository for future work.
11. Now that your local copy is up-to-date with the main repo, you need to update your remote fork. Run `gert::git_push("origin")` or click the `Push` button on the `Git` tab of Rstudio.

When your PR is checked into the main branch, the bookdown site will rebuild, adding your slides to [this site](https://r4ds.github.io/bookclub-tmwr/).
=======
# R4DS Tidy Modeling with R Book Club

Welcome to the R4DS Tidy Modeling with R Book Club!

We are working together to read [Tidy Modeling with R](https://www.tmwr.org/) by Max Kuhn and Julia Silge.
Join the #book_club-tidy_modeling_with_r channel on the [R4DS Slack](https://r4ds.io/join) to participate.
As we read, we are producing [notes about the book](https://r4ds.github.io/bookclub-tmwr/).

## Meeting Schedule

If you would like to present, please add your name next to a chapter using the [GitHub Web Editor](https://youtu.be/d41oc2OMAuI)!

*Cohort 1: Tuesdays, 8:00pm EST/EDT*

<details>
  <summary> Past Meetings </summary>

- 2021-01-05: Chapter 1: Software for modeling: Jon Harmon
- 2021-01-12: Chapter 2: A tidyverse primer: Jonathan Trattner
- 2021-01-19: Chapter 3: A review of R modeling fundamentals: Tony ElHabr
- 2021-01-26: Chapter 4: The Ames housing data: Tan Ho
- 2021-02-02: Chapter 5: Spending our data: Asmae Toumi
- 2021-02-09: Chapter 6: Feature engineering with recipes: Pavitra Chakravarty
- 2021-02-16: Chapter 7: Fitting models with parsnip: Jordan Krogmann
- 2021-02-23: Chapter 8: A model workflow: Ben Gramza
- 2021-03-02: Chapter 9: Judging model effectiveness: Joe Sydlowski
- 2021-03-09: Q&A with authors Max Kuhn & Julia Silge: Chapters 1-9
- 2021-03-16: Chapter 10: Resampling for evaluating performance: Asmae Toumi/Jon Harmon
- 2021-03-23: Chapter 11: Comparing models with resampling: Jon Harmon
- 2021-03-30: Chapter 12: Modeling tuning and the dangers of overfitting: Andrew Farina
- 2021-04-06: Chapter 13: Grid search: Jim Gruman
- 2021-04-13: Chapter 14: Iterative search: Asmae Toumi
- 2021-04-20: Chapter 15: Screening many models: Tony ElHabr
- 2021-05-11: What we missed about {workflowsets}
- 2021-05-18: Q&A with authors Max Kuhn & Julia Silge: Chapters 10-15
</details>


*Cohort 2: Sundays, 1pm CDT - facilitated by Stephen Holsenbeck*

<details>
  <summary> Past Meetings </summary>

- 2021-02-07: Chapter 1: Software for modeling: Stephen Holsenbeck
- 2021-02-14: Chapter 2: A tidyverse primer: Kevin Kent
- 2021-02-21: Chapter 3: A review of R modeling fundamentals: Layla Bouzoubaa
- 2021-02-28: Chapter 4: The Ames housing data: Amélie Gourdon-Kanhukamwe
- 2021-03-07: Chapter 5: Spending our data: Amélie Gourdon-Kanhukamwe
- 2021-03-21: Chapter 6: Feature engineering with recipes: Graeme Davidson
- 2021-03-28: AI Ethics
- 2021-04-11: Chapter 7: Fitting models with parsnip: Shamsuddeen Hassan Muhammad
- 2021-04-18: Chapter 9: Judging model effectiveness: Luke Shaw
- 2021-04-25: Chapter 8: A model workflow: Kevin Kent
- 2021-05-02: Chapter 10: Resampling for evaluating performance: Rahul Bahadur
- 2021-05-09: Chapter 11: Comparing models with resampling: Graeme Davidson
- **2021-05-16: Chapter 12: Model tuning and the dangers of overfitting: Shamsuddeen Hassan Muhammad**
- 2021-05-23: Chapter 13: Grid search: Stephen Holsenbeck
- 2021-05-30: Appendix A: Recommended preoprocessing
- 2021-06-06: Chapter 14: Iterative search
- 2021-06-13: Chapter 15: Screening many models
</details>


*Cohort 3: Mondays, 11:00am CDT - facilitated by Ildiko Czeller*

<details>
  <summary> Past Meetings </summary>

- 2021-03-29: Chapter 1: Software for modeling: Ildiko Czeller
- 2021-04-05: Chapter 2: A tidyverse primer: Daniel Chen
- 2021-04-12: Chapter 3: A review of R modeling fundamentals: Edgar Zamora
- 2021-04-19: Chapter 4: The Ames housing data: Jiwan Heo
- 2021-04-26: Chapter 5: Spending our data: Ildiko Czeller
- 2021-05-24: Chapter 6: Feature engineering with recipes: Priyanka Gagneja
- 2021-06-07: Chapter 7: Fitting models with parsnip: Toryn Schafer
- 2021-06-14: Chapter 8: A model workflow: Ildiko Czeller
- 2021-06-28: Chapter 9: Judging model effectiveness: Federica Gazzelloni
- 2021-07-05: Chapter 10: Resampling for evaluating performance: Jiwan Heo
- 2021-07-19: Chapter 11: Comparing models with resampling: Edgar Zamora
- 2021-07-26: Chapter 12: Model tuning and the dangers of overfitting: Daniel Chen
- 2021-08-09: Chapter 13: Grid search: Jiwan Heo
- 2021-08-16: Chapter 14: Iterative search: Ildiko Czeller
- 2021-08-23: Chapter 15: Screening many models: Federica Gazzelloni
- 2021-09-20: Chapter 17: Dimensionality reduction: Ildiko Czeller & Federica Gazzelloni
- 2021-09-27: Chapter 18: Explaining models and predictions: Ildiko Czeller & Federica Gazzelloni  
- 2021-10-04: Chapter 19: When should you trust your predictions?: Ildiko Czeller & Federica Gazzelloni  
- 2021-10-18: Chapter 20: Ensembles of models: Jiwan Heo
</details>


*Cohort 4: Fridays, 8:00am CST - facilitated by Federica Gazzelloni*

<details>
  <summary> Past Meetings </summary>
  	
- 2021-12-03	0. Hello World - Book_club Intro: Federica Gazzelloni
- 2021-12-10	1. Software for modeling: Federica Gazzelloni	

</details>

- 2021-12-17	2. A tidyverse primer: Brandon Hurr	
- 2021-12-24	NO MEETING	
- 2021-12-31	NO MEETING	
- 2022-01-07	3. A review of R modeling fundamentals: AL Brown	
- 2022-01-14	4. The Ames housing data	
- 2022-01-21	5. Spending our data: AL Brown	
- 2022-01-28	6. Fitting models with parsnip: Laura Rose	
- 2022-02-04	7. A model workflow	
- 2022-02-11	8. Feature engineering with recipes	
- 2022-02-18	9. Judging model effectiveness	
- 2022-02-25	10. Resampling for evaluating performance	
- 2022-03-04	11. Comparing models with resampling	
- 2022-03-11	12. Model tuning and the danger of overfitting	
- 2022-03-18	13. Grid search	
- 2022-03-25	14. Iterative search	
- 2022-04-01	15. Screening many models	
- 2022-04-08	16. Encoding categorical data	
- 2022-04-15	17. Dimensionality reduction	
- 2022-04-22	18. Explaining models and predictions	
- 2022-04-29	19. When should you trust you predictions	
- 2022-05-06	20. Ensembles of models	
- 2022-05-13	21. Inferential analysis	

<hr>  

## How to Present

This repository is structured as a [{bookdown}](https://CRAN.R-project.org/package=bookdown) site.
To present, follow these instructions:

1. [Setup Github Locally](https://www.youtube.com/watch?v=hNUNPkoledI)
2. Fork this repository.
3. Create a New Project in RStudio using your fork.
4. Install dependencies for this book with `devtools::install_dev_deps()` (technically optional but it's nice to be able to rebuild the full book).
5. Create a New Branch in your fork for your work.
6. Edit the appropriate chapter file. Use `##` to indicate new slides (new sections).
7. If you use any packages that are not already in the `DESCRIPTION`, add them. You can use `usethis::use_package("myCoolPackage")` to add them quickly!
8. Commit your changes.
9. Push your changes to your branch.
10. Open a Pull Request (PR) to let us know that your slides are ready.

When your PR is checked into the main branch, the bookdown site will rebuild, adding your slides to [this site](https://r4ds.github.io/bookclub-tmwr/).
>>>>>>> Stashed changes
