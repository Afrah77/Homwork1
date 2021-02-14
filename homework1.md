Homework \#1 – Pet Names Dataset
================
Afrah jaber
2021-02-14

\*\*Student ID:2201002977

**Deadline:** 23:59 on Saturday, 13 February 2021

**Total Points:** 30

## Loading Packages

``` r
library(tidyverse)
library(openintro)
library(ggrepel)
```

\#\#Exercises According to the data dictionary, how many pets are
included in this dataset? - 52519

\`1.

(4 points)

\#Exercises 2 how many varibles do we have for each pet?  
- variables 7

\`2.

(4 points)

Write your narrative below

\`3. Copy the code provided in the homework documentation and paste it
here. seattlepets %&gt;% + count(animal\_name, sort = TRUE)

(4 points)

Write your narrative here

seattlepets %&gt;% group\_by(species) %&gt;% count(animal\_name, sort =
TRUE) %&gt;% slice\_max(n, n = 5)

\`4.

(10 points)

\`5. What names are more common for cats than dogs? The ones above the
line or the ones below the line?

Answer here

(4 points)

\`6. Is the relationship between the two variables (proportion of cats
with a given name and proportion of dogs with a given name) positive or
negative? What does this mean in context of the data?

Answer here

(4 points)
