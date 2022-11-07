# Shortcomings of AlphaFold
Protein folding problem
- deemed intractable since degrees of freedom in peptide bonds create very high number of possibilities
- sequential sampling would take longer than the age of the universe, even for small protein domain.  
Alphafold
- alphafold relies primarily on co-evolution 
- if two residues are close in space and interact with each other, even if they’re far apart in the amino acid sequence, they’ll stick together during evolution to preserve structure and function
- does poorly on natively unfolded regions or sequences where there are less sequences available for alignment
- gives indication of dynamic movement between the domains.  
Limitations
- metal ions, cofactors, other ligands
- post-translational modifications (glycosylation, phosphorylation, DNA/RNA/complexes) 
- but it does correctly predict HGB chain – demonstrates that it has learned results of folding at the AA residue contact level
- only predicts a single state of a protein
