# Image-Classification

![CNN-architecture-for-image-classification](https://github.com/user-attachments/assets/6d3b18a3-af25-42a5-873b-04108bf7d66f)



### Task 1: Data Exploration and Preparation
- **Loading and Visualization:** The CIFAR-10 dataset was loaded, which includes 60,000 color images in 10 different classes. Sample images from the dataset were displayed along with their labels to understand what the images look like and what they represent.
- **Dataset Inspection:** The shape of the training and testing data was printed to confirm the dimensions and the number of images available for training and testing.
- **Normalization:** The pixel values of the images were normalized to the range [0, 1] to facilitate more efficient training by scaling down the input parameter space.
- **Data Splitting:** The dataset was split into an 80% training set and a 20% testing set to ensure that there was enough data for training the model while having a separate subset for model evaluation.

### Task 2: Build and Train a CNN Model
- **Model Design:** A convolutional neural network (CNN) was constructed using layers like Conv2D for feature extraction, ReLU activation functions for non-linearity, MaxPooling for dimensionality reduction, Dropout for regularization, and Dense layers for classification.
- **Model Compilation:** The model was compiled with a loss function, optimizer, and metrics specified to guide the training process.
- **Training:** The model was trained on the training dataset for a specified number of epochs, adjusting weights to minimize the loss.
- **Evaluation Plotting:** Training and validation loss and accuracy were plotted to visually assess how well the model was learning and generalizing to unseen data. Observations were made regarding potential overfitting or underfitting based on these plots.

### Task 3: Evaluate the Model
- **Performance Evaluation:** After training, the model's performance was assessed on the test dataset to measure accuracy and loss on data that was not seen during training.
- **Confusion Matrix and Classification Report:** A confusion matrix and a classification report were generated to provide detailed insights into the model's performance across all classes, highlighting precision, recall, and F1-score for each category.

### Task 4: Experimentation with Model Improvements
- **Optimization Techniques:** Different optimizers were tested to compare their impact on model performance. This experimentation aimed to find an optimizer that could improve training dynamics and potentially enhance the model's accuracy and generalization.
