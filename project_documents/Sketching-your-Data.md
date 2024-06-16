
### Dataset Overview
**Source**: [Titanic dataset](https://www.kaggle.com/datasets/brendan45774/test-file/data)

**Key Attributes**:
- **PassengerId**: Unique ID for each passenger
- **Survived**: Survival indicator (0 = No, 1 = Yes)
- **Pclass**: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name**: Name of the passenger
- **Sex**: Gender of the passenger
- **Age**: Age of the passenger
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

### High-Level Goals
1. **Understand Demographic Factors in Survival Rates**
   - **Goal**: Determine how different demographic factors (e.g., age, gender, class) affected survival rates on the Titanic.
   - **Means**: Data analysis and visualization.
   - **Characteristics**: Age, gender, class, and survival status.
   - **Target Data**: Titanic passenger data.
   - **Workflow**: Data preprocessing -> Exploratory Data Analysis (EDA) -> Visualization.
   - **Roles**: Data analyst, researcher.

2. **Analyze Socioeconomic Factors and Survival Rates**
   - **Goal**: Explore the impact of socioeconomic status, represented by passenger class and fare, on survival rates.
   - **Means**: Statistical analysis and visualization.
   - **Characteristics**: Passenger class, fare, and survival status.
   - **Target Data**: Titanic passenger data.
   - **Workflow**: Data preprocessing -> Statistical analysis -> Visualization.
   - **Roles**: Data analyst, sociologist.

3. **Explore Family Influence on Survival**
   - **Goal**: Investigate whether traveling with family members (siblings/spouses, parents/children) influenced the likelihood of survival.
   - **Means**: Data analysis and visualization.
   - **Characteristics**: Number of siblings/spouses, number of parents/children, and survival status.
   - **Target Data**: Titanic passenger data.
   - **Workflow**: Data preprocessing -> EDA -> Visualization.
   - **Roles**: Data analyst, social scientist.

### Low-Fidelity Prototypes

#### Task 1: Understanding Demographic Factors in Survival Rates
- **Why**: To identify patterns in survival rates based on age, gender, and class.
- **How**: By visualizing survival rates across different demographic groups.
- **What**: Differences in survival rates.
- **Where**: Demographic data (age, gender, class).
- **When**: During the exploratory phase of the analysis.
- **Who**: Data analyst, researcher.

**Prototype 1**: Bar chart showing survival rates by gender.
- **Sketch**: A simple bar chart with two bars, one for male and one for female, showing the percentage of survivors.

**Prototype 2**: Box plot of age distribution for survivors and non-survivors.
- **Sketch**: A box plot with age on the y-axis and survival status on the x-axis.

**Prototype 3**: Stacked bar chart for survival rate by passenger class.
- **Sketch**: A stacked bar chart with passenger class on the x-axis and count of passengers (stacked by survived and not survived) on the y-axis.

#### Task 2: Analyzing Socioeconomic Factors and Survival Rates
- **Why**: To explore how wealth and social status affected chances of survival.
- **How**: By analyzing the distribution of fare and class among survivors and non-survivors.
- **What**: The impact of fare and class on survival.
- **Where**: Socioeconomic data (class, fare).
- **When**: During detailed data analysis.
- **Who**: Data analyst, sociologist.

**Prototype 1**: Violin plot of fare distribution by survival status.
- **Sketch**: A violin plot with fare on the y-axis and survival status on the x-axis.

**Prototype 2**: Heatmap of survival rates by class and fare range.
- **Sketch**: A heatmap with class on the y-axis, fare ranges on the x-axis, and color intensity representing survival rates.

#### Task 3: Exploring Family Influence on Survival
- **Why**: To determine if family presence influenced survival rates.
- **How**: By examining survival rates based on family size.
- **What**: The relationship between family size and survival.
- **Where**: Family data (siblings/spouses, parents/children).
- **When**: During hypothesis testing and analysis.
- **Who**: Data analyst, social scientist.

**Prototype 1**: Scatter plot of number of siblings/spouses vs. survival status.
- **Sketch**: A scatter plot with number of siblings/spouses on the x-axis and survival status on the y-axis.

**Prototype 2**: Bar chart showing survival rates by family size (sum of SibSp and Parch).
- **Sketch**: A bar chart with family size on the x-axis and survival rate on the y-axis.

### Visual Critique

1. **Bar chart showing survival rates by gender.**
   - **Works Well**: Clear comparison of survival rates between genders.
   - **Needs Improvement**: Adding percentages could enhance readability.

2. **Heatmap of survival rates by class and fare range.**
   - **Works Well**: Effective at showing correlation between socioeconomic status and survival.
   - **Needs Improvement**: May need a clear legend and color scale to interpret values correctly.

### Next Steps
1. **Create Visualizations**: Develop the outlined low-fidelity prototypes using Altair.
2. **Refine Prototypes**: Based on feedback, refine the prototypes to ensure clarity and effectiveness.
3. **Conduct Analysis**: Use the visualizations to answer the key questions identified for the dataset.