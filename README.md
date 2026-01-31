<h1 align="center">🌦️ Weather Temperature Prediction using Machine Learning 📈</h1>

<p align="center">
  <img src="https://img.icons8.com/color/96/cloud.png"/>
  <img src="https://img.icons8.com/color/96/artificial-intelligence.png"/>
  <img src="https://img.icons8.com/color/96/python.png"/>
</p>

<p align="center">
  <b>A clean, beginner-friendly Machine Learning project for weather forecasting using regression</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Machine%20Learning-Regression-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Python-3.x-yellow?style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikit-learn"/>
</p>

<hr>

<h2>🚀 Project Overview</h2>

<p>
This project implements a <b>Weather Temperature Prediction System</b> using
<b>Machine Learning regression techniques</b>.
</p>

<p>
Historical weather data is analyzed to predict the <b>next day’s maximum temperature</b>,
demonstrating a complete end-to-end ML workflow.
</p>

<p>
Technologies used include <b>Python, Pandas, NumPy, Matplotlib, and Scikit-learn</b>,
with focus on data preprocessing, feature engineering, model training, and evaluation.
</p>

<ul>
  <li>🎓 College mini / major project</li>
  <li>💡 Beginner-friendly ML workflow</li>
  <li>📊 Time-series regression</li>
  <li>💼 Portfolio-ready GitHub project</li>
</ul>

<hr>

<h2>🧠 Problem Statement</h2>

<p>
Weather forecasting is essential for agriculture, disaster preparedness, and daily planning.
</p>

<p>
Manual analysis of historical weather data is complex and time-consuming.
</p>

<p>
👉 <b>Machine Learning helps identify patterns in past weather data to predict future temperatures.</b>
</p>

<hr>

<h2>📂 Dataset Information</h2>

<p>
The project uses a processed dataset:
<b><code>weather_processed.csv</code></b>
</p>

<table border="1" cellpadding="8" cellspacing="0">
<tr><th>Column</th><th>Description</th></tr>
<tr><td>📅 date</td><td>Date of observation</td></tr>
<tr><td>🌡️ tmax</td><td>Maximum temperature</td></tr>
<tr><td>❄️ tmin</td><td>Minimum temperature</td></tr>
<tr><td>🌤️ tavg</td><td>Average temperature</td></tr>
<tr><td>❄️ snwd</td><td>Snow depth</td></tr>
<tr><td>🎯 target</td><td>Next day maximum temperature</td></tr>
<tr><td>📊 rolling features</td><td>Rolling & expanding mean features</td></tr>
</table>

<hr>

<h2>🛠️ Technologies Used</h2>

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge"/>
</p>

<hr>

<h2>🧠 Methodology</h2>

<ul>
  <li>📥 Load historical weather data</li>
  <li>🧹 Handle missing values using forward fill</li>
  <li>📐 Feature engineering (rolling & expanding means)</li>
  <li>📅 Convert date column into time-series index</li>
  <li>🤖 Train <b>Ridge Regression</b> model</li>
  <li>🔁 Perform rolling backtesting</li>
  <li>📉 Evaluate using Mean Absolute Error (MAE)</li>
</ul>

<hr>

<h2>▶️ How to Run the Project</h2>

<pre>
1️⃣ Clone the repository
git clone https://github.com/Nandan0402/weather-prediction-ml.git

2️⃣ Navigate to the project directory
cd weather-prediction-ml

3️⃣ Install required libraries
pip install pandas numpy scikit-learn matplotlib

4️⃣ Run the model
python model/weather_model.py
</pre>

<hr>

<h2>📈 Model Evaluation</h2>

<ul>
  <li>📊 Mean Absolute Error (MAE)</li>
  <li>📉 Actual vs Predicted temperature plots</li>
  <li>🔁 Rolling backtesting evaluation</li>
</ul>

<p>
Lower MAE indicates better prediction accuracy.
</p>

<hr>

<h2>🎯 Learning Outcomes</h2>

<ul>
  <li>Time-series data handling</li>
  <li>Feature engineering techniques</li>
  <li>Regression model implementation</li>
  <li>Model evaluation methods</li>
  <li>End-to-end ML project experience</li>
</ul>

<hr>

<h2>📌 Use Cases</h2>

<ul>
  <li>🎓 Academic project submission</li>
  <li>🌾 Agricultural planning</li>
  <li>📊 Weather trend analysis</li>
  <li>💼 Entry-level ML portfolio</li>
</ul>

<hr>

<h2>👤 Author</h2>

<p align="center">
  <img src="https://avatars.githubusercontent.com/Nandan0402" width="120" style="border-radius:50%"/>
</p>

<p align="center">
<b>Nandan B</b><br>
BCA Student | Machine Learning Enthusiast
</p>

<p align="center">
🌐 <a href="https://github.com/Nandan0402">GitHub</a> |
💼 <a href="https://www.linkedin.com/in/nandan-b-2a9b1b334/">LinkedIn</a>
</p>

<hr>

<h2>⭐ Conclusion</h2>

<p>
This project focuses on strong Machine Learning fundamentals with a clean and
traditional approach to weather-based regression problems.
</p>

<p>
⭐ If you find this project useful, please star the repository.
</p>

<h2>📁 Project Structure</h2>

<pre>
weather-prediction-ml/
│
├── data/
│   └── weather_processed.csv
│
├── model/
│   └── weather_prediction.ipynb
└── README.md
</pre>
