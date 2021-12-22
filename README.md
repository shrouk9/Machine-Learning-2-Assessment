# Machine-Learning-2-Assessment

## Coding Tasks:
### 1. Recommender systems
a. Given the following resources
b. Please use the above resources to build two recommender systems. The first
one is to recommend the top 5 movies based on a given movie title. The
second model will estimate the rating of a movie based on the user
behaviour.
c. You are allowed to use the Surprise python package, Scikit-Learn, or your
own implementation. “NMF is sufficient or whatever you desire”
d. It’s expected that your justification will be clear about the chosen
hyperparameters and the mechanism of the chosen algorithm.

### 2. Topic Modelling
a. Choose either the twitter dataset or the newsgroup dataset or combine them
used in the above resources “i” and “ii”. It’s your own choice but you should
describe the merits and demerits of combining the two datasets if you do so.
b. Build a topic modelling algorithm using NMF model either using Scikit-Learn
or your implementation or any other library.
c. Given a sentence, create a function that will return the top 3 topics using
NMF.
d. Compare the performance of the NMF model against LDA “Latent Dirichlet
Allocation”. Choose the appropriate metric. “Perplexity, Pearson, or
Coherence, ...”
e. You are not asked to describe the inner steps of LDA at all.
### 3. Anomaly detection
a. Given the following resources: http://odds.cs.stonybrook.edu/
b. Using a GMM model, please detect the anomalies in either of the following
datasets: “Obligatory”
i. A multidimensional dataset from the above resources “i”.
ii. The credit card fraud detection dataset in “ii”.
c. You can use Scikit-Learn outlier detection models or PyOD models. “Bonus”
d. Please quickly describe the chosen algorithm.
e. Benchmark your outlier detection model against a supervised approach of
your own choice. The AUC will be a good metric however choose your own
metric if you want to with a sensible justification.
Kareem H. El-Safty 3
### 4. Matrix Decomposition
a. Create a notebook and experiment with PCA if it can handle gaussian noise
and salt and pepper noise.
b. It would be good to plot the number of required components against the
level of impurity or noise.
c. Write down your conclusions and insights and of course you can use the set
of images that you captured or available image datasets such as MNIST or
any easy image.
d. Linear discriminant analysis suffers from multicollinearity. Generate a highly
correlated dataset with its labels - this should be fun - and try to decorrelate
the features using matrix decomposition techniques then fit the data against
a linear discriminant model.
### 5. K-means suffers a lot when the dataset is not flat
a. Please apply the necessary techniques - perhaps such as kernels - on the
moons dataset found in Scikit-Learn to make it possible to cluster the
dataset successfully. A bonus question: is there a method in Scikit-Learn
other than Spectral Clustering - like the DBSCAN method which depends on
the Nearest Neighbour techniques or an Agglomerative method - that can
do this trick for you? Explain please. “Read the user guide of the clustering
page on Scikit-Learn website”
b. Choose two unsupervised metric techniques and evaluate the K-means
output before and after applying the techniques in point “a”. One of the
techniques should not require a label to be evaluated.
Kareem H. El-Safty 
