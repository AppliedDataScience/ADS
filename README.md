ADS
===
data <- read.table("adult.txt",header=FALSE,sep=",")

View(data)

colnames(data) <- c("age","workclass","fnlwgt","education","educationnum","maritalstatus",
                    
                    "occupation","relationship","race","sex","capitalgain","capitalloss",
                    
                    "hoursperweek","nativecountry","income")
