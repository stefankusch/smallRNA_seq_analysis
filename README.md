## Analysis of smallRNA-seq data obtained from *Blumeria graminis* f.sp. *hordei*-infected barley

In this repository, we summarize the scripts and pipelines used to perform the analysis of smallRNA-seq data obtained from *Blumeria graminis* f.sp. *hordei*-infected barley. The publication can be found **here**.

#### Index

01. Raw sequencing data processing.
02. Read length distribution analysis.
03. RFAM BLAST analysis of reads. 
04. ShortStack analyis for milRNA discovery in *H. vulgare* and *B. graminis* f.sp. *hordei*
05. Differential expression analysis of milRNAs in *H. vulgare* and *B. graminis* f.sp. *hordei*
06. Sample clustering by WGCNA
07. Target prediction of milRNAs
08. Gene Ontology (GO) enrichment

#### References

- ShortStack [Publication](https://doi.org/10.1534/g3.116.030452)
- Trimmomatic [Publication](https://doi.org/10.1093/bioinformatics/btu170) | [Manual](http://www.usadellab.org/cms/uploads/supplementary/Trimmomatic/TrimmomaticManual_V0.32.pdf)
- MMSeqs2 [Publication](https://doi.org/10.1038/nbt.3988) | [Manual/Repository](https://github.com/soedinglab/mmseqs2)
- featureCounts [Publication](https://doi.org/10.1093/bioinformatics/btt656)
- Samtools [Publication](https://academic.oup.com/bioinformatics/article/25/16/2078/204688) | [Manual](http://www.htslib.org/doc/)
- BEDtools [Publication](https://academic.oup.com/bioinformatics/article-lookup/doi/10.1093/bioinformatics/btq033) | [Manual](https://bedtools.readthedocs.io/en/latest/)
- gffread [Manual](http://ccb.jhu.edu/software/stringtie/gff.shtml)
- SeqKit [Publication](https://doi.org/10.1371/journal.pone.0163962) | [Manual](https://bioinf.shenwei.me/seqkit/usage/)
- BBmap [Manual](https://jgi.doe.gov/data-and-tools/software-tools/bbtools/)
- NCBI Blast+ [Website](https://www.ncbi.nlm.nih.gov/books/NBK279690/)
- RepeatMasker [Website](http://www.repeatmasker.org)
- DESeq2 [Publication](https://doi.org/10.1186/s13059-014-0550-8) | [Manual](https://bioconductor.org/packages/devel/bioc/manuals/DESeq2/man/DESeq2.pdf)
- EdgeR [Publication](https://dx.doi.org/10.1093/bioinformatics/btp616) | [Manual](https://bioconductor.org/packages/release/bioc/vignettes/edgeR/inst/doc/edgeRUsersGuide.pdf)
- Limma-VOOM [Publication](https://doi.org/10.1186/gb-2014-15-2-r29) | [Manual](https://rdrr.io/bioc/limma/man/voom.html)
- WGCNA [Publication](https://doi.org/10.1186/1471-2105-9-559) | [Manual](https://horvath.genetics.ucla.edu/html/CoexpressionNetwork/Rpackages/WGCNA/)
- psRNAtarget [Publication](https://doi.org/10.1093/nar/gkr319) | [Website](https://www.zhaolab.org/psRNATarget/)
- ShinyGO [Publication](https://doi.org/10.1093/bioinformatics/btz931) | [Website](http://bioinformatics.sdstate.edu/go/)
