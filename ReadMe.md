# MNIST Regression

MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world”
dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has
served as the basis for benchmarking classification algorithms. As new machine learning
techniques emerge, MNIST remains a reliable resource for researchers and learners alike.
(https://en.wikipedia.org/wiki/MNIST_database).

#####Part 1:
Part 1: Find a least-squares binary classifier for handwritten MNIST digit set, i.e. determine if
an image 𝑥 is a digit 𝑘 or not digit 𝑘. Pick a digit you like. First, extract the indices of all digit’s
with label 𝑘 and randomly separate the samples into equal-sized training and testing groups.
Second, do the same for the digits that are not labeled 𝑘. Use label 𝑦$ = 1 if 𝑥$ is digit 𝑘 and 𝑦$ =
−1 otherwise. Find 𝛽, and 𝛽) , such that 𝑦$ ≈ 𝑦+$ = 𝐬𝐢𝐠𝐧 (𝛽2𝑥$ + 𝛽)) = 𝐬𝐢𝐠𝐧(𝑦5$). Note that 𝛽
can be visualized as a 2D image of the same 28x28 size as the digits in the MNIST data set.
Display it. Compute the classification error rate and confusion matrices for the both the training
and test sets. Reduce the number of parameters in the 𝛽 using backward selection methods.
Display 𝛽 for the reduced model.
Use the plot() function to run a series of diagnostic tests for your regression. Plot “Residuals vs
Fitted”, “Normal Q-Q”, “Scale-Location”, and “Residuals vs Leverage” plots.
(https://www.rdocumentation.org/packages/stats/versions/3.6.2/topics/plot.lm). Briefly describe
what you have observed.

#####Part 2: Repeat the above problem for all pairs of digits. For each pair of digits, report the
classification error rates for the training and testing sets. The error rates can be formatted nicely
into a triangular matrix. For storage and display efficiency, store the testing error in the lower
triangle and the training error in the upper triangle. Display 𝛽 and 𝛽) as a 2D images for pairs
with lowest and highest error rates.

#####Part 3: Use logistic regression and compare your results with Parts 1 and 2.
Part 4: Test for outliers in each group of 10 digits using Cook’s distance. Visualize the ‘mean’
and identified outliers for each digit. Repeat Parts 1 - 3 with outliers removed



### Installation

 requires [python](https://www.python.org/download/releases/3.0/) v3(3.6.9) to run.

