# MiceClassification
 Classify Mice Data Based on 77 Protein Expression Levels

### 📣 Proposal: Build a Machine Learning Model to classify mice based on their protein expression levels.


**Task 1.** Build BinaryClassification Models to predict Genotype of Mice based on their protein expression levels.

    - Decision Tree 
    
**Task 2.** Build MultiClassification Models to predict Mice Class based on their protein expression levels.

    - Random Forest
    - KNN
    - neural networks (in progress)

**📊 DATA INFORMATION 📊**
- Data and its description(a, b) is from kaggle ➡️ (https://www.kaggle.com/datasets/ruslankl/mice-protein-expression)


**a) Attribute Information**

    [1] Mouse ID

    [2:78] Values of expression levels of 77 proteins; the names of proteins are followed by N indicating that they were measured in the nuclear fraction. For example: DYRK1A_n

    [79] Genotype: control (c) or trisomy (t)

    [80] Treatment type: memantine (m) or saline (s)

    [81] Behavior: context-shock (CS) or shock-context (SC)

    [82] Class: c-CS-s, c-CS-m, c-SC-s, c-SC-m, t-CS-s, t-CS-m, t-SC-s, t-SC-m
    
    
**b) Classes**

    c-CS-s: control mice, stimulated to learn, injected with saline (9 mice)

    c-CS-m: control mice, stimulated to learn, injected with memantine (10 mice)

    c-SC-s: control mice, not stimulated to learn, injected with saline (9 mice)

    c-SC-m: control mice, not stimulated to learn, injected with memantine (10 mice)

    t-CS-s: trisomy mice, stimulated to learn, injected with saline (7 mice)

    t-CS-m: trisomy mice, stimulated to learn, injected with memantine (9 mice)

    t-SC-s: trisomy mice, not stimulated to learn, injected with saline (9 mice)

    t-SC-m: trisomy mice, not stimulated to learn, injected with memantine (9 mice)
    

### ✅ Tasks ✅ 


1. **Data Exploration**: Explore the dataset by calculating descriptive statistics, visualizing the data, and identifying any missing values or outliers. 


2. **Data Preprocessing**: Preprocess the data by scaling the features, imputing missing values, and encoding categorical variables.

3. **Dimensionality Reduction**: is needed since there are over 80 cols
    - PCA
    - t-SNE


4. **Binary Classification**: Classify mice as either control or trisomy based on their protein expression levels. 
    - Decision Trees


5. **Multiclass Classification**: Classify mice into all 8 classes based on their protein expression levels. 
    - random forests, k-nearest neighbors, or neural networks.

