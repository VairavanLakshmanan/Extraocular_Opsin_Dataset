# Extraocular_Opsin_Dataset
Alignment files and phylogenetic tree  
These are the alignment files and phylogentic tree files that were analyzed & used in the manuscript entitled '***Discovery of a body-wide photosensory array that matures in an adult-like animal and mediates eye-brain independent movement and arousal***'.

<b>Phylogenetic analysis of opsins</b><br/>
In our previous work we mined the available planarian transcriptomes and identified 7 different opsin like sequences (Shettigar etal., 2017). Further filtering based on opsin sequence signature/motifs, we narrowed down to five unique planarian opsin sequences. To identify which class of opsin these ( five S.mediterranea Opsin) sequences fall into, we constructed a phylogenetic tree with already annotated nine opsin paralogs (792 animal opsin sequences), as described in Ramirez et al., 2016. We aligned the identified five planarian opsins with the opsin alignment file generated by Ramirez et al., 2016 along with additional 21 human GPCR sequences as an outgroup using MAFFT 7.3 (https://mafft.cbrc.jp/alignment/software/). We generated a phylogenetic tree using iqtree 1.5.5 (http://www.iqtree.org/) with 1000 bootstraps and single branch likelihood with 1000 replicates. Iqtree used Modelfinder to test for protein models (available 468 models) and using Bayesian-information criterion picked LG+F+R8 as best-fit model. The consensus log-likelihood tree was used for further analysis. We used FigTree v1.4.3 (http://tree.bio.ed.ac.uk/software/figtree/) to rearrange and represent the tree.


<b>Tools used</b><br/><br/>
MAFFT 7.3 (<a>https://mafft.cbrc.jp/alignment/software/</a>)<br/>
iqtree 1.5.5 (<a>http://www.iqtree.org/</a>)<br/>
FigTree v1.4.3 (<a>http://tree.bio.ed.ac.uk/software/figtree/</a>)<br/>

<b> Alignment Files </b><br/>
Shettigar et al_To_RUN_FINAL_Seqs_added_Smed_Alignment_to Ramirez et al.aln<br/>

<b> Tree Files </b><br/>
Shettigar et al_Seqs_added_Smed_Alignment_to Ramirez et al.aln.treefile<br/>
Shettigar et al_Seqs_added_Smed_Alignment_to Ramirez et al.aln.splits.nex<br/><br/>
<b> iqTree & consencus Tree file </b><br/><br/>
Shettigar et al_Seqs_added_Smed_Alignment_ to Ramirez et al.aln.iqtree<br/>
Shettigar et al_Seqs_added_Smed_Alignment_ to Ramirez et al.aln.contree<br/>

<b>Sequences used in the alignment files </b><br/><br/>
Ramirez_etal_2016_GBE_MAR23-15_90sim_opsin.aln
Planarian opsin sequences - Genbank accession: MW465947 - MW465950
