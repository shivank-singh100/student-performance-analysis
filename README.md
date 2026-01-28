# 📊 Student Performance Analysis

Exploratory data analysis to understand how factors like parental education and test preparation influence students scores

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-orange)

## 📖 Overview

This project analyzes a dataset of students' test scores to understand how various factors such as parental education, test preparation courses, and potential study habits impact performance. The analysis is presented in a beginner-friendly Jupyter Notebook with clear explanations and visualizations.

## 📂 Dataset

The dataset used is `StudentsPerformance.csv`, which includes the following features:

- **Gender**: Female/Male
- **Race/Ethnicity**: Group A - E
- **Parental Level of Education**: Education background of parents
- **Lunch**: Type of lunch (Standard/Free/Reduced)
- **Test Preparation Course**: Completed/None
- **Scores**: Math, Reading, and Writing

## 🚀 Getting Started

### Prerequisites

Ensure you have Python installed along with the following libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/student-performance-analysis.git
    cd student-performance-analysis
    ```

2.  **Launch Jupyter Notebook:**

    ```bash
    jupyter notebook
    ```

3.  **Open the notebook:**
    Click on `student_performance_analysis.ipynb` to view and run the analysis.

### ☁️ Google Colab

Run the notebook directly in your browser (no installation required):

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1wxyuxUOJaaU_QHK6C3ZVLWUQuiqBA7Y1?usp=sharing)

## 📈 Key Insights

Based on the analysis, several trends emerged:

1.  **Reading & Writing Correlation**: There is a very high correlation (~0.95) between reading and writing scores. Students proficient in one are likely to excel in the other.
2.  **Parental Education**: Higher parental education levels (Bachelor's, Master's) are consistently associated with higher average student scores across all subjects.
3.  **Test Preparation**: Students who completed the test preparation course showed higher median scores and a lower variance (fewer low scores), particularly in Math.
4.  **Content Areas**: Math scores were generally lower on average compared to reading and writing scores.
5.  **Demographic Variations**: Performance trends varied across gender and distinct racial/ethnic groups, highlighting diverse areas for educational support.
6.  **Study Habits**: Consistent trends throughout the data reinforce the importance of study habits and preparation courses.

## 🛠️ Technologies Used

- **Python**: Core programming language.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib & Seaborn**: For creating static, quality visualizations.
- **Jupyter Notebook**: Interactive environment for code and narrative.

## 🤝 Contributing

Contributions are welcome! If you have suggestions for further analysis or visualizations, please feel free to fork the repo and submit a pull request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
