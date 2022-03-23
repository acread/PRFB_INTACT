# INTACT -  isolation of nuclei from tagged specific cell types

### The basics 
Not all plant cells experience the same stress(es) during infection, however most existing techniques for nucleic acid isolation \
use whole tissue homegenate (even if this is isolated to specific regions/hole punches it is collecting a mix of cells) \
By generating different stress-specific promoter fusions I will be able to pull down nuclei from cells experiencing stress(es) \
I believe this will boost the signal:noise ratio and allow me to get a better idea of changes in gene expression and DNA methylation

![image](https://user-images.githubusercontent.com/43852873/159764793-c9c92c0f-bb1a-4052-a83f-50b0e7f51993.png)

### Caveats and a small risk in the strategy
Caveat - this is a nuclear sorting strategy.  Any RNA in the cytoplasm will be lost.  There are conflicting reports about the \
correlation between nuclear and total mRNA abundances/ratios

Small risk - The initial INTACT systems all require transformation with two plasmids, 1 that has an ecoli biotin ligase and a \
2nd that encodes a nuclear tether, GFP, and a biotin acceptor peptide.  The biotin acceptor peptide is biotinylated in planta \
and these biotinylated nuclei are pulled down with streptavidin beads. \
I am trying to simplify the system by omitting the first plasmid and getting rid of the biotin acceptor peptide and using \
magnetic anti-GFP beads to pull down nuclei.  I should be able to tell pretty quickly if this is going to work or if I'm going \
to need to go back to the more complex system.


### Rough draft of strategy
1.  WIP domain amplified from genomic Setaria viridis DNA \
    Cloned in-frame downstream of GFP in pMOD_A3001 to generate pMOD_A3001_WIP\
    This plasmid was full-length sequenced and looks solid*
                     *it would have been nice to swap out 35s in this plasmid, but several of the promoters I'm interested \
                     in have internal AarI sites, so I'm generating the full t-dna before promoter swapping
                     
1.  It is probably a good idea to confirm that I'm able to pull down nuclei with anti-GFP at this point -- I can express \
     35s-GFP-WIP in protoplasts, run over column, and visualize how much of the green nuclei get captured...
     
2.  Combine pMOD_A3001_WIP + pMOD_B0000 + pMOD_C0000 + pTRANS_250d to generate a full-length t-dna plasmid
                     Note: It is possible to create some fun B and C modules to make combined reporters or do other tricks

3.  Swap promoters - I'll do an inverse PCR flanking the 35s promoter to get a solid cloning backbone and then amplify \
    various promoters of interest with overlaps homologous to the inverse PCR product and boom bam blue.
 
