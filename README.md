# save-rdata-to-json
Save an .RData object to JSON

setwd("~/Directory") #set your working directory
FinalResult <- toJSON(Result, pretty=TRUE)
cat(FinalResult)
write(FinalResult, paste("FileName",".json",sep="")) #save the file to your working directory
