# 3.1 Assignment - American Community Survey
# Frank Neugebauer - DSC520-T301
#
#install.packages("ggplot2")
#library("ggplot2")

#install.packages("rmarkdown")
#library("rmarkdown")

install.packages("pastecs")
library("pastecs")

# Import the data
comm_sur <- read.csv("acs-14-1yr-s0201.csv", header=TRUE)

# 1. Document the elements in your data including the categories 
#    and data types.
print('hi')
stat.desc(comm_sur$HSDegree, basic = TRUE, desc = TRUE, norm = TRUE)
a <- mean(comm_sur$HSDegree) / sd(comm_sur$HSDegree)
print(a)