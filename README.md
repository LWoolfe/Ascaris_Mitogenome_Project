This contains the code used for both the bioinformatic pipeline and figure generation for the publication "Scalable Assembly of Ascaris Mitogenomes from Whole-Genome Data Reveals a Novel Clade".   

ABSTRACT 
The genus Ascaris is an important group of giant parasitic roundworms, infecting over 700 million people globally, with substantial economic losses in domestic pigs.  Whilst species of Ascaris are morphologically indistinguishable, analysis of mitochondrial and selected nuclear DNA loci has revealed three clades (A, B, C), which may inflate with the addition of genomic data. Here, we present a bioinformatic pipeline for de novo assembly of complete mitochondrial genomes (mtDNA) from low-coverage whole-genome data through host-read depletion or mtDNA read enrichment, followed by mtDNA-specific assembly.
Our approach yielded 149 high-quality Ascaris mtDNA assemblies, enabling the study of population-level diversity, including the identification of a novel clade (Clade D, designated here) associated with human samples from Ethiopia.  Our analysis further revealed Clade C to comprise of pig-derived samples from Europe based on characterisation of worms isolated in Germany. Furthermore, genetic diversity across all mitochondrial loci was high (concatenated dataset: S = 1261; h = 94; π = 0.0224), indicating substantial intraspecies variation. Our methods described here provide a scalable framework for mtDNA genome reconstruction with insights into roundworm  population-genomic and phylogenetic studies.

A) Bioinformatic Processing: 
1. Initial Processing
2. Using Deacon
3. Using Bowtie2/SqueezeMeta
5. Assembly with mitoZ and annotation with MITOS2

A) Data analysis using R: 
1. Alluvial Plot
2. Tree_analysis
3. Clade heatmap
4. Tanglegram
   
[lauren_mtDNA_commands_used.txt](https://github.com/user-attachments/files/24103144/lauren_mtDNA_commands_used.txt)
