# Assignment-B4-OptionA: Strings and Functional Programming in R

This repository contains the implementation of **Option A** for the **assignment-b4** focusing on string manipulation and functional programming in R. It includes two main exercises: **Text Analysis** using Jane Austen's works and a **Pig Latin Conversion** function.

## Repository Structure

In this repository, you will find two key files:

1. **`assignment-b4-optionA.md`**: This is the Markdown file that contains detailed explanations of the project, including the exercises and examples. You can view this file directly on GitHub.
   
2. **`assignment-b4-optionA.rmd`**: This is the RMarkdown file that contains the same information as the `.md` file but also includes the code chunks for executing in R. You can open this file in an R environment (such as RStudio) to execute and render it interactively.

## Project Overview

### Exercise 1: Text Analysis
- **Goal**: Perform text analysis on Jane Austen's *Sense and Sensibility*.
- **Process**:
  1. Tokenize the text and clean it by removing stop words.
  2. Plot the most common words (top 10, top 20, top 30) after cleaning.

### Exercise 2: Pig Latin Conversion
- **Goal**: Convert English words into a modified version of Pig Latin with updated rules.
- **Process**:
  1. Handle words starting with vowels, starting with consonants but still containing vowels, and words without vowels.
  2. Add the appropriate suffix ("yay", "ay", or "xay") based on the original word type.
  3. Provide examples and validation tests for different cases.

## Installation

To get started with this project, you will need to have **R** installed. You can download and install R from the official website: [https://cran.r-project.org/](https://cran.r-project.org/).

### Dependencies

The following R packages are required for running the code:
- `janeaustenr`: For accessing Jane Austen's works.
- `tidyverse`: For data manipulation and visualization.
- `tidytext`: For text mining tasks like tokenization and stop-word removal.
- `purrr`: For functional programming.
- `ggplot2`: For data visualization.
- `testthat`: For testing the functions.

You can install these dependencies by running the following command in R:

```r
install.packages(c("janeaustenr", "tidyverse", "tidytext", "ggplot2", "purrr", "testthat"))
```

