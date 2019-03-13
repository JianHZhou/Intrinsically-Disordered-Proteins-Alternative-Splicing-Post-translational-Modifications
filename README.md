# IDP–AS–PTM hypothesis

Title: Intrinsically Disordered Proteins(IDPs) Link Alternative Splicing (AS) and Post-translational Modifications (PTMs) to Complex Cell Signaling and Regulation.

![GraphAbstract](https://user-images.githubusercontent.com/48297393/54318943-2689db80-45a5-11e9-9417-f330dcf6267f.png)

This project is to investigate the funcitonal role of intrinsically disordered proteins or regions in human signaling and regulatory proteins,
such as G protein-coupled receptors (GPCRs),transcription factors(TFs), Src family kinases(SFKs), and many others.

Protein Datasets(all from human):
1) 822 GPCRs
2) 1691 TFs
3) 9 SFKs

1. Predict the disorder/order on all these three protein families using PONDR-FIT. 
PONDR-FIT is a meta-predictor that uses a neural network to combine the normalized outputs of six different disorder predictors, namely,PONDR VLXT, PONDR VSL2, PONDR VL3, IUPred,FoldIndex and TopIDP. Overall, this meta-predictor
outperforms all of the individual predictors for nearly every protein and by an average of about 11%.
This predictor was accessed at:http://disorder.compbio.iupui.edu/meta predictor.php#PONDR-FIT. However, this link is no longer available.
Those who want to use this predictor can contact the author or use other predictors instead.

2. Identify all the AS events and PTMS for these three protein families.
 AS annotations are from UniProt. PTMs are from both UniProt and PhosphoSitePlus

3. Determine whether AS and PTMs are more likely to occur within disordered regions, and whether AS would further modify PTMs
