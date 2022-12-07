# Successes and Limitations of AlphaFold
Alphafold 2 has revolutionized the field of protein predictions, as demonstrated by de novo predictions for the 3D structures of human glucose-6-phosphatase, diacylglycerol-O-acetyltransferase 2, and the transmembrane ER protein wolframin. Previously, no predicted or experimentally validated structure was available for any of these structures. Ultimately, Alphafold 2 is revolutionary for monomeric proteins that have a single native structure and don't interact with other molecules in ways that impact their confomration.  
<p align="center">
  <img src="./docs/assets/g6p.png" alt="Glucose-6-Phosphate" width="900"/>
</p>  
<p align="center">
  Alphafold predicted structure for glucose-6-phosphatase. Taken from https://alphafold.ebi.ac.uk/entry/P35575.  
</p>
  
Despite its successes, Alphafold 2 is still lacking in a number of ways. Interactions with partner proteins and multimers are not available for prediction -- Alphafold Multimer was recently precented and aims to address this, but is still only most successful with homomeric proteins or heterodimeric proteins. In addition to struggling to predict multiunit proteins, Alphafold is unable to predict other aspects or components of protein structure, such as interactions with metal ions, cofactors, and other ligands or post-translational modifications such as glycosylation or phosphorylation. For natively unfolded regions or proteins with less data available for alignment, Alphafold is unable to produce appropriate structures.  

<p align="center">
  <img src="./docs/assets/prediction.webp" alt="Limitations" width="900"/>
</p>  
<p align="center">
  Alphafold Confidence Metrics for Different Proteins. Taken from https://www.nature.com/articles/d41586-022-00997-5#:~:text=AlphaFold%20deploys%20deep%2Dlearning%20neural,the%20PDB%20and%20other%20databases..  
</p>

Moving forward, Alphafold is anticipated to prsent even more opportunity regarding drug discovery, as drug development currently requires using structures throughout the process. The creators of Alphafold have acknowledged these shortcomings and it is almost certain that the algorithm will continue to improve over time. 

