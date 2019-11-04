# Support_Vector_Machines
SVM with RBF Kernal on Cancer Dataset

In this notebook, you will use SVM (Support Vector Machines) to build and train a model using human cell records, and classify cells to whether the samples are benign or malignant.

## About DataSet

The example is based on a dataset that is publicly available from the UCI Machine Learning Repository (Asuncion and Newman, 2007)[http://mlearn.ics.uci.edu/MLRepository.html]. The dataset consists of several hundred human cell sample records, each of which contains the values of a set of cell characteristics. The fields in each record are:

## Fieldname       	Description
    ID	          Clump thickness
    Clump	        Clump thickness
    UnifSize    	Uniformity of cell size
    UnifShape	    Uniformity of cell shape
    MargAdh	      Marginal adhesion
    SingEpiSize	  Single epithelial cell size
    BareNuc	      Bare nuclei
    BlandChrom	  Bland chromatin
    NormNucl	    Normal nucleoli
    Mit	          Mitoses
    Class	        Benign or malignant


The ID field contains the patient identifiers. The characteristics of the cell samples from each patient are contained in fields Clump to Mit. The values are graded from 1 to 10, with 1 being the closest to benign.

The Class field contains the diagnosis, as confirmed by separate medical procedures, as to whether the samples are benign (value = 2) or malignant (value = 4).
