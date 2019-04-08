# FluOMICS lung: source code #

## List of figures:
[Fig. 1A](#fig-1a)

### Fig. 1A


## Supplemental material:

### a. RNA-Seq analysis:
code:  
- preprocessing [[MD]](code/20180402_FluOMICS.preprocessing.md)  
  
input:  
- non-normalized (raw) gene counts [[CSV]](input/lung.genecounts.csv)  
- mouse GRCm38 genome annotation [[GTF]](input/genes.gtf)  
- sample annotation [[TSV]](input/SraRunTable.txt)  
  
output:  
- raw SeqExpressionSet [[RDA]](output/fluomics.seqSetRaw.RData)  
- normalized SeqExpressionSet [[RDA]](output/fluomics.seqSet.RData)  
- mock-subtracted SeqExpressionSet [[RDA]](output/fluomics.seqSetBaselined.RData)  
- list of differential expression models [[RDA]](output/fluomics.fits.RData)  
