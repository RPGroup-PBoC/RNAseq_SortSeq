# Reg-Seq

Welcome to the repository for the Reg-Seq project of the Rob Phillips Lab at Caltech! 

## Go to the tutorials branch to work through the analysis code for the Reg-Seq project

All of the code use in this repo is python-based.
The library requirements can be installed by executing the following command using
[`pip`](pypi.org/project/pip) in the command line:

``` pip install -r requirements.txt ```

If you have `conda` you can also install the libraries by creating a conda environment.
To do this, run the following command: 

```conda env create -f env2.yml```

## Repository folders

This repository is broken up into several directories and subdirectories. Please
see each directory for information regarding each file. 


### **`results`** 

The Reg-Seq paper is contained in the main repository, figures for mass spectrometry enrichments, as well as lists of sigma factor identities and transcription factor binding site locations are contained in the results folder. All information footprints from this experiment are also contained here.  

### **`datasets`** 

All of the processed datasets are stored here. The datasets folder contains what you'll need to run the
analysis code and/or explore the results from our paper.

### **`figs`**

The figs folder contains all the source figures for use in the interactive figure for the Reg-Seq project. https://www.rpgroup.caltech.edu/RNAseq_SortSeq/interactive_a
