# CA_housing_analysis
Machine learning and classical statistics applied to Census 1990 data on CA block group median house values


This is a project in five parts analyzing and modeling the California housing dataset that Aurelien Geron looks at in Chapter 2 of his book, "Hands-On Machine Learning with Scikit-Learn & TensorFlow".  The work presented here is related to work I have been doing for Perscitus International.

At present (October 2021) all five parts have been uploaded: Part01, Part02, Appendix A, Appendix B, and Appendix C.  The appendices contain material on imputation and have recently been updated.

I explore a wide range of predictive models for this housing dataset.  The response variable is median house value.

Some of the noteworthy elements of the investigation include: 

(a) introducing a valuable new predictor---an urbanacity metric

(b) finding a transformation for longitude that dramatically increases its predictive power; the transformed variable eliminates the need for the categorical ocean_proximity variable that Geron introduced

(c) showing how we can adjust the output from a Gibbs sampler to improve the imputation of censored data.

Items (a) - (c) are found in Part01, Appendix A, and Appendix B. 


NOTE: the .pdf files are created by converting the .ipynb files using the Firefox browser.  The conversion does not always work that well.  The .pdf files are provided for those who do not want to open up the Jupyter notebook viewer.  The notebooks, however, look far better in the notebook viewer.

One further note: the notebook viewer in Github might have difficulty opening some of the larger notebooks.  One needs to be persistent with the Reload button.















