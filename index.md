# Data Analysis and Visualisation in R

This is an introduction to R designed for participants with no programming experience. 

## Set up

1. Install R & RStudio

*University device*

- Search 'R project' in the Software Center / Self Service and install.
- Search RStudio in the Software Center / Self Service and install.

*Personal device*

- Install [R](https://cran.stat.auckland.ac.nz/) and then [RStudio](https://posit.co/download/rstudio-desktop/) directly.

2. Install required R package

- In RStudio, click on the Tools menu then Install Packages.
- Type `tidyverse` and click install.
- Wait for the background processes to finish (can take a couple of minutes).

3. Know how to check for updates

- Keep R up to date by checking CRAN every now and then.
- Keep RStudio up to date by following the automatic prompts in outdated versions.
- Keep packages up to date by clicking Tools > 'Check for package updates' every now and then.

3. Download the data

- Download this data file and save it somewhere convenient.

## Introduction to R & RStudio

### What are R & RStudio?

R is a programming language as well as the software that runs R code written in that language.

RStudio is separate software which provides an interface that makes it more conveneient to interact with R and write R code.

### Why learn R?

1. Programming is more efficient than pointing and clicking

- Instead of remembering what you clicked on and in what order, writing out R code and saving it in a script file makes it far easier to see what you did and why. 
- If your data changes, or you have another similar dataset, a script can be rerun in seconds.

2. R is great for reproducibility

- By publishing your data and code, you ensure that your results are transparent, verifiable, and can be built on by others.

3. R can do just about anything

- R was originally written with statistics in mind, but it has been expanded and extended over the years into a fully fledged programming language capable of performing all kinds of tasks.
- R works on data of all shapes and sizes, and there are community-developed packages to make it easier to perform all kinds of analyses and workflows.

4. R produces famously good graphics

- With R you can create professional-looking plots and figures to submit to journals with your manuscripts.

5. The R community is welcoming and helpful

- R is popular among researchers so you'll find large and welcoming communities of fellow R users in places like [Stack Overflow](https://stackoverflow.com/) or the [Posit Forums](https://forum.posit.co/) (Posit is the company which makes RStudio).

### Navigating RStudio

RStudio can help with many advanced tasks, but we're going to be focussing on the core features.

In the default layout there are 4 panes, clockwise from top left:

1. Top left: Source pane. Displays scripts, data, and other files.
2. Top right: Environment pane. Displays the objects in your current R session.
3. Bottom right: Files pane. Displays a file explorer, any plots you create, and help information.
4. Bottom left: Console. Where commands are executed by R.

!(img/)

These 4 panes comprise most of what you need to work with R. Other features we will see:
- Keyboard shortcuts
- Autocompletion
- Syntax highlighting

### Creating a project




