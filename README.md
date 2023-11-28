# Genomics and Epigenomics TD4

## Analysis of eukaryotic sequences

### Ensembl genome browser

An exome from a patient with a retinal disease has been analyzed. The sequence of a mutated exon (109 bp) is available on Moodle.

####  Mapping an exon sequence to the human genome

Open the BLAST/BLAT page. 

> :question: What is the difference between BLAST and BLAT?

> :question: Is BLAT relevant to map our transcript on the genome? 

Perform the search.

> :question: What is the localization of the exonic region (chromosome, strand)? What is the corresponding gene?

Display alignment.

> :question: Which variation(s) are observed on the patient exon compared to the reference genome?

#### GPR179 Gene

Select the gene.

**Isoforms (splice variants)**

> :question: How many protein coding transcripts are associated to this gene?

> :question: According to the flags of the transcript table, which transcript is the more reliable?

> :question: How many exons are present in this transcript?

**Protein: function, GO annotation, and expression **

In a new window, search for the protein encoded by this gene in SwissProt.

> :question: What is the protein function according to SwissProt?

> :question: GO annotations: look at the list of synonyms associated with the GO molecular function of the protein. Does standardization make sense in this case?

> :question: In which tissue is the gene expressed?
  
**Phenotype (Ensembl, Gene tab)**

> :question: Which phenotype(s) is linked to this gene? Is it consistent with the exome analysis?

#### Annotated genomic region

Display the GPR179 genomic region (region in details). Zoom out to have a good overview.

> :question: To which exon does the patient sequence correspond ?

**Gene prediction (ab initio + similarity)**

Configure this page (left panel) to display:
- Genes and transcripts / Prediction transcripts: Genscan predictions
- mRNA and protein alignments
  - mRNA alignments: display human cDNAs
  - protein alignments: display Proteins (mammals) from Uniprot

> :question: Compare information provided by Genscan (ab initio prediction), cDNA and protein alignments.

**Repeatitive elements**

Configure the page to display repeats (Repeat regions/All repeats) and conserved elements using Comparative genomics:
- Conservation regions/Constrained elements for eutherian mammals
- BLASTz/LASTz alignments with Chimpanzee, Mouse, crocodile, Zebrafish.
  
> :question: What is conserved in these different species?
> 
Retrieve the genomic region with 10000 bp 5’ and 3’ flanking sequence using Export data (fasta sequence, unmasked, text) or use the genomic region available on Moodle.

Analyze this sequence with [RepeatMasker](www.repeatmasker.org/) using default parameters (don’t hesitate to refresh the result page).

> :question: Which type of repeated element is the most represented in the genomic region?

> :question: Display the annotation output and have a look at the 1st Alu repeat in the list. Can you identify a typical feature in this Alu repeat?

> :question: To get a concrete idea of the importance of repetitive elements in the human genome, display the masked region.

**Regulation (Optional)**

> :question: According to regulatory features, can we have information about GPR179 promoter? How do you explain it?

> :question: Is it the same for the neighbor gene SOC7?

Display the same region in the UCSC genome browser (by following the hypertext link) and display CpG islands.

### Functional analysis of a gene list

Another patient with a retinal disease exhibits several mutations including a mutation in a gene of completely unknown function. We only know that this gene is co-expressed with other genes (list available on Moodle).

GO enrichment analysis

Use the website of the [Gene Ontology](http://www.geneontology.org/).

> :question: Perform a functional enrichment analysis (Biological process ontology) of this list of genes in comparison to human genes.

> :question: What is the meaning of the different columns in the result table?

> :question: Sort the results according to the P Value. Is the mutation a good candidate to explain the retinal disease of the patient?

**Network analysis with STRING **

Use the website of [String](https://string-db.org/).

Visualize the functional links between the genes in the list with STRING (using the “Multiple proteins” form).

> :question: Which main types of links are observed between the genes of this list?

> :question: Analyze the network (Analysis). Are there more links than expected in this list?

> :question: Is the STRING analysis in agreement with the previous one?