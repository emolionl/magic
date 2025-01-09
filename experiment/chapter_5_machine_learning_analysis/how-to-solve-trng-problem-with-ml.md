---
description: Supervised or Unsupervised Learning?
---

# How to solve TRNG (without EEG) problem with ML

#### **Supervised Learning**

* **Definition**: Supervised learning involves training a model on labeled data, where the labels are known categories or outcomes.
* **How It Applies to Your Experiment**:
  * If you label the TRNG data by phase (e.g., "Baseline," "Intention on 1," "Intention on 0"), it becomes a supervised learning problem.
  * **Example Task**: Train a model to classify whether a given segment of TRNG data belongs to the baseline, "1" focus, or "0" focus phase.
  * **Model Types**: Logistic regression, Support Vector Machines (SVMs), or neural networks.

***

#### **Unsupervised Learning**

* **Definition**: Unsupervised learning involves finding patterns or clusters in data without predefined labels.
* **How It Applies to Your Experiment**:
  * If you don’t label the data by phase and instead explore whether the TRNG outputs naturally form distinct clusters corresponding to the three phases, this is an unsupervised learning task.
  * **Example Task**: Use clustering methods like K-Means or DBSCAN to see if the TRNG outputs group into three distinct clusters that align with the phases.
  * **Model Types**: K-Means, Gaussian Mixture Models (GMM), DBSCAN.

***

#### **Which One to Use?**

1. **Starting with Supervised Learning**:
   * If your goal is to test whether the model can distinguish between the three phases based on TRNG data, supervised learning is a clear choice.
   * Example: Train the model using labeled data from the three phases and evaluate its classification performance.
2. **Explore Unsupervised Learning**:
   * If you’re curious whether the phases are inherently distinguishable based on the TRNG outputs, unsupervised learning can reveal natural groupings in the data.
   * Example: Cluster the TRNG outputs and see if clusters align with your experiment phases.
