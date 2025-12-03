# Hands-on workshop for age-depth modelling using Bchron

Hello and welcome to age-depth modelling using Bchron. There are a few necessary installation instructions to comlpete ahead of time to ensure the workshop runs smoothly!

Install:

- [Quarto CLI](https://quarto.org/docs/get-started/)

Update:

- R
- RStudio (or your prefered IDE)

Install the required packages:

- Open R (after updating it) and run these lines in the console

```
if (!require("pacman")) install.packages("pacman", repos="http://cran.r-project.org")
pacman::p_load(neotoma2, Bchron, splines, ggplot2, dplyr)
```
