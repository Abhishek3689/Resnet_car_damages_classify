# Resnet_car_damages_classification
#### The link for dataset is available in kaggle

https://www.kaggle.com/datasets/abhisheknishad8988/car-damages/data

In the insurance industry processing claims for vehicle damage is a common and most essential task. With the advancement in AI and Computer Vision the users can settle the claims online instantly by uploading the image of damage car with the insurance company.

Now the insurance companies face the constant challenge of fraudulent claims. It is a common practice for users to submit the fraudulent images as a part of claim settlement process. This brings out the threat/challenge to the insurance companies to identify the fraudulent claims which lead to significantly financial loss.

Fraudulent claims often involve exaggerating the extent of damage or submitting false claims altogether
In this problem we will focus on the first type of problem i.e. exaggerating the extent of damage. To mitigate these losses and maintain the integrity of their operations, insurance companies must develop effective methods to flag out these claims most accurately.

The challenge here is to develop a robust and high performance model for classifying an image of a car into different type of damages automatically with the help of computer vision techniques

The Dataset has 4 files
- train set
- train.csv
- test set
- test.csv

##### The train set contains a diverse dataset of car images of damaged vehicles at various angles, lighting condition .
##### train.csv contains 3 columns : image_id, filename and target class (label)

##### Columns Description
1. image_id :Unique identifier of image
2. filename : Filename of Image
3. label :Types of Damages

  * 1:Crack
  * 2:scratch
  * 3:tire flat
  * 4:dent
  * 5:glass shatter
  * 6:lamp broken.
  
In the test datset you are only provided with images, you need to predict the type of damage present in the test set

##### Test.csv contains 2 columns: image_id and filename

Test.csv
##### Columns Description
1. image_id: Unique identifier of image
2. filename :Filename of Image
