Fastq files were analyzed according to the FLAM-seq analysis pipeline: reads were filtered for containing at least 10 As followed by 9 Gs (or the rev. comp.), then reoriented to start with the adapter sequence, the unique molecular identifier (UMI), the G tail and the poly(A) tail. Poly(A) tails were detected and removed, the remaining reads were aligned to hg38 or C. elegans WB235 genome assemblies using STARLong (Dobin et al., 2013). Each aligned read was then assigned to gene models (Ensembl GRCh38.84 for human, WBcel235_82 for worm) with FeatureCounts (Liao et al., 2014).
Genome_build: H. sapiens: hg38, C. elegans: WB235

Processed data contain read name, gene to which read is assigned using FeatureCounts, unique molecular identifier sequence, tail length and tail sequence
