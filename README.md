-------------------------------

Descriptoin of the project: 
--

The project aims to use Gillespie algorithm to simulate the Mitochondrial DNA Transcription. There are 37 mt-genes in human mitochondria DNA, and we will focus on the transcription of the 13 protein coding genes and the 2 rRNAs. 

Transcription of the genes can be initiated either on the light strand or on the heavy strand. On the light strand, it will only replicate one protein-coding gene (ND6). On the heavy strand, it starts from replicating the two rRNAs, and has a chance to terminate right after that; otherwise, it will continue to replicate all the remaining 12 protein-coding genes. 

Meanwhile, the gene transcripts have a chance to degrade at time. The quantity of transcripts of each gene is subject to exponential decay, where the explicit decay coefficient is unknown. In the simulation, we will assume decay coefficients for the transcripts, and use the algorithm to solve for the stable status. 

--------------------------------
