## Exploratory Data Analysis Project : Wine Quality

**Data Set Information:**

The two datasets (winequality-red.csv and winequality-white.csv) are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult: [https://archive.ics.uci.edu/ml/datasets/Wine+Quality].

Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are many more normal wines than excellent or poor ones). Outlier detection algorithms could be used to detect the few excellent or poor wines. Also, we are not sure if all input variables are relevant. So it could be interesting to test feature selection methods.


**Target**

`Our goal is to conduct an exploratory data analysis` (EDA) and uncover insightful findings, such as identifying variables that positively or negatively impact wine quality.

**Attribute Information**

**Input variables (based on physicochemical tests):**

* 1 - fixed acidity:The majority of acids found in wine are either fixed or non-volatile, meaning they do not easily evaporate.
* 2 - volatile acidity: High levels of acetic acid in wine can cause an unpleasant vinegar taste.
* 3 - citric acid: In small quantities, citric acid can contribute to the fresh taste and flavor of wines.
* 4 - residual sugar: The level of sweetness in a wine is determined by the amount of sugar left after fermentation. (Wines with less than 1 gram per liter are rare, while those with more than 45 grams per liter are considered sweet.)

* 5 - chlorides : The amount of salt in the wine.
* 6 - free sulfur dioxide: he free form of SO2 in wine exists in equilibrium between molecular SO2, as a dissolved gas, and bisulfite ion (This equilibrium helps prevent microbial growth and oxidation in the wine.)

* 7 - total sulfur dioxide: The amount of free and bound SO2 in wine can vary, and low levels of SO2 are usually imperceptible. However, when free SO2 levels rise above 50 ppm, it can affect the smell and taste of the wine.

* 8 - density: The density of wine depends on its alcohol and sugar levels, but is typically close to that of water.
* 9 - pH: The pH scale is used to describe the acidity or basicity of wine, with a range of 0 (very acidic) to 14 (very basic). Most wines have a pH between 3 and 4.

* 10 - sulphates: Sulfur dioxide (SO2) is an additive commonly used in wine production as an antimicrobial and antioxidant, and can contribute to the overall SO2 levels in the wine.

* 11 - alcohol: The alcohol percentage of the wine.

**Output variable (based on sensory data):**

* 12 - quality (score between 0 and 10): Target variable based on sensory data, scored on a scale from 0 to 10. Represents the wine's quality according to this standard.

