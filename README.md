This is an assignment for BT5511 Advanced Biotechnology with Computation

You work for a small biotech start-up company 
that is searching for mutant genes that can help them 
to develop new therapeutics for their infectious 
disease target portfolio. 

They also have a side-interest in bioremediation, 
and so use a range of microbes and bioreactors 
to both develop and test drugs as well as mutant microbes. 

You are a bioinformatics consultant and have been asked 
by the company to help them analyse their latest mutation 
screening data to prioritise targets for them to focus on 
for experimental validation. 

Your task is to analyse the 25 data files, 
summarise the data contained therein, and present them 
in a report that will illustrate which genes and mutations 
the company should focus their efforts on. 

Each mutation experiment file will contain the following data in a tab-separated format: 

Gene name,
Wild-type gene DNA sequence including promoter and coding region,
Mutant DNA gene sequence including promoter and coding region,
Normalised cell viability – expressed as a percentage for the original and mutant gene in 3 replicates, 
Normalised mRNA expression level measured by qRT-PCR for the original and mutant gene in 3 replicates,
Normalised protein expression level measured by a protein array for the original and mutant gene in 3 replicates. 

The analysis will complete the following tasks: 

Aggregate data in all files into a single data object in Python 

Using the data provided, identify the top 5 genes and mutations 
to prioritise validation experiments.

Demonstrate that you have considered the type of mutation 
(substitution, insertion, deletion), effect of the mutations on cell viability,
promoter and coding sequences, as well as how the protein and mRNA expression
levels differ between wild-type and mutants. 

Plot the data to support your choice of the 5 genes. 
You can include up to 3 individual figures (a multi-panel graph counts as 1 figure), 
one of which should match the example graph provided 
(note the exact data points and variables need not be the same). 
