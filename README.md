# Basketball Player Statistics Analysis

## 📌 Project Overview
This project involves analyzing basketball player statistics to uncover insights about their performance and demographic details. The dataset includes both numerical and categorical data, enabling detailed exploration, visualization, and statistical analysis.

---

## 📊 Dataset Description
The dataset comprises the following columns, grouped into **categorical** and **numerical** features:

### **Categorical Variables**
- **League**: The league in which the player participated.
- **Season**: The season of the statistics.
- **Stage**: The stage of the season (e.g., playoffs, regular season).
- **Player**: The name of the player.
- **Team**: The player's team.
- **Nationality**: The player's country of origin.
- **High_School**: High school attended by the player.
- **Draft_Round**: The draft round in which the player was picked.
- **Draft_Pick**: The pick number in the draft.
- **Draft_Team**: The team that drafted the player.

### **Numerical Variables**
- **GP**: Games played.
- **MIN**: Minutes played.
- **FGM**: Field goals made.
- **FGA**: Field goals attempted.
- **3PM**: Three-pointers made.
- **3PA**: Three-pointers attempted.
- **FTM**: Free throws made.
- **FTA**: Free throws attempted.
- **TOV**: Turnovers.
- **PF**: Personal fouls.
- **ORB**: Offensive rebounds.
- **DRB**: Defensive rebounds.
- **REB**: Total rebounds.
- **AST**: Assists.
- **STL**: Steals.
- **BLK**: Blocks.
- **PTS**: Points scored.
- **Birth_Year**: The year the player was born.
- **Birth_Month**: The month the player was born.
- **Birth_Date**: The day the player was born.
- **Height / Height_cm**: Player's height (in inches and centimeters).
- **Weight / Weight_kg**: Player's weight (in pounds and kilograms).

---

## 🛠️ Analysis Workflow

### 1. **Preparing the Dataset**
- Importing the dataset and required libraries.
- Initial examination of data structure, types, and basic statistics.

### 2. **Data Overview and Inspection**
- Inspecting data dimensions and variable distributions.
- Identifying the proportion of categorical and numerical variables.

### 3. **Basic Information**
- Displaying first few rows of the dataset.
- Summary statistics for numerical variables.
- Unique value counts for categorical variables.

### 4. **Missing Data Analysis**
- Quantifying missing values in the dataset.
- Evaluating the percentage of missing data for each variable.

### 5. **Visualizing Missing Data**
- Visualizing missing data patterns using heatmaps and bar charts.

### 6. **Handling Missing Data**
#### a) **Deleting Missing Data**
- Dropping rows or columns with excessive missing values based on thresholds.

#### b) **Filling Missing Data**
- **Numerical Data**: Imputing with mean, median, or using interpolation.
- **Categorical Data**: Imputing with mode or predicting values using other variables.

### 7. **Categorical Data Analysis**
- Analyzing frequency distributions of categorical variables.
- Exploring key statistics for grouped categories.

### 8. **Relationships Between Categorical and Numerical Data**
- Studying associations between team-based statistics and individual performance.
- Using statistical tests like ANOVA or visualizations to explore relationships.

### 9. **Visualization**
- **Bar Charts**: Frequency distributions of categorical variables.
- **Histograms**: Distribution of numerical variables (e.g., points scored).
- **Box Plots**: Comparing numerical data across categorical variables (e.g., rebounds by team).
- **Correlation Heatmaps**: Relationships among numerical features.

---

## 🔍 Key Insights
- High-scoring players tend to play for top-performing teams.
- Offensive rebounds have a stronger impact on overall scoring efficiency than defensive rebounds.
- Key metrics like assists and turnovers exhibit league-specific trends.

---

## 🛠️ Tools and Libraries
- **Pandas**: Data manipulation and cleaning.
- **NumPy**: Numerical operations.
- **Matplotlib/Seaborn**: Data visualization.
- **Scikit-learn**: For potential model-building steps.

