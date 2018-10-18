##	Dog Breed Classifier using CNN and Transfer Learning

This project is about building a dog breed classifier using Convolution Neural Network (CNN) and Transfer Learning. The test accuracy of this CNN model to predict the dog breeds from its images is about 87%. In the final model using transfer learning, I have used Xception pre-trained model to act as a features extractor of the dogs’ dataset, and then apply fully connected dense layers to classify the dog images into its predicted breed. Finally I converted the final model into Flask Web App to be production-ready solution. The dataset has a limited number of instances, so to protect against overfitting and augment the size of training dataset; we used data augmentation technique to increase the number of the instances in the training dataset as well as the validation dataset.


## Testing the final model on unseen data

**Here is some results in a visual way that summarize the accuracy of the final model when I have tested on unseeen dogs (new instances):**

<img src="https://github.com/osamadev/Dog-Breed-Classifier-Using-CNN-Model-and-Transfer-Learning-/blob/master/images/my_results.png" >
