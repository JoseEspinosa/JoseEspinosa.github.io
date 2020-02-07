---
title: "Using the T-Coffee package to build multiple sequence alignments of protein, RNA, DNA sequences and 3D structures"
collection: publications
permalink: /publication/2011-10-06-tcoffee-nat-protocol
excerpt: ''
date: 2011-10-06
venue: 'Nature Protocol'
paperurl: 'https://www.nature.com/articles/nprot.2011.393'
citation: 'J. Taly, C. Magis, G. Bussotti, J. Chang, P. di Tommaso, I. Erb, J. Espinosa-Carrasco, C. Kemena, C. Notredame. 
Using the T-Coffee package to build multiple sequence alignments of protein, RNA, DNA sequences and 3D structures. 
Nat Protoc 6, 1669–1682 (2011),
DOI: 10.1038/nprot.2011.393
'

---
### Abstract

Authors: Jean-Francois Taly, Cedrik Magis, Giovanni Bussotti, Jia-Ming Chang, Paolo Di Tommaso, Ionas Erb, 
Jose Espinosa-Carrasco, Carsten Kemena, Cedric Notredame

T-Coffee (Tree-based consistency objective function for alignment evaluation) is a versatile multiple sequence 
alignment (MSA) method suitable for aligning most types of biological sequences. The main strength of T-Coffee is its 
ability to combine third party aligners and to integrate structural (or homology) information when building MSAs. The 
series of protocols presented here show how the package can be used to multiply align proteins, RNA and DNA sequences. 
The protein section shows how users can select the most suitable T-Coffee mode for their data set. Detailed protocols 
include T-Coffee, the default mode, M-Coffee, a meta version able to combine several third party aligners into one, PSI 
(position-specific iterated)-Coffee, the homology extended mode suitable for remote homologs and Expresso, the 
structure-based multiple aligner. We then also show how the T-RMSD (tree based on root mean square deviation) option 
can be used to produce a functionally informative structure-based clustering. RNA alignment procedures are described 
for using R-Coffee, a mode able to use predicted RNA secondary structures when aligning RNA sequences. DNA alignments 
are illustrated with Pro-Coffee, a multiple aligner specific of promoter regions. We also present some of the many 
reformatting utilities bundled with T-Coffee. The package is an open-source freeware available from 
http://www.tcoffee.org/.