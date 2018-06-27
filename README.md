# RDKit_chemicals_curator
use python rdkit module to curate data
the salts_typical.csv contains isomeric canonical SMILES codes for
typical organic and inorganic salts(actually due parent compounds).
These SMILES and fields in this data frame could help to initialize a RDKit SaltRemover
(see rdkit.Chem.SaltRemover doc for details)
