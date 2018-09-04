# clausen_ribonucleotides

[![Binder](http://mybinder.org/badge.svg)](http://beta.mybinder.org/v2/gh/fomightez/clausen_ribonucleotides/master?filepath=index.ipynb)

*tl;dr:*  
Click any `launch binder` badge on this page to analyze ribonucleotide incorporation data from Clausen et al. 2015 data using script `plot_5prime_end_from_bedgraph.py`.


------

***Demonstrating the use of my script `plot_5prime_end_from_bedgraph.py` by analyzing ribonucleotide incorporation data***



-------



Usage
-----

This repository is set up to analyze ribonucleotide incorporation data from Clausen et al. 2015 data (see below), demonstrating the use of my script `plot_5prime_end_from_bedgraph.py`. The script will automatically be obtained when the notebook is run in the active Jupyter session launched from this repository. Click on any [`launch binder` badge](http://beta.mybinder.org/v2/gh/fomightez/clausen_ribonucleotides/master?filepath=index.ipynb) on this page to begin.

In the notebook that is launched I illustrate how to use the script and some of the various options it has.  Alternatively, the notebook can be viewed statically [here](https://nbviewer.jupyter.org/github/fomightez/clausen_ribonucleotides/blob/master/index.ipynb).

The necessary data is already available when in the active Jupyter session [launched from this repository](http://beta.mybinder.org/v2/gh/fomightez/clausen_ribonucleotides/master?filepath=index.ipynb).




Data Source
-----------


The data used here comes from [Clausen et al., 2015 (PMID:25622295)](https://www.ncbi.nlm.nih.gov/pubmed/25622295) (full citation below) and was retrieved [here](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE62181)

Users of the data should cite:

- Tracking replication enzymology in vivo by genome-wide mapping of ribonucleotide incorporation. Clausen AR, Lujan SA, Burkholder AB, Orebaugh CD, Williams JS, Clausen MF, Malc EP, Mieczkowski PA, Fargo DC, Smith DJ, Kunkel TA. Nat Struct Mol Biol. 2015 Mar;22(3):185-91. doi: 10.1038/nsmb.2957. Epub 2015 Jan 26. [PMID:25622295](https://www.ncbi.nlm.nih.gov/pubmed/25622295?dopt=Citation)

The sequences and analyzed data from that publication have been deposited in the NCBI Gene Expression Omnibus under accession number [GSE62181](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE62181).


***Clarifying Data Attribution:   
I, Wayne, had nothing to do with that manuscript or data. I simply generated after-the-fact a utility script for analyzing data for specific regions from there. That script is called `plot_5prime_end_from_bedgraph.py` and is available [here](https://github.com/fomightez/sequencework/tree/master/plot_read_data). It is demonstrated in the notebook [launchable from this repository](http://beta.mybinder.org/v2/gh/fomightez/clausen_ribonucleotides/master?filepath=index.ipynb)***



Technical Details
-----------------

This repository is set up to make use of the Binder service offered by [MyBinder.org](https://mybinder.org/). See their site for more information about Binder.

Python 3 only is available in the Binder sessions launched from this repository. However, the script `plot_5prime_end_from_bedgraph.py` also works in Python 2. This can be demonstrated by copying the notebook from this repo and uploading it into a Binder session launched from [here](https://github.com/fomightez/mcscan-blast-binder), which includes Python 2 as well. Run it there with the kernel switched to use Python 2.

Because the [Clausen et al., 2015 data](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE62181) are served via FTP, some of the data has been already included in any active Jupyter session launched from the `launch binder` button in the repository. MyBinder.org cannot access data served from FTP for security purposes.

Developed from my [blast-binder repo](https://github.com/fomightez/blast-binder) that was mainly made from adding the ability to run BLAST to much of the binderized repo from [here](https://github.com/fomightez/qgrid-notebooks) with the ability to also run PatMatch, see [here](https://github.com/fomightez/patmatch-binder) for information about PatMatch and launchable Jupyter notebooks demonstrating its use.

I borrrowed the 'warning' highlight/introductory text about notebooks at the top of the included notebook from Tim Sherratt's notebook [here](https://github.com/GLAM-Workbench/te-papa-api/blob/master/Exploring-the-Te-Papa-collection-API.ipynb).


Click this button below to begin:

[![Binder](http://mybinder.org/badge.svg)](http://beta.mybinder.org/v2/gh/fomightez/clausen_ribonucleotides/master?filepath=index.ipynb)
