Deep Learning for Computer Vision (CS776A): Assignment I

###############################################################################################################################################################

Submitted By: Shivam Tripathi (21111408) shivamtr21@iitk.ac.in

###############################################################################################################################################################

Packages and Libraries Required:
python: version 3.9.7
pytorch: version 1.10.1+cu102
opencv: version 4.5.3
numpy: version 1.19.5
matplotlib: version  3.4.3
pickle: version 4.0

The main solution notebook is '21111408.ipynb' file

###############################################################################################################################################################

Directory Structure:

Keep all files in a single directory, there is no substructure.
However, there is a folder 'codefiles' that contains the files provided with the HelloIITK assignment.

Files required in the directory:

codefiles  --> Folder provided with the assignment on the HelloIITK portal
cifar-10-python.tar.gz  --> CIFAR10 data file, download from https://www.cs.toronto.edu/~kriz/cifar-100-python.tar.gz
augmented_model_parameters.pkl  --> Parameters of the model trained on augmented data (dictionary of weights and biases)
unaugmented_model_parameters.pkl  --> Parameters of the model trained on un-augmented data (dictionary of weights and biases)
augmented_data_features.npy  --> Extracted features of augmented data (100000, 512)
test_data_features.npy  --> Extracted features of the test data (10000, 512)


###############################################################################################################################################################

To run the complete notebook:
	Keep the following flags as true: (they are set as such by default)
		load_weights = True
		load_features = True
	Run the notebook as usual. It should not take more than 3 minutes.

##############################################################################################################################################################