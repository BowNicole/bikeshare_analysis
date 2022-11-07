Bikeshare Analysis- README

This project was actually my first data analysis project that I completed for my _Google Data Analytics Program_ on _Coursera_.

It's a simple analysis on rider trips from a ficticous bikeshare company that focuses on riders stats acoss the different memberships to help them
figure out the differences in rider metrics.

The entire project was performed on RStudio using R programming languages. You can find more about the packages used in the case study itself, but I will focus on one:
1. data.table

This package was extremely helpful when it came to reading and writing the csv files used for the project since they were large. This is the reason why the data  is not 
availabe on here, it had exceeded the available storage limit. R can be notoriously slow when dealing with heavy csv/excel files especially when working with 
the base readr package.

I foudn that data.table's `fread` and `fwrite` functions were exponentially faster and saved me quite a bit of time.

I hope you enjoy taking a look through the study, it was defintiely an arduous but rewarding experience. A really good first trial, if I do say so myself.
