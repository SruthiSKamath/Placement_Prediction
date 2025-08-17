<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=32&pause=1000&color=36BCF7&center=true&vCenter=true&width=800&repeat=true&lines=%F0%9F%8E%93+Placement+Prediction+%F0%9F%9A%80;%F0%9F%93%8A+Predict+Placements+with+Machine+Learning;%F0%9F%92%B0+Estimate+Salary+Packages;%F0%9F%9A%80+Smart+Career+Guidance"
    alt="Typing SVG"
  />
</p>


📌 Overview

The Placement Prediction project is designed to help students and institutions analyze and predict campus placement outcomes using Machine Learning. By leveraging student academic records, work experience, and MBA specializations, the system predicts whether a candidate is likely to be placed and, if placed, estimates the salary package.

This project provides insights into the factors influencing placements and demonstrates how ML can support career guidance and decision-making.

📂 Dataset

The dataset contains 215 student records with the following attributes:

Feature	Description	Example
gender	Gender of student	M / F
ssc_p	Secondary Education percentage	67.00
ssc_b	Board of education (SSC)	Central / Others
hsc_p	Higher Secondary percentage	91.00
hsc_b	Board of education (HSC)	Central / Others
hsc_s	Higher Secondary specialization	Science / Commerce / Arts
degree_p	Degree percentage	77.48
degree_t	Degree type	Sci&Tech / Comm&Mgmt / Others
workex	Work experience	Yes / No
etest_p	Employability test percentage	86.5
specialisation	MBA specialization	Mkt&HR / Mkt&Fin
mba_p	MBA percentage	66.28
status	Placement status	Placed / Not Placed
salary	Annual salary offered	270000.0

✨ Target Variables:

Placement Status (Classification Task) → Placed or Not Placed

Salary Prediction (Regression Task) → Salary (if placed)

🧠 Machine Learning Approach
🔹 Problem Formulation

Binary Classification → Predict whether a student will be placed.

Regression → Predict salary for placed students.

🔹 Models Used

Logistic Regression

Decision Tree Classifier 🌳

Random Forest Classifier 🌲🌲

Gradient Boosting

Linear Regression (for salary prediction)

🚀 Project Workflow
graph TD;
    A[Data Collection 📑] --> B[Data Preprocessing 🧹]
    B --> C[Exploratory Data Analysis 📊]
    C --> D[Feature Engineering ⚙️]
    D --> E[Model Training 🤖]
    E --> F[Placement Prediction ✅❌]
    F --> G[Salary Prediction 💰]

📈 Results

✅ Placement Prediction Accuracy: ~85–90% (varies by model)

💰 Salary Regression R² Score: ~0.70 (good fit for small dataset)

🔑 Key Insights:

Higher degree % and MBA % strongly influence placement chances.

Students with work experience have higher placement probabilities.

Science & Tech backgrounds show slightly better placement outcomes.

📊 Visual Insights
<p align="center"> <img src="https://media.giphy.com/media/26BRuo6sLetdllPAQ/giphy.gif" width="350"> </p>

Some example plots included in the notebook:

Placement vs Degree Percentage

Placement vs Work Experience

Specialization impact on placements

Salary distribution among placed students

⚙️ Tech Stack

🐍 Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

📊 Jupyter Notebook

🔮 Machine Learning (Classification + Regression)

📌 Future Scope

🔹 Deploy as a web app (Streamlit / Flask / Django)

🔹 Add real-time input form for students to check placement chances

🔹 Expand dataset with soft skills & extracurriculars

🔹 Apply Deep Learning models for improved accuracy

🤝 Contributing

Contributions are welcome! 🎉
If you’d like to add features, improve accuracy, or enhance visualizations, feel free to fork this repo and submit a pull request. 
