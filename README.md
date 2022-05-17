# co-edu

getwd()
setwd("c:/tp")
data <- read.csv('c:/tp/Co_edu.csv')

summary(data)

data
tail(str(data))
data$onln_cls_hope<-as.factor(data$onln_cls_hope)
levels(data$onln_cls_hope)

data[data$onln_cls_hope == "on.offine_class " , ]
data[data$onln_cls_hope == "offline_class " , ]
data[data$onln_cls_hope == "on_class" , ]
