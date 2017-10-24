# vHIV
An HIV vaccine (preliminary). -- This version shows more clearly the symmetry between creating a glycosylated HIV neutralizing molecule (see aequorea/zHIV) and using designed-in glycans to create an epitope focused vaccine.
<p align="center">
  <img src="vHIV2.png" width="500"/>
</p>
<p align="center">
  vHIV (raspberry and red) shown bound to the zHIV N6 heavy chain fragment (blue)
</p>
<p align="center">
  Potential glycosylation sites selected by gly21 software on the gp120 monomer are shown in red.
</p>
<p align="center">
  (based on 5TE4.PDB -- DOI:10.1016/j.immuni.2016.10.027)
</p>
<p>
When I had the glycodesign software pick glycosylation sites on the N6 fragment, I did it with the fragment bound to gp120 to avoid glycosylating the binding pocket. Maybe a good way to make a vaccine would be to design glycans into gp120 instead. It's a method of "epitope focusing."
</p>
<p>
There is probably more to making a vaccine that would encourage antibodies that bind CD4 than just making vaccine molecules, injecting them, and then getting nice antibodies from a single vaccination. Broadly neutralizing antibodies targeting the CD4 binding site take time to develop. There is significant "affinity maturation" of the antibody binding site going on and this can take time. In an HIV patient it can take years for broadly neutralizing antibodies to arise. The question is, can we speed up this process?
</p>
<p>
HIV may already be telling us something about how to encourage the evolution of broadly neutralizing antibodies. The HIV early entrants, or "pioneers," have statistically fewer N-linked glycosylation sites and may have fewer glycans than HIV viruses that have been part of an infection for a while. Maybe this is part of the co-evolution of HIV with the antibodies that has been seen in cases where broadly neutralizing antibodies have arisen in the course of an HIV infection. To imitate this behavior we might like to see immunization as a series of vaccine molecules. In this series of molecules, start with fewer glycans and a more accessible CD4 binding site and progress to more glycans and a less accessible CD4 binding site. 
</p>
<p>
Another thing HIV does is vary the protein surface in areas that neighbor the CD4 binding site while leaving the binding site itself relatively constant. Since the antibodies are evolving to bind the area better, one imagines that it might be easier to improve the affinity to an area that is not changing. If the surface is changing, binding might initially improve, but when the surface changes, binding would likely drop to a lower efficiency. Thus binding to an area that doesn't change might continually improve, while binding to an area that changes might not. So it may also be important in the series of vaccine molecules to vary the protein surface in the vicinity of the desired binding site to better focus the antibody on it. This may improve binding specificity and breadth of neutralization.
</p>
<p>
So based on the behavior of HIV itself, we have a method of vaccine design that uses glycodesign based epitope focusing with variational sharpening. Use glycans to provide the "broad strokes" for focusing on the region of interest, and use variation of the protein surface in the immediate vicinity of the region to more sharply focus the antibodies on it.
</p>
