# wine-prediction using knn algorithm

These data are the results of a chemical analysis of wines grown in the same region in
Italy but derived from three different cultivars. The analysis determined the quantities of
13 constituents found in each of the three types of wines.

The attributes are,
1) Alcohol
2) Malic acid
3) Ash
4) Alcalinity of ash
5) Magnesium
6) Total phenols
7) Flavanoids
8) Nonflavanoid phenols
9) Proanthocyanins
10)Color intensity
11)Hue
12)OD280/OD315 of diluted wines
13)Proline

Attribute Information:
All attributes are continuous

so in this case, a KNN algorithm have been used to build wine prediction based on a sample of wine dataset producing in the following link

Download Link: https://archive.ics.uci.edu/ml/datasets/Wine

So look out why used KNN algorithm and what measurements have been used for KNN algorithm.

<h3>why used KNN algorithm?</h3>

<ul>
<li>K-Nearest Neighbour is one of the simplest Machine Learning algorithms based on Supervised Learning technique.</li>
<li>K-NN algorithm assumes the similarity between the new case/data and available cases and put the new case into the category that is most similar to the available categories.</li>
<li>K-NN algorithm stores all the available data and classifies a new data point based on the similarity. This means when new data appears then it can be easily classified into a well suite category by using K- NN algorithm.</li>
<li>K-NN algorithm can be used for Regression as well as for Classification but mostly it is used for the Classification problems.</li>
<li>K-NN is a non-parametric algorithm, which means it does not make any assumption on underlying data.</li>
  <li>It is also called a <em>lazy learner</em> algorithm because it does not learn from the training set immediately instead it stores the dataset and at the time of classification, it performs an action on the dataset.</li>
<li>KNN algorithm at the training phase just stores the dataset and when it gets new data, then it classifies that data into a category that is much similar to the new data.</li>
<li>so to measure k-nearest neighbour in wine prediction,a mathematical operation have been used which is called as 'Euclidean Distance'.</li>
</ul>
  
<h3>Euclidean Distance</h3>

What is meant by Euclidean distance?
Image result for euclidean distance
In Mathematics, the Euclidean distance is defined as the distance between two points. In other words, the Euclidean distance between two points in the Euclidean space is defined as the length of the line segment between two points.

<img src="https://www.gstatic.com/education/formulas2/472522532/en/euclidean_distance.svg" color="white"/>

<p>p,q = two points in euclidean distance</p>
<br>
<p>q<sub>i</sub>,p<sub>i</sub> = Euclidean vectors, starting from the origin of the space (initial point)</p>
<br>
n = n-space
