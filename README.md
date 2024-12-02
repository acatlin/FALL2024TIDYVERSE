# FALL2024TIDYVERSE

# Sample
Initial Description and Link: 
* Demonstrates how to flip ggplot axes
* ggplot_forcats.qmd


Revision/Addition Description and Link: 
* Modified ggplot/forcats example to demonstrate sorting, other category
* ggplot_forcats.qmd

# Amish R.

Initial Description and Link: `group_by` and `summarize` tidyverse functions
amish_tidyverse_vignette.rmd

Revision/Addition Description and Link:
* Modified amish_tidyverse_vignette.rmd to include an example of the ungroup() command
* Extension begins on line 61
=======
Revision/Addition Description and Link: additional examples demonstrating data transformation and visualization through the use of mutate() and other dyplr functions. 

dplyr+ggplot2-extended.Rmd

# Anthony R.

Initial Description and Link:
- Using `pivot_longer()` to reshape data for visualization
- Utilizing multiple methods to visualize data
- roman_tidyverse.qmd
- [Here is a link to my github source](https://raw.githubusercontent.com/spacerome/TidyVerseCREATE/refs/heads/main/tidyverseCREATE.qmd)

Revision/Addition Description and Link:
- Added advanced text analysis techniques using Tidyverse for Alexander Wrubel
- Extension is [here](Data607_tidyverseAW+extended.Rmd)

# Benjamin W.

Initial Description and Link:
* Demonstrates how to use the gather function to collpse multiple columns of a datadrame into key-value pairs.
* BW_Gather.RMD

Revision/Addition Description and Link:


# Crystal Q.

Initial Description and Link:

Revision/Addition Description and Link:


# Daniel B.

Initial Description and Link: This dataset explores maternal health risks for pregnant women based on factors such as age and blood pressure. It focuses on the RiskLevel column and uses ggplot2 to better explore how age and blood pressure relate to the risk level.  
Tidyverse create Daniel Brusche.Rmd
Revision/Addition Description and Link:


# John F.

Initial Description and Link:
- Basic Usage of the `group_by()` function for aggregate metrics.
- groupby_vingette.Rmd

Revision/Addition Description and Link:
- Extended the initial file `unnesting.Rmd` from tillmawitz
- Around line 114 is where my extension begins.
- Extended with `group_split()` from kevinhav


# Julian A-N.

Initial Description and Link:

Revision/Addition Description and Link:


# Keith R.

Initial Description and Link:
* Using dplyr's count() function for calculating subtotals of observations in a group.
* count()_vignette.Rmd

Revision/Addition Description and Link:
* Extended groupby_vingette.rmd to include an example of how to use the count() function (starting at line 77).


# Kevin H.

Initial Description and Link:
- Using `across()` with `mutate()` for column-wise transformations
- across_vignette.Rmd

Revision/Addition Description and Link:


# Kevin K.

Initial Description and Link:
* Combining `tidytext` for text mining with `gganimate` for animated visuals to create dynamic visualizations 
* kkirby_tidytext.Rmd

Revision/Addition Description and Link:


# Kimberly K.

Initial Description and Link:
- Using 'dense_rank()' with 'group_by()' and 'desc()' to perform equivalent to rank() over (partition by order by) in SQL
- Using case_when() to perform equivalent to case when in SQL
- DATA_607_Koon_Tidyverse_Create.Rmd

Revision/Addition Description and Link:
- Extended Zach R's ggplot vignette, Data607TidyVerse.Rmd
- Found the dataset on fivethirtyeight and edited the dataset loading to point to a publicly available path
- Demonstrated the use of scale_color_manual() to map colors to the data in ggplot

# Luis M.

Initial Description and Link: For the CREATE assignment, I provided an example of the use of some functions from the forcats package:
- fct_reorder(): Reordering a factor by another variable.
- fct_relevel(): Changing the order of a factor by hand.
[Link](https://github.com/acatlin/FALL2024TIDYVERSE/blob/main/607_LMG_create_forcats.Rmd)

Revision/Addition Description and Link: For the EXTEND assignment, I chose gather() by Ben W to include an explanation of separate () and mutate()
[Link](https://github.com/Lfirenzeg/FALL2024TIDYVERSE/blob/main/BW_Gather.Rmd)
# Matthew T.

Exploring how to work with nested data using `unnest()`

Initial Description and Link:\
Nested data occurs when a cell of a dataframe contains a list or similar object. Properly unnesting can range from very simple to incredibly complicated, and we will explore a few examples and explain how to handle them using the `tidyr` package.

[Click here to see the example!](unnesting.Rmd)

Revision/Addition Description and Link:\
Extending the work done by [Kevin H.](#kevin-h) on the `across()` function we explore the similar `if_any()` and `if_all()` functions which can be used with the `filter()` function as well as `mutate()`. The `if_any()` and `if_all()` functions follow the same pattern as `across()` and can be used when conditional operations are desired.

[Check out the extension here!](across_vignette.Rmd)

# Tenzin D.

Initial Description and Link:

Revision/Addition Description and Link:


# Nwe M.

Initial Description and Link:

Revision/Addition Description and Link:


# Robert G.

Initial Description and Link:

Revision/Addition Description and Link:


# Tiffany H.

Initial Description and Link:This vignette explores analyzing election deniers' stances by state, using mutate() and case_when() from dplyr for efficient conditional transformations and recoding. It also demonstrates group_by(), summarize(), and arrange() for data aggregation. ggplot2 is used for visualization.

file name: dplyr+ggplot2.Rmd

Revision/Addition Description and Link:

I expanded Kimberly K.'s vignette by incorporating visualizations using the ggplot2 package. These visualizations include a detailed breakdown of salary proportions by subdiscipline and an exploration of the relationship between salary and education level. The extension begins on line 10.

file name: DATA_607_Koon_Tidyverse_Extension.rmd


# Zachary R.

Initial Description and Link:A vignette demonstrating the use of TidyVerse packages (`dplyr`, `ggplot2`, and `kable`) to analyze polling trends using FiveThirtyEight data on Donald Trump's polling percentages over time.
Data607TidyVerse.Rmd

Revision/Addition Description and Link: 
Created new dataset featuring total and average consumption rates by year to the file 'BW_Gather.RMD'. Created additional visualizations using ggplot and kable for cleaner visibility. 


# Alinzon Simon

Initial Description and Link:
`purrr`, is part of the Tidyverse and is designed for working with functional programming concepts in R; especially for lists, vectors, and data frames. 
https://purrr.tidyverse.org/

purrr_tidyverse.Rmd

Revision/Addition Description and Link:

# Alexander Wrubel

Initial Description and Link:
- using stringr package to clean and prep data
- Data607_tidyverseAW.Rmd

Revision/Addition Description and Link:
