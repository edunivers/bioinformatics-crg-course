Basic Bioinformatics Course
========================
This is the self-learning contents compiled for the basics in bioinformatics course done at the Center for Genomics Regulation in 2018 (10 sessions, dedication: 1h per session).

## T01. Introduction to bioinformatics and data science
* Assignment 1: Read "So you want to be a computational biologist?" http://www.nature.com/nbt/journal/v31/n11/full/nbt.2740.html
* Assignment 2: Video "5 Questions Data Science Answers" https://www.youtube.com/watch?v=0XyV91VYrDs
* Assignment 3: Video "Is your data ready for data science?" https://www.youtube.com/watch?v=FVgJe4iDZ3Y
* Assignment 4: Video "Ask a question you can answer with data https://www.youtube.com/watch?v=nBoybSf7jwo

### Class activities
* Activity 1: Make groups and discuss what are their questions and how they are addressing them. Followed by class discussion on whether questions are clear enough and concrete enough.
* Activity 2: Discuss how they currently organize their data analysis projects. Followed by class discussion on pros and cons of the different approaches.

## T02. Setting up and managing a bioinformatics project
* Assignment 1: Read "Ten Simple Rules for Reproducible Computational Research" http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003285
* Assignment 2: Tutorial on GitHub http://mozillascience.github.io/working-open-workshop/github_for_collaboration/
* Assignment 3: Tutorial on R Markdown http://rmarkdown.rstudio.com/lesson-1.html
* Classwork: questions answers

### Class activities
* Activity 1: Make groups and discuss what are the differences on organization for data analysis projects with what they discussed last week, followed by a hands-on demonstration on setting up of a github project.
* Activity 2: Group discussion on how to access unix machines.

## T03. Interacting with machines I: Unix systems
* Assignment 1: Read "Linux took the web, now it is taking over the world" https://www.wired.com/2016/08/linux-took-web-now-taking-world/
* Assignment 2: Tutorial on "Survival Guide on Unix/Linux for newbies" http://matt.might.net/articles/basic-unix/
* Classwork: "Connection to a computational cluster, finding resources and sending jobs".
### Class activities
* Activity 1: Connect to https://bellard.org/jslinux/ and review commands (pwd, ls -la, mkdir, chmod, vi, cat, head)
* Activity 2:  Connect to the CRG cluster and send a job (qsub and qstat) R script.

## T04. Interacting with machines II: Data formats
* Assignment 1: Read "Computer friendly data file formats" http://opendatahandbook.org/guide/en/appendices/file-formats/
* Assignment 2: Read "What is XML?" https://www.w3schools.com/xml/xml_whatis.asp
* Assignment 3: Read "Best (worst) practices in excel for bioinformatics" https://michiel.wordpress.com/2009/04/05/10-worst-microsoft-excel-practices/
* Assignment 4: Read "How to import and export csv files in Excel" https://support.office.com/en-us/article/Import-or-export-text-txt-or-csv-files-5250ac4c-663c-47ce-937b-339e391393ba
* Assignment 5: Read "Most Frequent data formats in bioinformatics" http://bioinformatics.uconn.edu/resources-and-events/tutorials/file-formats-tutorial/
* Classwork: questions answers

### Class activities
* Activity 1: Discuss file formats: 1) binary vs plain, 2) extensions, 3) propietary vs interoperable/open (rwx GNU).
* Activity 2: Open XML file + Make a custom XML file of your field + git upload and public presentation + What are the XML standards in my field?

## T05. Introduction to basic programming
* Assignment 1: Learn the basics of programming with Python (12 brief lessons) https://www.learnpython.org/
* Assignment 2: Video The sorting algorithm 1: https://www.youtube.com/watch?v=YHm_4bVOe1s
* Classwork: questions answers
	
