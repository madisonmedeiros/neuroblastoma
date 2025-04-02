# RV-EXCALIBER Steps

These are the scripts that were run to find rare variants in neuroblastoma patients. Most of these files have been edited in some way, so they are not fully identical to the ones found on the RV-EXCALIBER GitHub. Here, I outline a basic rundown of each script's function.

## STEP 0 Get ANNOVAR annotations

This script was used to download the refGene, gnomAD 211, and dbNSFP databases to ANNOVAR's /humandb directory
- refGene: Database that provides gene-based annotations
- gnomAD 2.1.1: Population frequency information
- dbNSFP: Functional Predications

## STEP 1 Get Burden Matrix for Testing Dataset

This script generates a rare variant burden matrix for the testing dataset

## STEP 2 Get Burden Matrix for gnomAD

This script generates a rare variant burden matrix for gnomAD that corresponds to the testing dataset

## STEP 3 Get Summary Associations

This script takes in variant counts in cases and controls and applies iCF and gCF correction to these counts along with generate a p-value 
