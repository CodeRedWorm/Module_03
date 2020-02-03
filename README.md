# Module_03
Cleaned up the data as RStudio did not recognize some of the quotation mark characters. Also added commas where missing.

Name <- c("Jeb", "Donald", "Ted", "Marco", "Carly", "Hillary", "Berine")
ABC <- c(4, 62, 51, 21, 2, 14, 15)
CBS <- c(12, 75, 43, 19, 1, 21, 19) 

Created a data frame (d) using the data. 
d <- data.frame(Name,ABC,CBS,stringsAsFactors=FALSE)

Calling the data frame
d

Viewing column 1 in two different ways
d[1] or d[,1]

Viewing row 1. In this example "Jeb" and his corresponding poll numbers are displayed.
d[1,]
