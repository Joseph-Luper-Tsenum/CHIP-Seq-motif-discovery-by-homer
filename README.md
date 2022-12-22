# CHIP-Seq motif discovery by homer for chromosome 18 of the human genome 

### Introduction

Increasing quantities of long noncoding RNAs (lncRNAs) are now found in mammalian transcriptome, and scientist have reported that a good number of them are expressed specifically in the brain. For example, Shi-Yan et al. 2013 reported that some lncRNAs are expressed in the brain including rhabdomyosarcoma 2-associated transcript (RMST). RMST is regulated by REST (a transcription repressor). RMST's role in neurogenesis can be traced to its over expression during neuronal differentiation. To exert its functions, RMST physically interacts with a transcription factor (SOX2). SOX2 is known to modulate the fate of neurogenesis. A huge number of downregulated genes known to be involved in neurogenesis are coregulated by RMST and SOX2. Shi-Yan et al. 2013 reported that RMST is needed for SOX2 to bind to the promoter regions of neurogenic transcription factors. 

Here,chromosome 18 of the human genome was used for CHIP-Seq motif discovery by homer based on the paper by Shi-Yan et al. 2013 (https://www.cell.com/molecular-cell/fulltext/S1097-2765(13)00543-1?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS1097276513005431%3Fshowall%3Dtrue)


### PART I

#### SOX2 analysis:

The following Motifs homer were found from our SOX2 analysis. Only the first five motifs have been shown here.

                                     First Five motifs found by homer for SOX2

![now25](https://user-images.githubusercontent.com/58364462/208830191-5eb5c663-d6e4-4c0f-a9a0-8561a670fb1a.png)

From our SOX2 analysis, there was no similar motif as our known SOX2 motif, even though some motifs looks like s our known SOX2 motif, an example is the 6th motif in the result

### PART II

#### RMST Analysis:

Following Motifs homer were found from our RMST analysis. Only the first five motifs have been shown here.

                                     First Five motifs found by homer for  RMST
                                    
![now26](https://user-images.githubusercontent.com/58364462/208831058-f40adbce-5996-49f1-8fef-edc4a260a039.png)

From our RMST analysis, there was no similar motif as our known SOX2 motif, even though some motifs looks like s our known SOX2 motif, an example is the 6th motif in the result.

### Conclusion

• There was no similar SOX2 motif found for both SOX2 and RMST analysis.

• Randomly, chromosome (chr18) of the human genome was used, and even though the required result did not turn out, there are motifs that are very close to being similar to our known SOX2 motif, meaning that if we consider only one chromosome, it can still produce a similar or nearly similar results. Despite the absence of identified motifs, it is necessary to search for motifs at the whole genome level to avoid false negative results. 


The same process was repeated for Chromosome 19, but there was no motif was discovered as being similar to our known SOX2 motif. 


##### The homer results for chromosome 18 is uploaded here as HomerResults.html file while the homer results for chromosome 19 is uploaded as ChIP-Seq_for Chromosome 19_Motifs.zip file. You can download it and view the results.


##### To learn more about homer, http://homer.ucsd.edu/homer/motif/ and http://homer.ucsd.edu/homer/ will be helpful


### References

1. Ng SY, Bogu GK, Soh BS, Stanton LW. The long noncoding RNA RMST interacts with SOX2 to regulate neurogenesis. Mol Cell. 2013 Aug 8;51(3):349-59. doi: 10.1016/j.molcel.2013.07.017. PMID: 23932716.

2. Heinz S, Benner C, Spann N, Bertolino E et al. Simple Combinations of Lineage-Determining Transcription Factors Prime cis-Regulatory Elements Required for Macrophage and B Cell Identities. Mol Cell 2010 May 28;38(4):576-589. PMID: 20513432


