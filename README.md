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
  
