Dockerfile -- It includes the set of commands which is used to deploy the required script file into the container and run it as image.
install_packages.R -- It is the R Script which includes all the R packages i.e needed to be preinstalled in the required image.
myscipt.R -- It is the R Script which includes the preprocessing of the required dataset and predicting the model.
test.csv-- It is the csv file which is used in myscript.R
train.csv-- It is the csv file which is used in myscript.R

NOTE: while running the docker file all the above files must be inccluded in the same location.
