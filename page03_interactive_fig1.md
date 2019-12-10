---
layout: page
title: Interactive Figure 1
permalink: interactive_a
sidebar: true
interactive: main_interactive_fig.html
---
---

## Figure Description
Below is an interactive figure that displays the information footprint
for each gene and each growth condition ran in this experiment. The gene
and growth condition are chosen using the drop down boxes on the left. The
gene regulatory architecture, with identified transcription factors, and their
DNA-protein energy matrix for each transcription factor is displayed below
the information footprint. 

The regulatory cartoons are meant to be coarse grained representations of the
regulation. For example, an activator upstream of an RNAP in the regulatory
cartoon indicates an activator upstream of an RNAP site in the wild-type gene,
but the exact distance between the RNAP site and the cartoon is not significant.

The maximum information value for the y-axis displayed in the figure is set by the 
maximum value of the 95 percent confidence intervals for the information values
 for any of the displayed base pairs for the gene and growth condition combination.
 If the dataset for the gene and growth condition are unavailable then no
information footprint will be displayed. If a repressor or activator cartoon are
displayed without a protein name, then the identity of the binding site is
unknown.

<!-- The below line includes the interactive figure. Do not change! -->
<center>

{% include_relative interactives/{{page.interactive}} %}

</center>


























