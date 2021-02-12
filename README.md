# AI Data Analysis for Genomics and Whole Slide Images data

The idea is to classify colorectal cancer with the integration of informations coming from Gene Expression analysis and from Whole Slide Image analysis.

This integration is done building a consensus classifier that manage the results coming
from the mRNA classification and the Whole Slide Image classification.

The walkthrough is explained in details in the <b>Report</b>, and also on the <b>Slides</b>

### Repository Structure

Data are downloaded from the <b>Genomic Data Common Portal</b> (https://portal.gdc.cancer.gov/). I saved data on my drive, you can do that with your drive.

The Project folder is structured in the following way:

- ipynb folder contain all the codes: 
				
	``` Genomics_mRNAClassification: Contains the code that analyze Gene Expression. ```
				
	``` manifestFiltering: Contains the code that filter out the WSImages manifest. ```
				
	``` WSI_ImageClassification: Contains the code that analyze Whole Slide Images.```
				
	``` ConsensusClassifier: Contains the code that integrates Gene Expression and WSI analysis in a Consensus Classifier.```

- csv\_Results folder contain the results of the IMPROVEMENT.

- BioinfoProject\_Report.pdf : Contains the Report of this project.

- BioinfoProject\_Slides : Contains the slides for the presentation of this project.


The .ipynb files contains all cells ran and the corresponding results for this project.
Is suggested to load these files on Colab (https://colab.research.google.com/notebooks/intro.ipynb).
In this way the results of all the cells can be seen.

