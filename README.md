# My R Package: Statistical Functions with Arithmetic Operations

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![R](https://img.shields.io/badge/R-≥3.5.0-blue.svg)](https://www.r-project.org/)
[![GitHub issues](https://img.shields.io/github/issues/yourusername/yourpackage.svg)](https://github.com/yourusername/yourpackage/issues)

## Overview
This R package provides functions for computing basic statistical measures such as **Mean, Variance, Standard Deviation, and Standard Error**, with additional arithmetic operations (Addition, Subtraction, Multiplication, and Division). 

## Installation

To install the package directly from GitHub:

```r
# Install devtools if not already installed
install.packages("devtools")

# Install the package from GitHub
devtools::install_github("https://github.com/SaravanarajK-Stat/StatTool")

library(yourpackage)

# Example usage
x <- c(10, 20, 30, 40, 50)

# Compute mean with addition of 5
stat_mean(x, 5, "add")

# Compute variance with multiplication by 2
stat_var(x, 2, "multiply")

# Compute standard deviation with subtraction
stat_sd(x, 3, "subtract")

# Compute standard error with division by 2
stat_se(x, 2, "divide")
