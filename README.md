# RDKit_chemicals_curator
Use python rdkit module to curate data. 

The salts_typical.csv contains isomeric canonical SMILES codes for
typical organic and inorganic salts(actually due parent compounds).

These SMILES and fields in this data frame could help to initialize a RDKit SaltRemover
(see rdkit.Chem.SaltRemover doc for details)
