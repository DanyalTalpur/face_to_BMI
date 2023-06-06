# BMI calculator using facial data


The BMI calculator component uses facial recognition technology to calculate the Body Mass
Index (BMI) of the user. This feature provides an accurate BMI calculation based on the user's
face, which eliminates the need for manual input of height and weight.
The research indicates that overweight individuals experience weight stigma and discrimination,
which can have negative impacts on their mental and physical health. The stigma associated with
measuring weight may make some individuals hesitant to use traditional methods of BMI
calculation. However, the use of facial data for BMI calculation may provide a more discreet and
less stigmatizing alternative. This may encourage more individuals to track their BMI and take
steps towards a healthier lifestyle without the fear of judgment or stigma.

The BMI calculator using facial data was developed using a combination of deep learning
techniques and traditional image processing techniques. The methodology involved several steps,
including data collection and preprocessing, feature extraction, model training, and performance
evaluation.

# Data Preprocessing:
Before the images were used for model training, they underwent several preprocessing steps to
ensure that they were of good quality and suitable for the model. Firstly, images without clear two
eyes were deleted. Secondly, the faces were cropped from the images to ensure that only the facial
region was used for BMI estimation. Thirdly, color correction was applied to ensure that the
images were consistent in terms of brightness and contrast. Fourthly, the dataset was balanced by
randomly oversampling underrepresented BMI categories. Finally, data augmentation techniques
such as flipping, rotation, and zooming were used to increase the size of the dataset.

# Feature Extraction:
To extract features from the facial images, a pre-trained deep convolutional neural network (CNN)
was used. The CNN was fine-tuned on the facial images to extract relevant features for BMI
estimation. The features were extracted from the output of the last convolutional layer of the CNN.
These features were then flattened and used as input to the regression model.

# Model Training:
The model used for BMI estimation was a regression model. The model was trained using Kfold
cross-validation, with the dataset split into training and test sets in an 80/20 ratio. The model was
trained using the training set and validated using the test set. The performance of the model was
evaluated using the mean absolute error (MAE) and the coefficient of determination (R-squared).

# Data Privacy:
It is important to note that the data collected for this project cannot be shared due to user privacy
and ethical concerns.

![real time BMI](https://github.com/DanyalTalpur/face_to_BMI/assets/125806691/b5c234ab-13d0-4105-a75a-9bfb32fe8e95)
