# CA_housing_analysis
Machine learning and classical statistics applied to Census 1990 data on CA block group median house values


This is a project in six parts analyzing and modeling the California housing dataset that Aurelien Geron looks at in Chapter 2 of his book, "Hands-On Machine Learning with Scikit-Learn & TensorFlow".  The work presented here is related to work I have been doing for Perscitus International.

At present (February 2022) all six parts have been uploaded: Part01, Part02, Appendix A, Appendix B, Appendix C, and Appendix D.  Appendices A-C contain material on imputation and have recently been updated.  NOTE: As of December 2021 github.com is having issues opening Appendix C; that is why I also uploaded a pdf version of it.  The pdf file, unfortunately, is much harder to read.  An alternative method for viewing is to download the file (Ctrl-A, Ctrl-C, then paste into Notepad++ and save out as a .ipynb) and then open in Jupyter Notebook.  github.com might be having trouble with the colors used in the graphics.


In this notebook I explore a wide range of predictive models for the CA housing dataset.  The response variable is median house value.

Some of the noteworthy elements of the investigation include: 

(a) introducing a valuable new predictor---an urbanacity metric

(b) finding a transformation for longitude that dramatically increases its predictive power; the transformed variable eliminates the need for the categorical ocean_proximity variable that Geron introduced

(c) showing how we can improve upon the Gibbs sampler approach to imputing values for censored data.

Items (a) - (c) are found in Part01, Appendix A, Appendix B, and Appendix C.

Appendix D explores additional linear models.  These models improve upon the predictive performance of the OLS model, g03, of Part01.  A couple of the models in Appendix D still retain the transparency, or explanatory power, that we have with the g03 model.

















