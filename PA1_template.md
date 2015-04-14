# Reproducible Research: Peer Assessment 1


### Loading and preprocessing the data

```r
library(ggplot2)
file <- "activity.zip"
data <- read.csv(unz(file,  "activity.csv"))
data$date <- as.Date(data$date, format = "%Y-%m-%d")
```

### What is mean total number of steps taken per day?

![](./PA1_template_files/figure-html/unnamed-chunk-2-1.png) 

The mean total number of steps taken per day is 1.0766189\times 10^{4}

The mean total number of steps
## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
