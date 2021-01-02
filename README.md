# Anomaly / Outlier Detection
This is a simple example of Introduction to Anomaly Detection.

## Genarate Data with Faker
Faker is a library through which we can generate fake data.
for more information click on the [this link](https://faker.readthedocs.io/en/master/)

I have generated a fake dataset with faker library.
install in Google Colab or Jupyter Notebook via pip
!pip install Faker

## Data Visualization
Seeing is believing, just detecting anomalies/outlier by seeing / visualize with [matplotlib](https://matplotlib.org/3.3.3/contents.html)

## Clustering based approach for anomaly detection
### K-Mean Clustering
 In this approach, we start by grouping the similar kind of objects. Mathematically, this similarity is measured by distance measurement functions like Euclidean distance, Manhattan distance and so on. Euclidean distance is a very popular choice when choosing in between several distance measurement functions. Let's take a look at what Euclidean distance is all about.

An extremely short note on Euclidean distance

If there are n points on a two-dimensional space and their coordinates are denoted by(x_i, y_i), then the Euclidean distance between any two points((x1, y1) and(x2, y2)) on this space is given by:

square root[(x1-x2)^2 + (y1-y2)^2]

## Anomaly Detection as a Classification Problem
### K-Nearest Neighbors
To be able to treat the task of anomaly detection as a classification task, we need a labeled dataset. Let's give our existing dataset some labels.

We will first assign all the entries to the class of 0 and then we will manually edit the labels for those two anomalies. We will keep these class labels in a column named class. The label for the anomalies will be 1 (and for the normal entries the labels will be 0).

#### Note: Please open the jupyter notebook .ipynb file for detail explaination. Thanks

