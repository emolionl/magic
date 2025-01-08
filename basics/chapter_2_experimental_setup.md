---
icon: markdown
---

# Chapter 2: Experimental Setup

### Simplified Approach: TRNG and Timeline Experiment

To simplify the starting point of this research, the initial experiment will focus solely on TRNG outputs over a timeline without integrating EEG data. The design is as follows:

#### Experiment Design

1. **Baseline Phase (10 Minutes):**
   * Participants will sit quietly, focusing on "nothing" to establish a baseline for TRNG outputs.
   * TRNG outputs (0s and 1s) will be recorded continuously during this period.
2. **Intention Phase 1 (10 Minutes):**
   * Participants will focus their intention on influencing the TRNG to generate more "1s."
   * TRNG outputs will be recorded to detect any deviations from the baseline.
3. **Intention Phase 2 (10 Minutes):**
   * Participants will shift their focus to influence the TRNG to generate more "0s."
   * TRNG outputs will again be recorded for comparison.

#### Data Analysis

* **Statistical Metrics:**
  * Calculate the frequency of 0s and 1s for each phase.
  * Compare the distribution of TRNG outputs across the baseline and intention phases using chi-square tests or similar methods.
* **Visualization:**
  * Plot the TRNG outputs over time for each phase to visually identify patterns or deviations.

#### Goals

This simplified approach aims to:

* Establish a clear baseline for TRNG behavior without intentional focus.
* Test whether human intention can influence TRNG outputs under controlled conditions.
* Provide a foundation for later integration of EEG and machine learning to analyze more complex interactions.

