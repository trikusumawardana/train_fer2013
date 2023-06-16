# Dataset
https://www.kaggle.com/datasets/msambare/fer2013?resource=download

# The Flow of Execution
1. Import the required libraries
2. Set the paths to the directories containing the train and test datasets
3. Define the parameters
4. Create an instance of ImageDataGenerator for data preprocessing and augmentation:
5. Load the train dataset using flow_from_directory
6. Load the test dataset using flow_from_directory
7. Define a function to preprocess the image
8. Create the model architecture using Sequential
9. Compile the model
10. Define the callbacks for early stopping and model checkpointing
11. Train the model and capture the history
12. Print a summary of the model
13. Plot the validation accuracy and validation loss
14. Load the best model
15. Evaluate the model on the test dataset

## License
This repository and the code within it are intended for academic use only.
