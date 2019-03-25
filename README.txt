1. Download the tit.arff and adult.arff from the github, apply 2 to 4 for both. all steps for tit.arff
2. Open them in weka and run them by going into weka -> explorer -> cluster- > and chose the corresponding filter for K means and EM, select classes to clusters evaluation with your label, and click start. Tune the hyper paramters for number of clusters to find optimal clusters
3. Download the student filter from package manager
4. Apply ICA, PCA, and Random Projection from the proprocessing filters and save them. Run Info gain in Select Attribute and determine what attributes to delete and save another arff file.
5. Run Neural net on the saved arff files and record data
6. apply k means and EM to each of the files and run the neural net again

https://github.com/datyvk/Project3