### Class activities
* Activity 1: Sort poker cards in teams and propose an algorithm (e.g. https://www.youtube.com/watch?v=k1XDkXWKMqU)
* Activity 2: Introduction to scratch with BubbleSort script (https://wiki.scratch.mit.edu/wiki/Sorting_Values)

## T06. Bioinformatics resources and databases
* Assignment 1: Video "NCBI Gene Database - Overview" https://www.youtube.com/watch?v=-dOQMiEtL8I
* Assignment 2: Video "Explore Gene Pages at NCBI: Variation & Expression" https://www.youtube.com/watch?v=E8-NPZTK7_w&pbjreload=10
* Assignment 3: Video "Introduction to UniprotKB" https://www.youtube.com/watch?v=ado1r8IDm3U
* Assignment 4: Video "Uniprot Entry View" https://www.youtube.com/watch?v=lHeqHpNaSis
* Assignment 5: Video "Uniprot Batch retrieval" https://www.youtube.com/watch?v=kLdgjqWoMZc
* Assignment 6: Video "Introduction to Uniprot Proteomes" https://www.youtube.com/watch?v=ZLt3ug0mZ7A
* Assignment 7: Video "PDB Protein Structure Database" https://www.youtube.com/watch?v=_ok64nYRiCY
* Classwork: questions answers
* Learn More with Additional Tutorials: https://www.youtube.com/user/NCBINLM/videos

## T07. Multiple sequence alignment, similarity searches, and pattern recognition
* Assignment 1: Read "Basic Local Alignment Search Tool" https://www.nature.com/scitable/topicpage/basic-local-alignment-search-tool-blast-29096
* Assignment 2: Video "How to perform a BLAST analysis" https://www.youtube.com/watch?v=HXEpBnUbAMo
* Assignment 3: Read "An overview of multiple sequence alignment." Simossis V, Kleinjung J, Heringa J. Curr Protoc Bioinformatics. 2003 Nov;Chapter 3:Unit 3.7. doi: 10.1002/0471250953.bi0307s03.
* Assignment 4: Read "Protein Multiple Sequence Alignment" Chuong B. Do and Kazutaka Katoh, Methods in Molecular Biology, vol. 484: Functional Proteomics: Methods and Protocols Edited by: J. D. Thompson et al., DOI: 10.1007/978-1-59745-398-1, 
* Assignment 5: Video Tutorial Clustal Omega https://www.youtube.com/watch?v=I90MJShsmmk

### Class activities
* Activity 1: Explanation of the scoring system for sequence alignment (gaps, mismatches, and matches). Revision of the BLOSUM62 and other scoring matrices.
* Activity 2: We review the NCBI database from last week and look for the gene "CAOG_00226 tyrosine-protein kinase Src42A" https://www.ncbi.nlm.nih.gov/gene/14901928 and then look for homologous genes in human using a protein-protein BLAST.
* Activity 3: Perform a multiple sequence alignment with the homologous gene found in four or five species.


## T08. Genome Assembly and ChIP-Seq
* Assignment 1: Video "Introduction to Genome Assembly" https://www.youtube.com/watch?v=jw146c9zRVo
* Assignment 2: Video "Introduction to ChIP-Seq" https://www.youtube.com/watch?v=zwuUveGgmS0
* Classwork: questions answers

## T09. Proteomics analyses
* Assignment 1: Read "Mass-spectrometric exploration of proteome structure and function." https://www.ncbi.nlm.nih.gov/pubmed/27629641
* Assignment 2: Read "Shedding light on black boxes in protein identification" https://www.ncbi.nlm.nih.gov/pubmed/24678044
* Assignment 3: Tutorial "Peptide and protein identification" https://compomics.com/bioinformatics-for-proteomics/identification/
* Classwork: questions answers

## T10. Integrative platforms: Galaxy
* Assignment 1: https://www.melbournebioinformatics.org.au/tutorials/tutorials/galaxy_101/galaxy_101/
* Classwork: questions and answers

## ... even more!
* MIT Full Course on "Foundations of Computational and Systems Biology" https://ocw.mit.edu/courses/biology/7-91j-foundations-of-computational-and-systems-biology-spring-2014/video-lectures/

