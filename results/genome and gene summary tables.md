## 4. Data Source and Genome Selection

| **Item**               | **Information**                                                                                                              |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Chosen genus           | *Cocos*                                                                                                                      |
| Selected species       | *Cocos nucifera*                                                                                                             |
| Common name            | Coconut                                                                                                                      |
| Family                 | Arecaceae                                                                                                                    |
| Organelle              | Chloroplast (plastid)                                                                                                        |
| Genome type            | Complete chloroplast genome                                                                                                  |
| NCBI accession/version | NC_022417.1                                                                                                                  |
| Database               | NCBI RefSeq / Nucleotide                                                                                                     |
| Genome length          | 154,731 bp                                                                                                                   |
| Topology               | Circular                                                                                                                     |
| Sequence status        | Complete genome                                                                                                              |
| Source                 | NCBI Nucleotide / RefSeq                                                                                                     |
| Associated publication | Huang et al. (2013), *Complete Sequence and Comparative Analysis of the Chloroplast Genome of Coconut Palm (Cocos nucifera)* |
| NCBI record            | https://www.ncbi.nlm.nih.gov/nuccore/NC_022417.1                                                                             |

## 5. Files to Obtain

| **File**           | **Format**                   | **Purpose**                                             | **File/Accession**                                                                |
| ------------------ | ---------------------------- | ------------------------------------------------------- | --------------------------------------------------------------------------------- |
| Genome sequence    | FASTA                        | Used for Galaxy analysis and sequence statistics        | *Cocos nucifera* chloroplast genome, NC_022417.1                                  |
| Annotated genome   | GenBank / RefSeq             | Used to examine genes and other genome features         | *Cocos nucifera* chloroplast genome, NC_022417.1                                  |
| Source information | NCBI record link / accession | Used to record the database source and accession number |  NC_022417.1 — https://www.ncbi.nlm.nih.gov/nuccore/NC_022417.1                   |

## 6. Galaxy Workflow

| **Statistic**                                     | **Result**     |
| ------------------------------------------------- | -------------- |
| **Genome length**                                 | 154,731 bp     |
| **Number of sequence records**                    | 1              |
| **GC content**                                    | 37.44%         |
| **Complete plastome represented by one sequence** | Yes            |

## 7. Plastid Genome Terms to Understand

| Term                          | Meaning                                                                                           |
| ----------------------------- | ------------------------------------------------------------------------------------------------- |
| **Plastid genome / plastome** | The set of DNA found inside plastids, such as the chloroplasts of green plants.                   |
| **LSC**                       | The bigger single-copy section of the plastid genome.                                             |
| **SSC**                       | The smaller single-copy section of the plastid genome.                                            |
| **IR**                        | A repeated DNA section that appears twice in the plastid genome.                                  |
| **CDS**                       | A DNA sequence that contains the information needed to produce a protein.                         |
| **tRNA gene**                 | A gene that helps produce tRNA, which is involved in bringing amino acids for protein production. |
| **rRNA gene**                 | A gene that produces rRNA, which helps form ribosomes.                                            |
| **Intron**                    | A section of a gene that is removed before the RNA becomes ready for use.                         |
| **Pseudogene**                | A DNA sequence that looks like a gene but may not function properly anymore.                      |
| **GC content**                | The amount or percentage of guanine and cytosine bases in the DNA.                                |
| **Accession**                 | A unique code used to identify a sequence in a database.                                          |
| **Annotation**                | Details added to a genome sequence to show genes and other important parts.                       |

## 8. Required Plastid Genome Characterization

| **Characteristic**               | ***Cocos nucifera*** **chloroplast genome** |
| -------------------------------- | ------------------------------------------- |
| **Genus**                        | *Cocos*                                     |
| **Species**                      | *Cocos nucifera*                            |
| **Family**                       | Arecaceae                                   |
| **NCBI accession/version**       | NC_022417.1                                 |
| **Genome size**                  | 154,731 bp                                  |
| **GC content**                   | 37.44%                                      |
| **Topology**                     | Circular                                    |
| **LSC size**                     | 84,230 bp                                   |
| **SSC size**                     | 17,391 bp                                   |
| **IR size**                      | 26,555 bp each                              |
| **Number of sequence records**   | 1                                           |
| **Total annotated genes**        | 130 genes                                   |
| **Protein-coding genes**         | 84                                          |
| **tRNA genes**                   | 38                                          |
| **rRNA genes**                   | 8                                           |
| **Introns**                      | Present in some annotated genes             |
| **Pseudogenes / gene fragments** | 4 pseudogenes                               |
| **Gene duplications**            | Genes in the IR regions occur in two copies |
| **Overall organization**         | LSC–IR–SSC–IR                               |

**Gene Groups Identified**

| **Gene group** | **Examples / what to look for**           | **Main function**                                                                    |
| -------------- | ----------------------------------------- | ------------------------------------------------------------------------------------ |
| **psa**        | *psaA, psaB, psaC, psaI, psaJ*            | Involved in Photosystem I and photosynthesis.                                        |
| **psb**        | *psbA, psbB, psbC, psbD, psbE, psbF*      | Involved in Photosystem II and photosynthesis.                                       |
| **atp**        | *atpA, atpB, atpE, atpF, atpH, atpI*      | Encode components of ATP synthase, which helps produce ATP.                          |
| **pet**        | *petA, petB, petD, petG, petL, petN*      | Encode components of the cytochrome b6f complex involved in electron transport.      |
| **rbcL**       | *rbcL*                                    | Encodes the large subunit of RuBisCO, which is involved in carbon fixation.          |
| **rpo**        | *rpoA, rpoB, rpoC1, rpoC2*                | Encode RNA polymerase components used in transcription.                              |
| **rpl**        | *rpl2, rpl14, rpl16, rpl20, rpl22, rpl23* | Encode ribosomal proteins of the large ribosomal subunit.                            |
| **rps**        | *rps12, rps14, rps16, rps18, rps19*       | Encode ribosomal proteins of the small ribosomal subunit.                            |
| **rrn**        | *rrn4.5, rrn5, rrn16, rrn23*              | Encode ribosomal RNA.                                                                |
| **trn**        | *trnA, trnC, trnD, trnE, trnF*            | Encode transfer RNAs used during protein synthesis.                                  |
| **matK**       | *matK*                                    | Encodes a maturase involved in RNA processing.                                       |
| **clpP**       | *clpP*                                    | Encodes a component of a protease involved in protein processing/degradation.        |
| **accD**       | *accD*                                    | Involved in fatty-acid biosynthesis.                                                 |
| **cemA**       | *cemA*                                    | A conserved chloroplast envelope membrane-associated gene.                           |
| **ycf**        | *ycf1, ycf2, ycf3, ycf4, ycf15*           | Conserved chloroplast genes with various functions; some functions remain uncertain. |
