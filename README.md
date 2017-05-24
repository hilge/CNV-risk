# CNV-risk: A database of published association results examining copy number variants and their effect on mental illness and cognition

## Shortly the database and application will be available here
If you want to be notified when this is please write to j.thygesen@ucl.ac.uk.

## Introduction 
Asides from a positive family history rare copy number variants (CNVs)
comprise the most severe risk factor for psychiatric illness. Data
from SNP-microarray technology has helped establish strong
associations between specific CNV loci and psychiatric illness,
cognitive and/or morphological features. CNVs are highly pleiotropic,
and yet cause impairment to specific cognitive domains (as well as
brain structures) in both affected and healthy carriers.

The literature describing CNV effects is growing, but there is
currently no central resource that compiles this knowledge in a
structured manner. The lack of a structure in complex information
creates barriers and prevents effective utilisation of this valuable
resource. Here we present a solution to this problem, through the
development of a structured database loaded with CNV association
results from the published literature.

## CNV-risk database 
We constructed a structured SQLite database schema to hold information
on; loci positions, association results, phenotypes, sample size, and
inter study relation. The data source is tables from published
articles which are loaded into the database via a function that
integrates overlapping loci. Along with the database we present a set
of interactive graphical visualisations using the R Shiny package to
help query CNV effects in an easy manner.

The database presented here allow researchers to perform efficient
meta-analysis, cross querying, and annotation of local data sets, in
addition we provide tools needed to upload additional data alongside
running database updates provided by our lab. This resource may be
valuable for researchers as well as clinical geneticists who seek to
compare their practice with the lasted published literature.


## Screen shots
### Database schema
![Database schema](/images/schema.png)

### CNV-list overview
![CNV-list overview](/images/cnv_lists.png)

### CNV-locus overview
![CNV-Locus overview](/images/locus_view.png)

### Compare CNV loci's
![Compare CNV loci](/images/loci_compare.png)

### Add data to database
![Add data](/images/add_data.png)

