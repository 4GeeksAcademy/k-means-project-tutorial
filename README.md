<!-- hide -->
# K-Means - Step by step guide
<!-- endhide -->

- Understanding a new dataset.
- Model the data using a K-Means.
- Analyze the results and train a supervised model.

<onlyfor saas="false" withBanner="false"

## 🌱 How to start this project

Follow the instructions below:

1. Create a new repository based on [machine learning project](https://github.com/4GeeksAcademy/machine-learning-python-template) by [clicking here](https://github.com/4GeeksAcademy/machine-learning-python-template/generate).
2. Open the newly created repository in Codespace using the [Codespace button extension](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository#creating-a-codespace-for-a-repository).
3. Once the Codespace VSCode has finished opening, start your project by following the instructions below.

</onlyfor>

## 🚛 How to deliver this project

Once you have finished solving the exercises, be sure to commit your changes, push them to your repository, and go to 4Geeks.com to upload the repository link.

## 📝 Instructions

### House grouping system

We want to be able to classify houses according to their region and median income. To do this, we will use the famous `California Housing` dataset. It was constructed using data from the 1990 California census. It contains one row per census block group. A block group is the smallest geographic unit for which US Census data is published.

#### Step 1: Loading the dataset

The dataset can be found in this project folder under the name `housing.csv`. You can load it into the code directly from the link:

```text
https://raw.githubusercontent.com/4GeeksAcademy/k-means-project-tutorial/main/housing.csv
```

Or download it and add it by hand in your repository. In this case, we are only interested in the `Latitude`, `Longitude` and `MedInc` columns.

Be sure to conveniently split the dataset into `train` and `test` as we have seen in previous lessons. Although these sets are not used to obtain statistics, you can use them to train the unsupervised algorithm and then to make predictions about new points to predict the cluster they are associated with.

#### Step 2: Build a K-Means

Classify the data into 6 clusters using the K-Means model. Then store the cluster to which each house belongs as a new column in the dataset. You could call it `cluster`. To introduce it to your dataset, you may have to categorize it. See what format and values it has, and act accordingly. Plot it in a dot plot and describe what you see.

#### Step 3: Predict with the test set

Now use the trained model with the test set and add the points to the above plot to confirm that the prediction is successful or not.

#### Step 4: Train a supervised classification model

Now that K-Means has returned a categorization (clustering) of the points for the training and test sets, study which model might be most useful and train it. Get the statistics and describe what you see.

This flow is very common when we have unlabeled data: use an unsupervised learning model to label it automatically, and then a supervised learning model.

#### Step 5: Save the models

Store both models in the corresponding folder.

> Note: We also incorporated the solution samples on `./solution.ipynb` that we strongly suggest you only use if you are stuck for more than 30 min or if you have already finished and want to compare it with your approach.
