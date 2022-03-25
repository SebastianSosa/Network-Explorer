---
title: 'Network Explorer: an R package for live exploration of networks'
tags: 
  - R
  - Graph Theory
  - Network visualisation and exploration
authors: 
  - name: Sebastian Sosa
  - affiliation: "1"
affiliations:
  - name: Independent Researcher, France
  - index: 1
  date: "25/03/2022"
output: pdf_document
---

 
# Summary
Whether they are natural or artificial, complex systems (Thurner et al., 2018) ) (i.e. groups of interacting entities) are omnipresent at microscopic and macroscopic levels (e.g. Earth's global climate, organisms, the human brain, infrastructures such as power grids, transportation or communication systems, social and economic organizations (such as cities), ecosystems, animal societies, living cells…). However, exploration of complex systems can be difficult to explore due to the important number of variables that may locally affect connection patterns.

# Statement of need
Over the past 50 years, network analysis (Hanneman & Riddle, 2005a; Wasserman & Faust, 1994) has become an essential tool in the study of complex systems. In the study of animal sociality, network analysis has led to a foundational shift in our understanding of animal sociality that transcends the disciplinary boundaries of genetics, spatial movements, epidemiology, information transmission, evolution, species assemblages and conservation. However, the visualization and exploration of such complex systems can be difficult due to the important number of variables that may locally affect connection patterns. Network Explorer is based on 'd3js' library and allows to visualize and explore complex systems with:
1. A graphical user interface.
2. The possibility of customizing node size, node colour, node shape, node stroke colour, node stroke width. This way, it allows a data visualization through 5 axes.
3. Multiple layout possibilities: circular, linear, multilayer and force layout
4. Network live exploration
5. SVG exportation allowing high resolution images
A tutorial is available at : https://www.youtube.com/watch?v=IcFTZWCTO_s
In combination with other R packages focusing on network analysis such as igraph (Csardi & Nepusz, 2006; Sosa et al., 2020) and ANTs, Network Explorer offers an ecosystem allowing both the exploration and analysis of networks.

# References
- Csardi, G., & Nepusz, T. (2006). The igraph software package for complex network research. InterJournal, Complex Systems, 1695, 38.
- Hanneman, R. A., & Riddle, M. (2005). Introduction to social network methods. University of California Riverside.
- Sosa, S., Puga-Gonzalez, I., Hu, F., Pansanel, J., Xie, X., & Sueur, C. (2020). A multilevel statistical toolkit to study animal social networks: the Animal Network Toolkit Software (ANTs) R package. Scientific Reports, 10(1), 12507. https://doi.org/10.1038/s41598-020-69265-8
- Thurner, S., Hanel, R., & Klimek, P. (2018). Introduction to the theory of complex systems. Oxford University Press.
Wasserman, S., & Faust, K. (1994). Social network analysis: Methods and applications (Vol. 8). Cambridge university press.
