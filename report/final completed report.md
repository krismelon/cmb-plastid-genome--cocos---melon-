## Cell & Molecular Biology Lab Activity: Characterization of a Plastid Genome Cell and Molecular Biology

**Name:** Melon, Kris Bernadette S.

**Course:** BIO300- Cell and Molecular Biology 

**Section:** B

## 1. Purpose

In this activity, you will choose a plant genus with a complete plastid genome, obtain its chloroplast genome from a public database, upload it to your usegalaxy.org account 
for analysis, examine its sequence and genes, and record the results in a GitHub repository.

## 2. Learning Outcomes

* Locate and verify a complete plastid/chloroplast genome in NCBI. 

* Explain basic plastid-genome terms such as LSC, SSC, IR, CDS, rRNA, tRNA, intron, pseudogene,and GC content. 

* Describe the overall organization and gene content of a selected plastid genome.

* Use Galaxy to upload a plastid genome and obtain basic sequence statistics.

* Compare plastid genomes with mitochondrial and nuclear genomes.

* Evaluate practical advantages and limitations of plastid genomes in biological studies.

* Document the data source, analysis steps, results, and interpretation in GitHub.

## 3. Choosing and Recording a Plant Genus

_Cocos_

<img width="750" height="227" alt="image" src="https://github.com/user-attachments/assets/1cc21a88-d814-4da1-9f01-63442dec63fc" />

