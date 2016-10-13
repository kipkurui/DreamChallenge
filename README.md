# Implementation of TeamKE submissions to DREAM challenge


### Step 1: Install the requirements

We are using the conda environment in our analysis, whcih can be easily set up with requirements.yml


### Get all the required data in place

This code uses the Unzipped files provided by the organizers. These folders should be setup and contain the respective datasets. In addition to the provided data, the following additiona data are used.

1. Motifs: Contains all motifs used in our code
    - .meme: Downloaded from various sources as indicated by name suffix
    - .tomtom: Their ranks based on similarity using TOMTOM
    - \_cluster.txt: Clustered suing FISim
2. DNAShape information downloaded from ftp://rohslab.usc.edu/hg19/
    - hg19.HelT.wig.bw
    - hg19.MGW.wig.bw
    - hg19.ProT.wig.bw
    - hg19.Roll.wig.bw