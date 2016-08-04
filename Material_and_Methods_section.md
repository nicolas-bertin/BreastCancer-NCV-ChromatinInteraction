# Material and Methods

## Human Reference Genome
hg19 / GRCh37 Genome Reference Consortium Human Reference 37 (GCA_000001405.1) retrieved from http://hgdownload.cse.ucsc.edu/goldenPath/hg19/chromosomes/
<br>Note: We excluded chr6 alternate haplotype assemblies, the (chr*_random) sequences that are unplaced on reference chromosomes, as well as, the are unlocalized sequences where the corresponding reference chromosome has not been determined (chrUn_*).


## Reference Transcriptome
We used the UNC reference transcriptome used for mRNA-seq data processing by UNC as part of The Cancer Genome Atlas project, relevant to the level 3 data for the ‘rnaseqv2’ platform available at the TCGA Data Coordinating Center (DCC), retrieved from https://webshare.bioinf.unc.edu/public/mRNAseq_TCGA/
<br>Note:  contains 73,599 mapped transcripts associated to 26,750 genes (excluded were 108 transcripts/65 genes with no genome location).


## COSMIC WGS non-coding variants
We retrieved the list of curated non-coding mutations across all referenced cancers from COSMIC version 73, retrieved from http://grch37-cancer.sanger.ac.uk/cosmic/files?data=/files/grch37/cosmic/v73/CosmicNCV.tsv.gz
and extracted those corresponding the breast cancer patient samples from “Breast Cancer – UK” (cosmic_study_id 385) and “Breast Invasive Carcinoma (TCGA, US) import from ICGC” (cosmic_study_id 414) datasets


## GWAS Single Nucleotide Polymorphisms
 
NHGRI's collection of Genome-Wide Association Studies SNPs Catalog is a quality controlled, manually curated, literature-derived collection of all published genome-wide association studies assaying at least 100,000 SNPs and all SNP-trait associations with p-values < 1.0 x 10-5 (Hindorff et al., 2009). It was retrieved from UCSC table browser on 06 May 2015 and includes a total of 7,536 GWAS SNPs, 308 of them are associted to breast cancer  


## PanCancer Mutation hotspot (Weinhold et al. Nat. Gen. 2014)  

PanCancer Mutation hotspots were retireved from Weinhold et al. Nat. Gen. 2014 Supp table 17 (“Hotspots In Individual Cancer Types”). Breast cancer mutation hotspots wrere complemented (based on overlapping genomic coordinates) with Breast Cancer COSMIC WGS non-coding variants list described above.


## Chromatin-chromatin interactions

Published chromatin-chromatin interactions were retreived from ENCODE data portal : https://www.encodeproject.org/ as bed12 formatted file, accession numbers : ENCSR000CAD (CTCF ChIA-PET on human MCF-7),  ENCSR000BZZ (ESR1 ChIA-PET on human MCF-7) and ENCSR000CAA (POLR2A ChIA-PET on human MCF-7)
