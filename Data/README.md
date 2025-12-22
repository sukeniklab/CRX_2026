# Data Folder
* ```AllConstructSeqs.csv``` - All sequences and labels for experimentally tested tiles
* ```CRX_fulllength_unified.csv``` - Contains rows for every mutation in James' DMS scan. Mutation, activity scores, sequence. Also contains ELM results for SLiMs
* ```CRX_tiledata_unified.csv``` - Data for all of our experimental tiles. Construct, sequence, Ef, localization, and calculated NARDINI and sparrow parameters. IMPORTANT: TILED, NOT FULL-LENGTH!
* ```RePred_Activity_merged.csv``` - For all of James' DMS scan mutants in the AD (~109 - 290) contains Re predictions based on the shifting window method. Also contains a duplicate of the activity scores for these mutants, which can also be found in CRX_fulllength_unified.csv
* ```StallerActivities.csv``` - Contains activities based on Max Staller's method (SEPARATE FROM DMS!) for TILES along the CRX sequence, matching with our experimental FRET tiles. Also contains associated sparrow parameters calculated from these tiles.
* ```cells_df.csv``` - The raw, concatenated dataset from all of our microscopy data. Each row is a single cell. Use for violin plots.
* ```clinvar_missense.csv``` - The most recent version of the clinvar dataset. Holds clinvar mutants and their associated data.