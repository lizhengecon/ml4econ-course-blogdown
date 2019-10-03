Machine Learning for Economists: <br>ml4econ
================

### [Machine Learning for Economists](https://ml4econ.rbind.io/)

-----

<br>

:spiral\_calendar: March, 2020  
:clock8: 17:30 - 20:00  
:round\_pushpin: HUJI, Mount Scopus  
:anchor: [`ml4econ.rbind.io`](https://ml4econ.rbind.io/)

<br>

The schedule below is tentative and subject to change, depending on time
and class interests. We will move at a pace dictated by class
discussions. Please check this page often for updates.

| Week   | Topic                                                                          |
| :----- | :----------------------------------------------------------------------------- |
| **1**  | Course Overview & Basic ML Concepts                                            |
| **2**  | Reproducibiliy and Version Control                                             |
| **3**  | Regression and Classification                                                  |
| **4**  | Regularization                                                                 |
| **5**  | Decision Trees and Random Forests                                              |
| **6**  | Unsupervised Learning                                                          |
| **7**  | Prediction in Aid of Estimation I - Lasso and Average Treatment Effects        |
| **8**  | Prediction in Aid of Estimation II - Trees and Heterogeneous Treatment Effects |
| **9**  | Prediction Policy Problems                                                     |
| **10** | Text as Data                                                                   |

<br>

<!--
01
-use ozbabynames/usbabynames
-make parameterized rmd with plots (added more on params here)
-> deploy at end!

02- focus on HTML outputs [cut version control]
-knit to bookdown (not just for books!) ?
-knit to distill (not just for ML!) ?
-maybe add in generations here
? where to include oz bakeoff?
-knit to flexdashboard
-knit to xaringan
-maybe include good HTML widgets like leaflet for mapping

Where to go?
-knit from the command line
-knitting parameterized reports from the command line

03- templates inside a package
-build an opinionated template with custom things in it
-data?
-->

-----

## Overview

This course covers topics that range between machine learning (ML) and
econometrics. In particular, we will discuss concepts from the world of
ML that can potentially contribute to empirical research in economics.
The course will cover basic machine learning (supervised and
unsupervised) methods, with an emphasis on the challenges and
opportunities of integrating these methods in economics, and the
relevance of ML to policy analysis and causal inference. The various
topics are illustrated through applications, reading empirical articles,
and doing applied work.

## Pre-work

Welcome to the [Communicating with R Markdown](/) workshop\! We look
forward to meeting you in person. Before attending the workshop, please
complete the following prework:

1.  Sign up for a free RStudio Cloud account at <https://rstudio.cloud/>
    before the workshop. I recommend logging in with an existing Google
    or GitHub account, if you have one (rather than creating a new
    account with another password you have to remember).

2.  We will be using GitHub in this workshop for version control and
    publishing. Sign up for a free GitHub.com account at
    <https://github.com/join> if you don’t already have one. Also:
    
      - Complete these [installation
        instructions](https://happygitwithr.com/install-intro.html).
    
      - Test your connection between GitHub and RStudio following [these
        steps](https://happygitwithr.com/connect-intro.html).
    
      - **NOTE:** We *strongly recommend* that if you are not already a
        fluent GitHub user you choose [HTTPS over
        SSH](https://happygitwithr.com/credential-caching.html).

3.  Complete this [10-minute interactive tutorial on
    Markdown](https://commonmark.org/help/tutorial/).

4.  Please bring a laptop that has the following installed:
    
      - A recent version of R (\>=3.6.0), which is available for free at
        <https://cloud.r-project.org/>
    
      - A recent version of RStudio Desktop (\>=1.2), available for free
        ([RStudio Desktop Open Source
        License](https://www.rstudio.com/products/rstudio/download/#download))
    
      - The R packages we will use, which you can install by connecting
        to the internet, opening RStudio, and running at the command
        line:
        
        ``` r
        install.packages(c("rmarkdown", "devtools", "usethis", "here", 
                           "tidyverse", "xaringan", "flexdashboard", 
                           "distill", "bookdown", "blogdown",
                           "glue", "wesanderson"))
        ```

5.  Don’t forget your power cord\!

On the day of the workshop, I’ll provide you with an RStudio Cloud
project that contains all of the course materials. We will use the
software listed above only as an important backup should there be
problems with the on-site internet connection.

[View slides](/slides/00-loop.html) *(note: these slides are
intentionally a loop and will play on autoadvance)*

-----

[![forthebadge](https://forthebadge.com/images/badges/cc-by.svg)](https://creativecommons.org/licenses/by/4.0/)  
This work is licensed under a [Creative Commons Attribution 4.0
International License](https://creativecommons.org/licenses/by/4.0/).
