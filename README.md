# Bioinfromatics TopicModeling
We have extracted Bioinformatics related posts from the following websites:\
  1.https://stackoverflow.com/ \
  2.https://bioinformatics.stackexchange.com/ \
  3.https://stats.stackexchange.com/ \
  4.https://biology.stackexchange.com/ \
Then we have run LDA(Mallet) to find topics within them.
The IPython notebook,  "metrics.ipynb",  shows how the metrics were calculated for the selected models.\
The selected models are in the "model/" folder.
Each folder contains selected model of the website with which folders are  named.
Inside the folder \
  'doctopics.txt' represents the correlation between posts and topics.\
  The *.xlsx files contains the questions and answers who are mostly related to the topic.\
  'MapUniqueIdsToPostIds.pkl' includes the mapping from post id in doctopics to the actual post id of the website which is used to go to the actual post.\
  *.pkl files are some intermediate files needed for time-based analysis\
  Label.csv includes the labels\
  DesignPostInformation.csv includes the information of the posts we have worked with.
  
 The tags of different websites we have worked with are listed bellow:
  |Candidate Tags     |Stackoverflow|Biology|CrossValidated|
  |-------------------|-------------|-------|--------------|
  |ape-phylo          |56           |-      |- |
  |allele             |-            |75     |- |
  |bioconductor       |645          |-      |- |
  |bioinformatics     |3063         |905    |216 |
  |biojava            |26           |-      |- |
  |biom               |12           |-      |- |
  |biomart            |44           |-      |- |
  |bioperl            |125          |-      |- |
  |biopython          |1023         |10     |- |
  |bio-services       |17           |-      |- |
  |biostatistics      |-            |-      |660 |
  |blast              |205          |56     |- |
  |chromosome         |-            |224    |- |
  |computational-model|-            |73     |- |
  |clustalx           |8            |-      |- |
  |clustal            |11           |-      |- |
  |dendropy           |7            |-      |- |
  |dna-sequence       |358          |325    |- |
  |database           |-            |154    |- |
  |epigenetics        |-            |85     |- |
  |fasta              |668          |-      |- |
  |fastq              |186          |-      |- |
  |gene               |-            |178    |- |
  |genbank            |41           |-      |- |
  |genetics           |223          |2090   |190 |
  |genome             |155          |105    |- |
  |gff                |14           |-      |- |
  |gwas               |-            |-      |25 |
  |human-genetics     |-            |395    |- |
  |human-genome       |-            |86     |- |
  |intermine          |6            |-      |- |
  |molecular-genetics |-            |557    |- |
  |microarray         |-            |-      |51 |
  |mutation           |-            |245    |- |
  |ncbi               |152          |24     |- |
  |phylogeny          |281          |-      |36 |
  |protein-database   |104          |-      |- |
  |population genetics|-            |306    |- |
  |pubmed             |151          |-      |- |
  |pymol              |80           |7      |- |
  |r-ape              |5            |-      |- |
  |rentrez            |22           |-      |- |
  |rna-seq            |83           |111    |- |
  |samtools           |68           |-      |- |
  |sequence-alignment |103          |76     |- |
  |sequencing         |101          |-      |- |
  |sequence-analysis  |-            |115    |- |
  |seurat             |58           |-      |- |
  |skbio              |32           |-      |- |
  |snp                |-            |89     |- |
  |statistics         |-            |163    |- |


