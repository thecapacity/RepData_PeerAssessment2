### Introduction

Storms and other severe weather events can cause both public health and economic problems for communities and municipalities. Many severe events can result in fatalities, injuries, and property damage, and preventing such outcomes to the extent possible is a key concern.

This project involves exploring the U.S. National Oceanic and Atmospheric Administration's (NOAA) storm database. This database tracks characteristics of major storms and weather events in the United States, including when and where they occur, as well as estimates of any fatalities, injuries, and property damage.

**My practice for this analysis will follow the Reproducable Research standards and be published on my [RPubs Account](rpubs.com/thecapacity/).**

In addition to being published on RPubs, the full data file for this analysis is also available [on GitHub](https://github.com/thecapacity/RepData_PeerAssessment2/blob/master/NOAA_Storm_Analysis.Rmd).

### Data

The data for this assignment came as a comma-separated-value file compressed via the bzip2 algorithm to reduce its transmission size. The [Storm Data file](https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2FStormData.csv.bz2) can be downloadedfrom the Coursera course web site.

There is also some documentation of the database available here:

* National Weather Service [Storm Data Documentation](https://d396qusza40orc.cloudfront.net/repdata%2Fpeer2_doc%2Fpd01016005curr.pdf)

* National Climatic Data Center [Storm Events FAQ](https://d396qusza40orc.cloudfront.net/repdata%2Fpeer2_doc%2FNCDC%20Storm%20Events-FAQ%20Page.pdf)

The events in the database start in the year 1950 and end in November 2011. In the earlier years of the database there are generally fewer events recorded, most likely due to a lack of good records. More recent years should be considered more complete.

### Guidance

The fllowing guidance was received to inform the analsis.

* Language: The document should be written in English.

* Title: The document should have a title that briefly summarizes your data analysis

* Synopsis: Immediately after the title, there should be a synopsis which describes and summarizes your analysis in at most 10 complete sentences.

* There should be a section titled Data Processing which describes (in words and code) how the data were loaded into R and processed for analysis. In particular, analysis must start from the raw CSV file containing the data; there will be no preprocessing outside the document. **If preprocessing is time-consuming the cache = TRUE option may be used for certain code chunks.**

* There should be a section titled Results in which your results are presented.

* You may have other sections in your analysis, but Data Processing and Results are required.

* The analysis document must have at least one figure containing a plot.

* The analyis must have no more than three figures. Figures may have multiple plots in them (i.e. panel plots), but there cannot be more than three figures total.

* All your code must be shown for the work in your analysis document. This may make the document a bit verbose, but that is okay. In general, I will ensure that echo = TRUE for every code chunk (this is the default setting in knitr).

* For this assignment, the final assessment will be published on RPubs.com, at the account indicated earlier. This will be published to RPubs by doing the following:

    1. In RStudio, make sure your R Markdown document (.Rmd) document is loaded in the editor

    2. Click the Knit HTML button in the doc toolbar to preview your document.

    3. In the preview window, click the Publish button.

    **NOTE: If I have trouble connecting with RPubs the final analysis document file will be captured in my GitHub account, as well as uploaded as a PDF to Coursera.**