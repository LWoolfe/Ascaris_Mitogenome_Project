This contains the code used for both the bioinformatic pipeline and figure generation for the publication "Scalable Reconstruction of Ascaris Mitogenomes from Whole-Genome Sequencing Data".   

ABSTRACT 
The genus Ascaris comprises a family of large parasitic roundworms, infecting over 700 million people globally and causing substantial economic losses in domestic swine. Despite its impact, large nuclear genomes pose challenges for population genomic analyses. Mitochondrial and selected nuclear markers have suggested host- and geography-associated clustering, but Ascaris species are morphologically indistinguishable and differ by <1% at the genetic level. Here, we present a bioinformatic pipeline for de novo assembly of the complete mitochondrial genome (mtDNA) from low-coverage whole-genome sequencing data, through the utilisation of depleting host reads or enriching mtDNA reads, followed by mtDNA-specific genome assembly.
Our approach yielded 154 high-quality Ascaris mtDNA assemblies and enabled the  study of population-level diversity, including the identification of a previously undescribed clade (Clade D) associated with human samples from Ethiopia, extending the current classification beyond Clades A–C. We also found further evidence that Clade C comprises pig-derived samples from Europe, from those collected in Germany. Furthermore, genetic diversity across all mitochondrial loci was high (concatenated dataset: S = 1261; h = 94; π = 0.0224), indicating substantial intraspecific variation. The methods described provide a scalable framework for mitochondrial genome reconstruction and downstream applications in nematode phylogenetic and population-genomic studies  

A) Bioinformatic Processing: 
1. Initial Processing
2. Host decontamination with bowtie2
3. Host decontamination with deacon
4. mtDNA enrichment with deacon
5. Assembly with mitoZ and annotation with MITOS2

A) Data analysis using R: 
1. Alluvial Plot
2. Tree_analysis
3. Clade heatmap
4. Tanglegram 
