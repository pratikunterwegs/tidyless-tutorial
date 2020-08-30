# [The `tidy`-less Tutorial](https://pratikunterwegs.github.io/tidyless-tutorial/)

This is the source code for the `tidy`-less tutorial, where we do two things:
1. Introduce you to the wonders of the `data.table` package, and
2. Take you back to base `R`,
all while retaining the functionality of the `tidy/Hadley`-verse.

A readable `bookdown` version can be accessed by clicking the page title above.

## But why!?

> I feel a disturbance in the force...

That disturbance is probably the confusion of why we'd make a tutorial that teaches you how _not_ to use the tidyverse --- especially after spending two months teaching you why and how you _should_.

### No really, why?

The `tidyverse` is fine. If you want to use it, go ahead. But when you pass beyond the level of bashing out a simple analysis in `R` you might want to leave the `tidyverse` behind. When do you know you've passed beyond the basics?

For example:
1. You're building and maintaining code (for example as an `R` package) and this means minimising dependencies,
2. Your `R` code needs to deal with very large datasets,
3. You work with people who don't use the `tidyverse` and are more comfortable in base `R` (and their preferences take priority),
4. Some combination of the above.

### Less tangible reasons

People have pointed out that the `tidyverse` is syntactically nearly a different language from `R` entirely. This comes from it being developed by a small group of people at RStudio, a company that makes the most widely used IDE for `R`. This gives RStudio a larger platform to push their ideas for `R`, and it can be problematic if a single company basically defines the user preferences for an open source project. These arguments are better laid out in: LINK HERE.

## Additional resources

Here are links to external resources to dig deeper in making efficient use of R in data analysis:

- The tidyverse [website](https://www.tidyverse.org/)
- The RStudio [cheatsheats](https://rstudio.com/resources/cheatsheets/)
- The [R for Data Science](https://r4ds.had.co.nz/) book
- The [Advanced R](http://adv-r.had.co.nz/) book
- To learn about making your own packages, the [R Packages](http://r-pkgs.had.co.nz/) book
- [Datacamp](https://www.datacamp.com/tidyverse-tutorials/) has a bunch of tutorials too
