# this file contain all kinds of learning materials 
(1) git and github
## https://happygitwithr.com/rstudio-git-github.html

(2) R for data science / machine learning 

(3) mathematics / statistics

(4) Bioinformatics

(5) Biostatistics

# R-Bioconductor-Bioinfo-tips

pipe %>%

bioMart
MEME 
HOMER
1) IRangers
2) GRangers
3) Biobase
  
  all GSExxx files can be down loaded with GEO function
  geoq <- Biobase::getGEO("GSE9514")
  e <- geo[[1]]  # expressionSet
  exprs(e)
  pData(geo[[1]]) 
  names(pData(e))
  fData(e)
  names(fData(e))
  annotation(e)
  assay()
  rowData()
  
## download to current working dir
download.file("http://bowtie-bio.sourceforge.net/recount/ExpressionSets/bottomly_eset.RData", "bottomly_eset.RData")  
load("bottomly_eset.RData")
or 
load(url("http://bowtie-bio.sourceforge.net/recount/ExpressionSets/bottomly_eset.RData"))
  