_**Figure 1.**_ NCBI record showing the complete circular chloroplast genome of Cocos nucifera with accession NC_022417.1 and a genome size of 154,731 bp.

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
| NCBI record            | [https://www.ncbi.nlm.nih.gov/nuccore/NC_022417.1](https://www.ncbi.nlm.nih.gov/nuccore/NC_022417.1)                         |

<img width="738" height="852" alt="image" src="https://github.com/user-attachments/assets/4def8c72-1236-4f7c-aaa8-20335d0a0cd8" />

_**Figure 2.**_ NCBI FASTA record showing the complete chloroplast genome sequence of Cocos nucifera with accession NC_022417.

## 5. Files to Obtain

| **File**           | **Format**                   | **Purpose**                                             | **File/Accession**                                                                |
| ------------------ | ---------------------------- | ------------------------------------------------------- | --------------------------------------------------------------------------------- |
| Genome sequence    | FASTA                        | Used for Galaxy analysis and sequence statistics        | *Cocos nucifera* chloroplast genome, NC_022417.1                                  |
| Annotated genome   | GenBank / RefSeq             | Used to examine genes and other genome features         | *Cocos nucifera* chloroplast genome, NC_022417.1                                  |
| Source information | NCBI record link / accession | Used to record the database source and accession number |  NC_022417.1 — [NCBI Record](https://www.ncbi.nlm.nih.gov/nuccore/NC_022417.1)    |

## 6. Galaxy Workflow

| **Statistic**                                     | **Result**     |
| ------------------------------------------------- | -------------- |
| **Genome length**                                 | 154,731 bp     |
| **Number of sequence records**                    | 1              |
| **GC content**                                    | 37.44%         |
| **Complete plastome represented by one sequence** | Yes            |

<img width="1917" height="867" alt="Screenshot 2026-09-30 083150" src="https://github.com/user-attachments/assets/3970a5e8-5200-43ba-ad81-456cc20ab554" />

_**Figure 3.**_ Galaxy workflow of the Cocos nucifera chloroplast genome using FASTA Statistics. The FASTA file (NC_022417.1) was analyzed to determine the genome size, nucleotide composition, 
and GC content.

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

## Gene Groups Identified

| **Gene group** | **Examples / what to look for**           | **Main function**                                                                 |
| -------------- | ----------------------------------------- | --------------------------------------------------------------------------------- |
| **psa**        | *psaA, psaB, psaC, psaI, psaJ*            | Help carry out the functions of Photosystem I during photosynthesis.              |
| **psb**        | *psbA, psbB, psbC, psbD, psbE, psbF*      | Help carry out the functions of Photosystem II during photosynthesis.             |
| **atp**        | *atpA, atpB, atpE, atpF, atpH, atpI*      | Help form ATP synthase, which is responsible for ATP production.                  |
| **pet**        | *petA, petB, petD, petG, petL, petN*      | Help with electron transfer through the cytochrome b6f complex.                   |
| **rbcL**       | *rbcL*                                    | Produces the large subunit of RuBisCO used in carbon fixation.                    |
| **rpo**        | *rpoA, rpoB, rpoC1, rpoC2*                | Provide parts of RNA polymerase needed for gene transcription.                    |
| **rpl**        | *rpl2, rpl14, rpl16, rpl20, rpl22, rpl23* | Produce proteins that make up the large ribosomal subunit.                        |
| **rps**        | *rps12, rps14, rps16, rps18, rps19*       | Produce proteins that make up the small ribosomal subunit.                        |
| **rrn**        | *rrn4.5, rrn5, rrn16, rrn23*              | Produce ribosomal RNA needed for ribosome formation.                              |
| **trn**        | *trnA, trnC, trnD, trnE, trnF*            | Produce tRNA that helps deliver amino acids during protein production.            |
| **matK**       | *matK*                                    | Helps process RNA within the chloroplast.                                         |
| **clpP**       | *clpP*                                    | Helps break down and process proteins through a protease complex.                 |
| **accD**       | *accD*                                    | Plays a role in the production of fatty acids.                                    |
| **cemA**       | *cemA*                                    | Associated with the chloroplast envelope membrane.                                |
| **ycf**        | *ycf1, ycf2, ycf3, ycf4, ycf15*           | Includes conserved chloroplast genes with different or not fully known functions. |

<img width="743" height="850" alt="Screenshot 2026-09-30 080231" src="https://github.com/user-attachments/assets/268a1660-6762-4e4e-89ad-9ccec1c665f0" />

_**Figure 4.**_ NCBI RefSeq record used for the plastid genome characterization of Cocos nucifera, showing the complete chloroplast genome accession NC_022417.1, 
genome size of 154,731 bp, and circular topology. The record was used to obtain information needed for the characterization, including genome size, topology, and 
annotated genomic features.

## 9. Questions for the Student Report

**1. Give the full scientific name, family, NCBI accession/version, database source, and complete plastid-genome size of your selected organism.**
   
The organism I selected is _Cocos nucifera_ (coconut), which belongs to the family Arecaceae. Its complete chloroplast genome is recorded in the NCBI
RefSeq/Nucleotide database under accession NC_022417.1 and has a total length of 154,731 bp. The genome is reported as circular DNA.

**2. What evidence shows that the sequence is a complete plastid/chloroplast genome rather than a barcode marker, genome fragment, or nuclear sequence?**

The NCBI record is specifically identified as “Cocos nucifera chloroplast, complete genome” and has the RefSeq accession NC_022417.1. It is 154,731 bp long and 
contains annotated chloroplast genes and genomic features, rather than being only a barcode gene such as rbcL or matK. The Galaxy analysis also showed one sequence 
record with no missing bases, supporting that the uploaded FASTA represents the complete plastome.

**3. Describe the overall organization of the plastid genome. Does it contain the common LSC-IR-SSC-IR arrangement? Give the sizes of these regions when available.**

The _Cocos nucifera_ chloroplast genome has the common LSC–IR–SSC–IR arrangement. The LSC region is 84,230 bp, the SSC region is 17,391 bp, and the two IR regions are 
26,555 bp each (53,110 bp combined). The complete genome is 154,731 bp and has a circular structure.

**4. Summarize the annotated gene content: total genes, protein-coding genes, tRNA genes, rRNA genes, and pseudogenes. Explain why genes located in the inverted-repeat 
regions may appear in two copies.**

The *Cocos nucifera* chloroplast genome contains 130 genes, including 84 protein-coding genes, 38 tRNA genes, and 8 rRNA genes, along with 4 pseudogenes. 
The pseudogenes include pseudo-*ycf1*, *rps19*, and two copies of *ycf15*. Genes located in the inverted-repeat (IR) regions may appear in two copies because the IR 
regions are repeated twice in the chloroplast genome. 

**5. Choose at least eight protein-coding plastid genes from different functional groups. List eachgeneand briefly explain its biological function.**

| **Gene** | **Functional group** | **Main function**                                              |
| -------- | -------------------- | -------------------------------------------------------------- |
| *psaA*   | Photosystem I        | Helps form Photosystem I and supports photosynthesis.          |
| *psbA*   | Photosystem II       | Encodes a major component of Photosystem II.                   |
| *atpA*   | ATP synthase         | Helps produce ATP used as cellular energy.                     |
| *petA*   | Cytochrome b6f       | Participates in electron transport during photosynthesis.      |
| *rbcL*   | Carbon fixation      | Encodes the large subunit of RuBisCO for carbon fixation.      |
| *rpoB*   | RNA polymerase       | Helps with transcription of genetic information.               |
| *rps12*  | Ribosomal protein    | Encodes a protein that is part of the small ribosomal subunit. |
| *matK*   | RNA processing       | Encodes a maturase involved in RNA processing.                 |

**6. Identify important RNA and RNA-processing features. Include the rRNA genes, examples of tRNA genes, and at least two genes with introns if present in your genome.**

The genome contains 8 rRNA genes: rrn16, rrn23, rrn4.5, and rrn5, with these genes occurring in the IR regions. It also contains 38 tRNA genes, which help provide tRNAs 
needed for protein synthesis.

**7. Describe any pseudogenes, gene losses, duplications, rearrangements, or other unusual features reported for your plastid genome. If none are reported, state this clearly.**

The genome contains **four reported pseudogenes**: pseudo-*ycf1*, *rps19*, and two copies of *ycf15*. Several genes are duplicated in the IR regions, including *ycf2, ndhB,* 
and *rps7*, as well as some rRNA and tRNA genes. The study also identified four overlapping gene pairs and found no significant recombination among the coconut chloroplast 
genomes examined.

**8. What is the GC content of your plastid genome? Based on your Galaxy results and annotation, describe two other notable sequence or structural observations.**

The Cocos nucifera chloroplast genome has a GC content of 37.44%, based on the Galaxy analysis. It contains one sequence record, with a genome length of 154,731 bp. 
The genome also shows an AT bias, especially at the third positions of codons.

**9. Compare plastid and mitochondrial genomes. Give at least five similarities and five differences, considering location, biological role, inheritance, genome organization, gene content, copy number, and evolutionary behavior.**

| **Feature**               | **Plastid Genome**                                                                                 | **Mitochondrial Genome**                                                          |
| ------------------------- | -------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| **Location**              | Found inside chloroplasts or other plastids.                                                       | Found inside mitochondria.                                                        |
| **Main biological role**  | Mainly involved in photosynthesis and other plastid functions.                                     | Mainly involved in cellular respiration and energy production.                    |
| **Genome organization**   | Usually has LSC, SSC, and two IR regions in plants.                                                | More variable in structure and organization.                                      |
| **Gene content**          | Contains genes related to photosynthesis, transcription, translation, and other plastid functions. | Contains genes mainly related to respiration and mitochondrial functions.         |
| **Inheritance**           | Often inherited from one parent, commonly the maternal parent in plants, but exceptions exist.     | Often inherited from one parent, but the pattern can vary.                        |
| **Copy number**           | Can have multiple copies within chloroplasts.                                                      | Can have multiple copies within mitochondria.                                     |
| **Evolutionary behavior** | Can undergo gene loss, gene transfer, and rearrangements.                                          | Can also undergo gene loss, gene transfer, recombination, and structural changes. |
| **Genome size**           | Usually relatively compact in plants.                                                              | More variable in size and structure.                                              |

**Similarities**

1. Both are organelle genomes.
  
2. Both contain their own DNA.
   
3. Both can occur in multiple copies per cell.
   
4. Both contain genes needed for their organelle functions.
   
5. Both originated from bacterial ancestors.

**Differences**

1. Plastid genomes are found in plastids, while mitochondrial genomes are found in mitochondria.
   
2. Plastids are mainly associated with photosynthesis, while mitochondria are mainly associated with cellular respiration.
   
3. Plastid genomes contain genes related to photosynthesis, while mitochondrial genomes contain genes mainly related to respiration.
   
4. Plant plastid genomes commonly have LSC, SSC, and IR regions, while mitochondrial genomes have more variable organization.
   
5. Their patterns of inheritance and evolutionary changes can differ.


**10. Explain the practical value of plastid genomes in research. List as many advantages as youcancompared with the nuclear genome, 
including nuclear sex chromosomes where applicable, andalsoexplain important limitations. Give one research question for which plastid 
data would be useful andone for which nuclear genomic data would be more appropriate.**

Plastid genomes are useful in many areas of plant research. They are relatively small compared with nuclear genomes and contain many 
genes and regions that can be used for studying and comparing plants.

**Advantages of Plastid Genomes**

* Study plant evolution
* Identify plant species
* Study genetic relationships
* Study chloroplast functions
* Smaller than nuclear genomes
* More organized structure
* Easier to analyze for some research questions

**Limitations**

plastid genomes have limitations because they contain fewer genes than nuclear genomes and mainly represent the evolutionary history 
of the plastid rather than the entire plant genome.

**Research Questions**

_**How are different coconut populations or varieties related based on their chloroplast genomes?**_

Plastid genomes would be useful because conserved regions can be compared between different coconut populations or varieties to study their evolutionary relationships.

_**Which genetic variants are associated with important traits in Cocos nucifera?**_

Nuclear genomic data would be more appropriate because important traits can involve many genes located throughout the nuclear genome.

## 10. 10. Plastid vs Mitochondrial Genome Comparison

| **Feature**                           | **Plastid genome (*Cocos nucifera*)**                                                                       | **Mitochondrial genome (*Cocos nucifera*)**                                                       |
| ------------------------------------- | ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| **Cellular location**                 | Found inside the chloroplasts.                                                                              | Found inside the mitochondria.                                                                    |
| **Main biological functions**         | Mainly involved in photosynthesis and other chloroplast functions.                                          | Mainly involved in cellular respiration and energy production.                                    |
| **Typical genome organization**       | Has the typical LSC–IR–SSC–IR structure.                                                                    | Has a more variable genome organization.                                                          |
| **Relative genome size**              | About 154,731 bp.                                                                                           | Much larger, about **678,653 bp**.                                                                |
| **Gene content**                      | Contains genes for photosynthesis, transcription, translation, and other chloroplast functions.             | Contains genes mainly associated with respiration and mitochondrial functions.                    |
| **Copy number**                       | Multiple copies can occur within chloroplasts.                                                              | Multiple copies can occur within mitochondria.                                                    |
| **Inheritance**                       | Usually inherited from one parent in plants, commonly the maternal parent, but exceptions exist.            | Often inherited from one parent, but inheritance can vary among plants.                           |
| **Recombination / structural change** | Generally more conserved, although gene loss, transfer, and rearrangements can occur.                       | More structurally variable and can undergo recombination and other structural changes.            |
| **Mutation / substitution pattern**   | Generally more conserved and can show relatively low substitution rates.                                    | More variable and can have different mutation patterns depending on the plant lineage.            |
| **Common research applications**      | Useful for studying coconut evolution, species identification, and relationships among coconut populations. | Useful for studying mitochondrial evolution, respiration-related genes, and maternal inheritance. |

## References

NCBI Nucleotide: https://www.ncbi.nlm.nih.gov/nuccore/NC_022417.1?report=fasta

NCBI GenBank: https://www.ncbi.nlm.nih.gov/nuccore/NC_022417.1?report=genbank

usegalaxy.org: https://usegalaxy.org/u/krismelon/h/plastid-cocos-melon

Galaxy Training Network: https://usegalaxy.org/?tool_id=toolshed.g2.bx.psu.edu%2Frepos%2Fiuc%2Ffasta_stats%2Ffasta-stats%2F2.0&version=latest

GitHub: https://github.com/krismelon/cmb-plastid-genome--cocos---melon-

Huang, Y., Matzke, A. J. M., & Matzke, M. (2013). Complete Sequence and Comparative Analysis of the Chloroplast Genome of Coconut Palm (Cocos nucifera). PLoS ONE, 8(8), e74736. https://doi.org/10.1371/journal.pone.0074736
