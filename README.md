# OpenCaseStudies

This case study is part of the [OpenCaseStudies]() project. This work is licensed under the Creative Commons Attribution-NonCommercial 3.0 ([CC BY-NC 3.0](https://creativecommons.org/licenses/by-nc/3.0/us/)) United States License.


### Title

Twitter Vaccination Opinion Analysis

### Motivating question

Can we find communities of anti-vaccination individuals  on Twitter?

### Data

A Twitter dataset has been included in this case study for your convenience. A short description on how to generate an identical dataset using the Twitter API package `rtweet` is also included in the study if you would like to create your own.

### Analysis

The analysis includes data cleaning with regular expressions, data exploration and visualization using Natural Language Processing techniques, sentiment analysis, and topic modeling.

### Note to Instructors

This case study is a comprehensive introduction to working with text data:

- The `tidytext` library is the foundation of the study, allowing students to continue using tidyverse libraries such as `dplyr` and `ggplot2`.

- For cleaning text data, the package `stringr` is used to parse strings with regular expressions.

- Natural language processing methods such as tokenization, word stemming, removing stop words, and finding n-grams are introduced as a means to clean and explore text data.

- Sentiment analysis with the `tidytext` library is introduced.

- Document clustering or topic modeling is performed using Latent Dirichlet allocation from the `topicmodels` package.

### Other notes and resources

A great resource for this work is [Text Mining with R](https://www.tidytextmining.com/index.html), A Tidy Approach by Julia Silge and David Robinson.

### Keywords