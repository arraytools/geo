# geo
```
load(url("https://github.com/arraytools/geo/raw/master/gpl570.rda"))
```

This will load two R objects: gpl570 and gpl570sub. 
```
dim(gpl570)
# [1] 54675    16
dim(gpl570sub)
# [1] 45782    16
> gpl570[1:3, 1:5]
         ID GB_ACC SPOT_ID Species Scientific Name Annotation Date
1 1007_s_at U48705      NA            Homo sapiens     Oct 6, 2014
2   1053_at M87338      NA            Homo sapiens     Oct 6, 2014
3    117_at X51757      NA            Homo sapiens     Oct 6, 2014
> colnames(gpl570)
 [1] "ID"                               "GB_ACC"                          
 [3] "SPOT_ID"                          "Species Scientific Name"         
 [5] "Annotation Date"                  "Sequence Type"                   
 [7] "Sequence Source"                  "Target Description"              
 [9] "Representative Public ID"         "Gene Title"                      
[11] "Gene Symbol"                      "ENTREZ_GENE_ID"                  
[13] "RefSeq Transcript ID"             "Gene Ontology Biological Process"
[15] "Gene Ontology Cellular Component" "Gene Ontology Molecular Function"
```
