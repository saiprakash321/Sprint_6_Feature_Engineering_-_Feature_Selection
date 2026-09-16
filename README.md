# Sprint_6_Feature_Engineering_-_Feature_Selection
Feature Engineering &amp; Feature Selection for AI/ML Engineers using Python, Pandas, NumPy, and Scikit-learn.

# Feature Engineering & Feature Selection – Hotel Booking Demand 🛠️📊🐍


A structured and practical learning journey focused on Feature Engineering and Feature Selection using Python, Pandas, NumPy, and Scikit-learn.

This repository contains my learning, practice, Python implementations, feature engineering notebooks, feature selection techniques, domain-based feature creation, feature leakage analysis, preprocessing workflows, coding exercises, challenges, and assessments completed as part of Sprint 6.

---

## 🎯 Learning Objectives



The main goal of this repository is to build a strong practical understanding of feature engineering and feature selection and learn how to transform raw datasets into meaningful, relevant, and ML-ready features.

- Understand the fundamentals of Feature Engineering.
- Understand the fundamentals of Feature Selection.
- Identify different types of features.
- Create meaningful numerical features.
- Transform numerical features.
- Create and encode categorical features.
- Extract useful features from date and time columns.
- Create aggregation features.
- Create interaction features.
- Perform binning and discretization.
- Perform basic text feature engineering.
- Understand feature cardinality.
- Apply encoding techniques.
- Apply numerical transformations.
- Identify and remove irrelevant features.
- Understand and prevent feature leakage.
- Analyze feature importance.
- Perform feature selection using multiple techniques.
- Understand dimensionality reduction.
- Apply PCA.
- Build Scikit-learn feature engineering pipelines.
- Apply domain knowledge to create meaningful features.
- Compare datasets before and after feature engineering.
- Prepare a final ML-ready feature dataset.
- Apply Feature Engineering and Feature Selection through practical coding exercises and challenges.

---

## 📚 Topics Covered


### Feature Engineering Basics

- Introduction to Feature Engineering
- Importance of Feature Engineering
- Types of Features
- Numerical Features
- Categorical Features
- Date and Time Features
- Text Features
- Feature Creation
- Feature Transformation
- Feature Engineering Workflow

### Numerical Feature Engineering

- Numerical Feature Analysis
- Log Transformation
- Power Transformation
- Yeo-Johnson Transformation
- Handling Skewed Features
- Numerical Feature Transformation
- Creating Derived Numerical Features
- Ratio Features

### Categorical Feature Engineering

