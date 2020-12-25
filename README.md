# Facial-Emotion-Detection

## How to run this project

## Aim of the project
Given an image you need to predict if the person in the image is contempt or not.

## Code Design:
**Step 1:** Used **Open Face** library for Feature extraction from the 167 input images. This generates 167 csv files of 1 row and 977 columns.Open face is an open source toolkit used to convert image data into a csv file format (dataset) . More details can be found at following links:  (https://cmusatyalab.github.io/openface/) , (https://github.com/Prodesire/face-mask).

**Step 2:** Using data preprocessing techniques on the generated csv files, this includes combining all the 167 csv files into 1 csv file, normalizing the dataset and labelling the dataset.

**Step 3:** Test Train Split - out of 167 images used 155 images for training and 12 images for testing purpose 

**Step 4:** Developed a **Genetic Algorithm** (Local Search Algorithm) for Feature Selection. write details of each function.Show how by using different operators and adjusting the parameters of the search algorithm, brings about a  difference in the Space and Time of the search process, and also the Quality of the search solution

**Step 5:** Used **KNN** algorithm for training and solving classification problem

