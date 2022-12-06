# Proteins and the Protein-Folding Problem
## What is a protein? 
Proteins are biomolecules made up of amino acids, the sequence of which determines the structure and function of each protein. In biological systems, proteins play complex and critical roles, and are largely responsible for structure, function, and regulation of a system’s tissues and organs. You have likely heard of enzymes which are catalysts for important chemical reactions--these are also proteins! A protein's function is determined by its structure which is why its shape, and being able to predict it is so important. 

## Orders of protein structure
### 1. Primary
Primary structure is the sequence of amino acids making up a polypeptide chain. 

Amino acids usually have the following structural properties:
- A carbon (the alpha carbon) bonded to the four groups below:
- A hydrogen atom (H)
- A Carboxyl group (-COOH)
- An Amino group (-NH2)
- A "R" group or "variable" group  

<img src="./docs/assets/primarystructure.png" alt="Primary Structure Image" width="400"/>

### 2. Secondary
Secondary structure is local folded structures that form within a polypeptide resulting from interactions between atoms of the backbone. The backbone refers to the polypeptide chain not including the R group.  

There are two types of secondary structures seen in proteins.
- alpha (α) helix - looks like a coiled spring
- beta (β) pleated sheet - looks like its folded or pleated 

<img src="./docs/assets/alpha_beta.jpeg" alt="Secondary Structures Image" width="400"/>

### 3. Tertiary
Tertiary structure results from interactions between the R groups of the amino acids that make up the protein. This is the overall three-dimensional structure of a polypeptide. 
- Non-covalent bonds influencing interactions:
  - hydrogen bonding
  - ionic bonding
  - dipole-dipole interactions
  - London dispersion forces 
  - Hydrogen bonding 
- Hydrophobic interactions
  - nonpolar, hydrophobic R groups cluster on inside of protein, while hydrophilic amino acids are on the outside interacting with surrounding water
- Covalent bond
  - Disulfide bond are covalent linkages between sulfur-containing side chains of cysteines
    - Stronger than the other types of bonds that contribute to tertiary structure

<img src="./docs/assets/tertiary.png" alt="Tertiary Structures Image" width="400"/>

### 4. Quaternary
While many proteins are made of a singular polypeptide chain and have three structural levels, some are made up of multiple chains or subunits. When the subunits come together, a protein gets its quaternary structure. The types of interactions that are part of tertiary structures are usually the same ones that hold subunits together that give proteins quaternary structure. This involves interactions such as London disperson forces and hydrogen bonding.  

## The Protein Folding Problem  
The protein-folding problem first emerged around 50 years ago, and consists of three general questions:
1. The folding code: what is the code that determines a protein's structure for a given amino acid sequence?
2. The folding mechanism: what is the process that allows proteins to fold quickly?
3. Protein structure prediction: can we formulate a computer algorithm to predict the native structure of a protein from its amino acid sequences?

The idea of a folding problem came up in 1960 with the first appearance of atomic-resolution protein structures. There had been some expectation of internal crystalline regularity, and Linus Pauling had predicted the presence of α-helices. However, the first protein structures to be realized were globins, and they unexpectedly had helices packed together irregularly. 

In his thermodynamic hypothesis, Anfinsen proposed that the native structure of a protein is in face the thermodynamically stable structure. With this, Anfinsen stated that the structure of a protein solely depends on the amino acid sequence and the conditions of the solution rather than the folding route. This led to two notable conclusions in protein science, as it 1) facilitated research of in vitro protein folding and 2) implied that evolution can alter amino acid sequences, but the folding equilibrium and kinetics of sequences are related to chemistry. 

In the 1980s, statistical mechanical modeling led to the emergence of a new view on the protein folding code in which the hydrophobic interaction is the dominant component. There are a number of points that justify this new theory: 1) proteins have hydrophobic cores, suggesting that nonpolar amino acids separate from water; 2) model compound studies show 1-2 kcal/mol for transferring a transferring a hydrophobic side chain from water to oil-like substances; 3) proteins easily denature in nonpolar solvents; and d) when sequences are scrambled and maintain the correct hydrophobic and polar patterns, they fold to the expected native structures.
