---
icon: pen-to-square
---

# Chapter 3: Data Collection

#### 1.1 Background

* Overview of TRNGs and their importance.
* Introduction to EEG technology and its applications in neuroscience.
* Potential interaction between human brain activity and TRNGs.
* Role of machine learning in analyzing complex datasets.

#### 1.2 Objectives

* To determine whether EEG patterns influence TRNG output.
* To identify specific EEG features that correlate with TRNG deviations.
* To develop machine learning models for detecting and interpreting these correlations.

#### 1.3 Hypothesis

* State the hypothesis: e.g., "Specific mental states, as measured by EEG, can influence the statistical properties of TRNG outputs."

### Chapter 2: Experimental Setup

#### 2.1 Equipment

* **TRNG Device**: ESP32 with integrated TRNG.
* **EEG Device**: Specify model (e.g., Muse, OpenBCI, or other EEG systems).
* **Data Collection System**: Hardware and software setup for simultaneous EEG and TRNG data recording.
* **Software Tools**:
  * Python for data analysis.
  * Libraries: TensorFlow/PyTorch for machine learning, MNE-Python for EEG processing.

#### 2.2 Participants

* Number of participants and inclusion criteria.
* Consent and ethical considerations.

#### 2.3 Environment

* Controlled setting to minimize external influences.
* Instructions for participants to enter specific mental states (e.g., meditation, focus, relaxation).

### Chapter 3: Data Collection

#### 3.1 EEG Data Recording

* Procedure for setting up EEG device.
* Calibration process and quality checks.
* Types of tasks or stimuli used to evoke mental states.

#### 3.2 TRNG Data Collection

* Methodology for continuous TRNG output logging.
* Synchronization of TRNG data with EEG timestamps.

#### 3.3 Combined Data Logging

* Software tools and scripts for real-time data integration.
* Backup and data validation processes.

***

### Chapter 4: Data Preprocessing

#### 4.1 EEG Data

* Filtering (e.g., band-pass filters for alpha, beta, theta waves).
* Artifact removal (e.g., eye blinks, muscle movements).
* Segmentation into epochs corresponding to task phases.

#### 4.2 TRNG Data

* Statistical analysis (e.g., entropy, deviation from randomness).
* Identification of anomalies or deviations.

#### 4.3 Synchronization

* Aligning EEG and TRNG data based on timestamps.

***

### Chapter 5: Machine Learning Analysis

#### 5.1 Feature Extraction

* EEG Features: Power spectral density, event-related potentials, connectivity metrics.
* TRNG Features: Bit distribution, entropy, temporal patterns.

#### 5.2 Model Design

* Supervised learning: Label data based on experimental conditions.
* Unsupervised learning: Cluster EEG-TRNG relationships.
* Models: Convolutional Neural Networks (CNNs) for spatial EEG features, Recurrent Neural Networks (RNNs) for temporal dependencies.

#### 5.3 Training and Validation

* Train/test split or cross-validation.
* Metrics: Accuracy, precision, recall, F1 score for classification tasks.

***

### Chapter 6: Results and Analysis

#### 6.1 Statistical Analysis

* Correlation between EEG features and TRNG deviations.
* Significance testing for observed patterns.

#### 6.2 Machine Learning Outcomes

* Model performance evaluation.
* Visualization of feature importance and learned patterns.

#### 6.3 Interpretation

* Insights into potential EEG influence on TRNG behavior.
* Limitations and alternative explanations.

***

### Chapter 7: Conclusion and Future Work

#### 7.1 Summary of Findings

* Key results and their implications.

#### 7.2 Future Directions

* Exploring different EEG tasks or states.
* Refining machine learning models.
* Expanding to larger datasets and more participants.

***

### Chapter 8: Appendix

#### 8.1 Code Repositories

* Links to GitHub or other repositories for scripts and tools.

#### 8.2 Data Samples

* Example EEG and TRNG data snippets.

#### 8.3 References

* Scientific papers, tools, and resources used in the experiment.

