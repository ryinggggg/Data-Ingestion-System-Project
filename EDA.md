# Exploratory Data Analysis(EDA)

---

## 1. Background and Objective

This analysis is based on a small live sample of user reviews collected from a single application on Google Play. Google Play was selected as the primary data source due to its higher accessibility and practical feasibility for initial exploration.

It is important to note that this stage is based on a limited sample, while a much larger volume of reviews can be continuously collected. Therefore, the focus of this stage is not on sample size adequacy, but on understanding the dataset’s structure and core characteristics.

---

## 2. Key Patterns and Observations

### 2.1 Review Text Length Distribution

The majority of user reviews are extremely short, with a median length of 13 characters and a mean length of approximately 29 characters. The review length distribution is strongly righ-skewed and heavy-tailed: most users leave brief comments, while a small number of reviews are extremely long, with some exceeding 1,000 characters.

---

### 2.2 Relationship Between Review Length and Rating

There is a strong realationship between Review length and rating. Lower-rated reviews tend to be substantially longer and more dispersed, while higher-rated reviews are generally shorter and more concentrated.

---

### 2.3 Rating Distribution Characteristics

The rating distribution exhibits a strong positive skew, with the majority of reviews concentrated in the highest rating category. Low and mid-range ratings account for only a small fraction of the dataset.

---

### 2.4 Field-Level Characteristics
 
The most recent reviews are from within the past day, confirming the freshness of the data source and its suitability for continuous collection and time-based analysis.  
Because user identifiers are anonymized, the dataset does not support individual-level behavioral tracking or longitudinal user modeling. As a result, analysis is limited to review-level and aggregate patterns, and cannot capture evolving user sentiment trajectories over time.

---

## 3. Recommendations for Downstream Analytical Use

Based on the observed heavy-tailed structure of review length and its relationship with rating behavior, downstream analysis should explicitly account for extreme text lengths to reduce noise and structural bias.




