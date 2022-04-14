## Biotroph/SA reporter construct

In my initial drafts of this proposal I suggest using Setaria PR1 gene promoters as biotrophic stress reporters - I still want to \
do this, but defining these promoters is a little tricky.

Bestuyaku et al 2018 created some really cool SA and JA reporter Arabidopsis lines, but they used a 4.5kb PR1 promoter... this is \
longer than I was hoping to use

A recent Brachypodium paper from Shimizu et al 2022 used a smaller fragment to make a luciferase reporter - 1.5 kb upstream from the \
start codon of BdPR1 (Bradi1g57580) (PR1P) was cloned and inserted in front of the Fluc reporter gene::NOST cassette

## Necrotroph/JA reporter construct

lj

## TALE reporter construct

Because I'm working with Xanthomonas I have a shot at using a TALE inducible promoter. \
Nathan is interested in using a TALE inducible promoter in protoplasts as part of the system validation.  This seems possible but will \
require co-transformation of a TALE encoding plasmid.  I'd really like a second reporter in this plasmid - something in the RFP/mCherry \
family to avoid pulling it down with the antiGFP beads.  This reporter could be a fusion to the TALE or a seperate protein product (I prefer \
the fusion).

### The Tal2g minimal promoter construct from Cernadas 2014
the AvrBs3-responsive 343 bp sequence upstream of the Bs3 start codon, using previously reported primers [70] and inserting it into the Gateway entry vector pCR8/TOPO-TA (Life Technologies). A single base substitution was then introduced by site directed mutagenesis (Agilent) to create an NcoI site 47 bp upstream of the native EBE for AvrBs3. Candidate Tal2g EBEs flanked upstream by 5 bp and downstream by 4 bp matching their native context were synthesized as double stranded oligonucleotides with NcoI overhangs (Text S1) and cloned into the NcoI site of the modified Bs3 promoter.

### A TALE that we know will work = Xoc Tal2g \
The Cernadas paper used an Agro co-transformation with a Tal2g expressing construct and a GUS construct driven by a minimal Bs3 promoter and a Tal2g EBE - they saw really good induction.  If I can get the Tal2g construct, it can be used directly, or modified to include a red reporter.  The minimal Bs3/Tal2g_EBE promoter can be cloned into my GFP_WIP reporter construct.
### It seems like it would be relatively straight-forward to synthesize this fragment to drop into my GFP_WIP construct


### A TALE that would be great to know about b/c it's conserved in Xtu

### TAL8 - has a role in virulence (ABA pathway)

### TAL7 - highly conserved and no highly unusual RVDs/Repeats (it does have a few 34aa repeats)