[svg](https://github.com/saiprakash321/sprint-6-feature-engineering-feature-selection#categorical-feature-engineering)

- Identifying Categorical Features
- Understanding Categorical Variables
- One-Hot Encoding
- Label Encoding
- Ordinal Encoding
- Target Encoding
- Frequency Encoding
- Handling High-Cardinality Features
- Creating Derived Categorical Features

### Date & Time Feature Engineering



- Converting Data to Datetime
- Extracting Year
- Extracting Month
- Extracting Day
- Day of Week
- Weekend Indicators
- Quarter
- Seasonal Features
- Date-Based Feature Creation

### Aggregation Features



- GroupBy Operations
- Sum Aggregation
- Mean Aggregation
- Count Aggregation
- Minimum and Maximum
- Customer-Level Aggregation
- Hotel-Level Aggregation
- Aggregated Business Features
- Summary Features

### Interaction Features


- Understanding Interaction Features
- Numerical Interactions
- Multiplication-Based Features
- Ratio-Based Features
- Combining Multiple Features
- Business-Oriented Interaction Features
- Capturing Relationships Between Features

### Binning & Discretization


- Understanding Binning
- Continuous to Categorical Conversion
- Equal-Width Binning
- Quantile-Based Binning
- Creating Meaningful Groups
- Discretizing Numerical Features
- Creating Business-Based Categories

### Text Feature Engineering



- Understanding Text Features
- Text Preprocessing
- Text Length
- Word Count
- Character Count
- Basic Text Feature Creation
- Converting Text Information into Numerical Features

### Feature Selection



- Understanding Feature Selection
- Importance of Feature Selection
- Removing Irrelevant Features
- Removing Redundant Features
- Correlation-Based Selection
- Statistical Feature Selection
- Mutual Information
- SelectKBest
- Filter Methods
- Wrapper Methods
- Embedded Methods

### Feature Importance



- Understanding Feature Importance
- Model-Based Feature Importance
- Random Forest Feature Importance
- Ranking Important Features
- Understanding Feature Contribution
- Selecting Useful Features Based on Importance

### Dimensionality Reduction


- Understanding Dimensionality Reduction
- Curse of Dimensionality
- Principal Component Analysis
- PCA
- Principal Components
- Explained Variance
- Feature Dimension Reduction

### Feature Leakage



- Understanding Feature Leakage
- Target Leakage
- Post-Outcome Features
- Identifying Leakage Features
- Leakage Prevention
- Removing Leakage Features
- Preparing Leakage-Free Features

### Feature Engineering Pipeline


- Feature Engineering Pipeline
- Numerical Feature Pipeline
- Categorical Feature Pipeline
- ColumnTransformer
- Scikit-learn Pipeline
- Combining Feature Engineering Steps
- Feature Selection Pipeline
- ML-Ready Feature Pipeline

### Domain Feature Engineering



- Understanding Domain Knowledge
- Hotel Booking Domain
- Business-Oriented Features
- Stay-Based Features
- Guest-Based Features
- Booking-Based Features
- Revenue-Based Features
- Seasonal Features
- Special Request Features
- Domain-Specific Feature Selection

### Before vs. After Feature Engineering


- Dataset Shape Comparison
- Feature Count Comparison
- Original vs. Engineered Features
- Numerical Feature Comparison
- Categorical Feature Comparison
- New Feature Analysis
- Removed Feature Analysis
- Selected Feature Comparison
- ML-Ready Dataset Comparison

### Practical Exercises & Challenges



- Feature Engineering Exercises
- Numerical Feature Exercises
- Categorical Feature Exercises
- Date Feature Exercises
- Aggregation Exercises
- Interaction Feature Exercises
- Binning Exercises
- Feature Selection Exercises
- Feature Importance Exercises
- Feature Leakage Exercises
- PCA Exercises
- Complete Feature Engineering Workflow
- Feature Engineering Mini Challenge
- Mini Assessment

---

## 🛠️ Tools & Technologies



- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Git
- GitHub

---

## 📊 Dataset



**Dataset:** Hotel Booking Demand

The dataset contains information about hotel bookings, including hotel type, booking details, guest information, stay details, market segments, distribution channels, pricing information, special requests, and booking cancellation status.

The target variable used for machine learning preparation is:

**`is_canceled`**

- `0` → Booking not canceled
- `1` → Booking canceled

The dataset is used throughout the sprint to practice feature creation, feature transformation, feature selection, feature importance, feature leakage detection, and preparation of an ML-ready feature dataset.

---

## 📈 Notebook Progress


| **No.** | **Topic** | **Status** |
| --- | --- | --- |
| 01 | Feature Engineering Basics | Completed |
| 02 | Numerical Feature Engineering | Completed |
| 03 | Categorical Feature Engineering | Completed |
| 04 | Date & Time Feature Engineering | Completed |
| 05 | Aggregation Features | Completed |
| 06 | Interaction Features | Completed |
| 07 | Binning & Discretization | Completed |
| 08 | Text Feature Engineering | Completed |
| 09 | Feature Selection | Completed |
| 10 | Feature Importance | Completed |
| 11 | Dimensionality Reduction | Completed |
| 12 | Feature Leakage | Completed |
| 13 | Feature Engineering Pipeline | Completed |
| 14 | Domain Feature Engineering | Completed |
| 15 | Complete Feature Engineering Workflow | Completed |
| 16 | Feature Engineering Mini Challenge | Completed |
| 17 | Mini Assessment | Completed |

---

## 🔍 Feature Engineering Workflow



**Dataset Understanding → Identify Existing Features → Feature Creation → Numerical Features → Categorical Features → Date/Time Features → Aggregation Features → Interaction Features → Binning & Transformation → Feature Leakage Check → Feature Selection → Feature Importance → Dimensionality Reduction → Final ML-Ready Feature Set**

---

## 🏨 Domain Features – Hotel Booking Demand



Meaningful domain-specific features were created using the Hotel Booking Demand dataset.

Examples include:

- `Total_Stay_Nights`
- `Total_Guests`
- `Is_Weekend_Stay`
- `Is_Long_Stay`
- `Booking_Lead_Category`
- `Guests_Per_Night`
- `ADR_Per_Guest`
- `Estimated_Stay_Revenue`
- `Family_Booking`
- `Seasonal_Booking`
- `Special_Request_Rate`
- `Guest_Composition`
- `Arrival_Date`
- `Arrival_DayOfWeek`
- `Is_Weekend_Arrival`
- `LeadTime_ADR_Interaction`
- `Stay_ADR_Interaction`
- `Guests_Stay_Interaction`

These features were evaluated based on their business meaning, ML relevance, and potential leakage risk.

---

## 📋 Key Outcome


Completed the Feature Engineering and Feature Selection learning and practical workflow using the Hotel Booking Demand dataset.

The sprint focused on creating meaningful numerical, categorical, date-based, aggregation, and interaction features, applying transformations and encoding techniques, performing feature selection and feature importance analysis, detecting feature leakage, applying dimensionality reduction, and building complete feature engineering workflows.

The final workflow transforms the raw Hotel Booking Demand dataset into a structured, relevant, leakage-free, and ML-ready feature dataset suitable for machine learning model development.

---

## 👨‍💻 Author


**Saiprakash**
