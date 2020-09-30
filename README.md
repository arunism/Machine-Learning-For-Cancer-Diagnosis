# Personalized Cancer Diagnosis

### What is Personalized Cancer Diagnosis Dataset?

Personalized Cancer Diagnosis Dataset is the collection of genetic mutations based on clinical evidence (text) provided by Memorial Sloan Kettering Cancer Center (MSKCC).

There are nine different classes a genetic mutation can be classified on.

This is not a trivial task since interpreting clinical evidence is very challenging even for human specialists. Therefore, modeling the clinical evidence (text) will be critical for the success of your approach.

Both, training and test, data sets are provided via two different files. One (training/test_variants) provides the information about the genetic mutations, whereas the other (training/test_text) provides the clinical evidence (text) that our human experts used to classify the genetic mutations. Both are linked via the ID field.

Therefore the genetic mutation (row) with ID=15 in the file training_variants, was classified using the clinical evidence (text) from the row with ID=15 in the file training_text

Finally, to make it more exciting!! Some of the test data is machine-generated to prevent hand labeling. You will submit all the results of your classification algorithm, and we will ignore the machine-generated samples.

##### It consists of the following datasets:

    * training_variants
    * training_text

##### The Features/Attributes/Columns for training_variants are:

    * Id - Unique Identifier for the Dataset
    * Gene - Name of the gene
    * Variation - Name of the variation/mutation
    * Class - One of the 9 classes

##### The Features/Attributes/Columns for training_text are:

    * Id - Unique Identifier for the Dataset
    * Text - Bunch of text describing the mutation/variation


##### You can Download the Dataset from: https://www.kaggle.com/c/msk-redefining-cancer-treatment/data
