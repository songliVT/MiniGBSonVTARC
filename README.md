# MiniGBSonVTARC
This is a repository for a tutorial to run GBS pipeline on Virginia Tech ARC

I developed this document for teaching Introduction to Genomic Data Science at Virginia Tech. In 2023, some students are interested in using GBS pipeline to analyze their own data. This is a step-by-step instruction on how to run GBS pipeline on Virignia Tech ARC, TinkerCliffs cluster in 2023. This pipeline is largely based on an online tutorial here:

https://bioinformaticsworkbook.org/dataAnalysis/VariantCalling/gbs-data-snp-calling-using-tassel.html#gsc.tab=0

However some details of the scripts will be different from the online tutorial due to the differences in the computing resource. This is also a minimum pipeline where we only use one single fastq file as our input to reduce the total time need to test this pipeline on ARC. Change this pipeline to a pipeline that can analyze 91 or more fastq files should be relatively straight forward. 

##Step 0. Download fastq data.

##Step 1. Rename fastq data and create symbolic link.

##Step 2. Download genome and create bowtie2 index.

##Step 3. Run tassel pipeline. 




