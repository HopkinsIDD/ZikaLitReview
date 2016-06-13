# ZikaLitReview
Data and analytic code for a literature review and pooled analysis aimed at estimating key values in the natural history of Zika virus.
The main directory of this project contains the data files and models necessary to reproduce the main analysis in our paper 
"Time to Key Events in the Course of Zika Infection and their Implications for Surveillance" (preprint available at http://biorxiv.org/content/early/2016/03/02/041913). The file
ZikaLiteReviewSupplement.Rmd contains all code necessary to recreate our analyses, and will reproduce the supplement to the paper. 


**NOTE:** Two chunks that run and save results of the JAGS models are set not to evaluate when the file is knit, 
*these chunks must be run to successfully knit the file and recreate the analysis*. However, once they are run once they need not
be run again unless something about the underlying models is changed.

This project is licensed under the terms of the GNU GPL v3 license.
