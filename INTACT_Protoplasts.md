### Before I move into transgenic plants I need to confirm that the simplified INTACT system that I am planning to use (GFP pull-down) will work. The easiest way to test this is in protoplasts.

### Initial test strategy - 35s:GFP_WIP
Probably the simplest method to test the purification is by mixing pools of protoplasts transformed with our 35s:GFP_WIP construct and \
untransformed protoplasts.  We can mix the two pools of protoplasts at various ratios, extract nuclei, and run over our GFP capture beads. \
Various methods can be used to determine how many GFP nuclei are by-passing the capture and how many non-GFP nuclei are being captured \
The easiest of which is simple confocal or epifluorescence microscopy.  If we need finer resolution we can isolate RNA and do an RT-PCR.

### First expression/localization test of 35s:GFP_WIP in Setaria protoplasts
Jitesh isolated protoplasts and transformed with my 35s:GFP_WIP construct - a 35s:GFP construct was also transformed to compare to. \
I imaged the protoplasts 24 hours after transformation on the Voytas/Zhang epi-scope - it looks like transformation efficiency may have \
been a little lower for 35s:GFP_WIP than 35s:GFP, but localization looks good (see image below - I also observed many more examples of \
what appeared to be nuclear foci when scanning the sample). I did try to image at 48 hours on a scope on the 7th floor, but could not \
figure out how to get it to work.... 
<p align="center">
  <img src="https://user-images.githubusercontent.com/43852873/163430712-704e3bb4-b6fe-4621-beee-c48a979d1167.png" width = "400" >
</p>
  
### Second round expression/localization in maize protoplasts
The same construct was transformed into maize protoplasts by Zach Myers. A free-GFP control was not included. I was able to image these \
(briefly) on the higher power scopes in the imaging core. Due to limited time available on the scope I was not able to get many images, \
but it does look like we are seeing strong GFP signal at/near the nuclear membrane (see image).  The next time I do this I am hoping to: \
1.  Have more time at the scope, and 
2.  Try the magnetic bead pull down to isolate green nuclei

### A protocol for nuclei isolation from protoplasts
doi: 10.1093/abbs/gmz079 -- Acta Biochem Biophys Sin 2019

A total of 2 μl of 20 mM Tris-HCl (pH 7.5), containing 25%
Glycerol, 2.5 mM MgCl2, and 0.2% (v/v) Triton X-100 was
added to the protoplast, and the nuclei was re-suspended by
pipetting. The mixture was incubated for 10 min on ice to lyse
the chloroplasts before centrifugation at 3500 g for 10 min at
4◦C. This procedure was repeated twice. The supernatant was
discarded, and 2 ml of 20 mM Tris-HCl (pH 7.5), containing
25% Glycerol and 2.5 mM MgCl2, was added to the protoplast.
The nuclei were re-suspended by pipetting. The samples were
centrifuged at 3500 g at 4◦C for 10 min [2]. The purpose of this
step was to remove the Triton X-100. Mild detergents such as
Triton X-100 can be used for the isolation of nuclei as they can
disrupt the plasma membrane while having little effect on the
nuclear membrane if used under optimized concentrations and
incubation time. The chloroplasts are dispersed by the neutral
detergent Triton X-100 that is based on the selective dissolution
of the cytoplasmic membrane (not the nuclear membrane) [3].
One potential drawback is that higher concentrations of detergents or longer incubation time can lead to nuclear membrane
damage [4]. So 0.2% (v/v) Triton X-100 and an incubation time
of 10 min were used. Triton X-100 was stored as a 30% percent
w/v stock at 15◦C and diluted with isolation buffer.

### A protocol for INTACT nuclei extraction from plant tissue:
http://plant-plasticity.github.io/resources/INTACT-nuclei-purification.pdf

### It looks like anti-GFP magnetic beads should work well (though this use-case was with chloroplasts, which are smaller than nuclei....)
doi: 10.1111/j.1365-313X.2007.03113.x -- TPJ Truernit 2007

<p align="center">
  <img src="https://user-images.githubusercontent.com/43852873/165627663-5b1c2d2f-9e33-49b2-815e-ddb2bbc34299.png" width = "700" >
</p>
